# Contributor Documentation IMMERZA VR
This document is prepared as a roadmap for designers and developers who want to contribute to the IMMERZA VR application

Meditation App for Oculus Quest 2 
![Error](https://github.com/kahveciozan/ImmerzaContributorDoc/blob/main/Immerza.png)
# What is IMMERZA
Immerza is a meditation application that aims to be published first on Applab(Sideqestvr.com) and then on Oculus Official Store.Target devices are Oculus Quest and Quest2. Currently, we have decided to consist of 3 main categories. Focus, Calm and Excitement. You can specify ideas for new category ideas. Each part should consist of 2 or 3 different parts(With different environments).

# Guidelines for Creating Content IMMERZA. Be a Contibutor.
[Click here to become a contributor](https://forms.gle/XvepfJQD45Uu37mT7) <br/>
Immerza were created using the Unity3D Game Engine

## How To Create a New Scene and Environment. (You can upload scene in 3 basic steps)
1. Create and develop your scene in your own project. (Use Unity Version 2021.3.11.X)
2. Build the scene with Addressables.
3. Upload files to the website respectively.

#### Creating and Development in Unity Step by Step

* Decide in which category you want to create a scene(Focus,Calm or Excitement). Then create the scene you imagine.
* Review psychology documents according to the needs of your chosen category. For Calm, For Focus, For Excitement.

1. Create Standart Unity 3D Project
2. Setting up your Project for Mobile VR
> * Files > Build Settings (Ctrl+Shift+B)
> * Select Android
> * Click the Switch Platform Button.

3. Project Setting
> * Build Settings > Texture Compression : ASTC
> * Project Settings > Player > Other Settings > Graphics APIs : Remove Vulkan
> * Project Settings > Player > Other Settings > Target API Level : API Level 23

4. Change the Camera
> * In Hierarchy, Right click > XR > Convert Main Camera To XR Rig

5. If you have import oculus sdk. Add  `OculusInteractionSampleRig.prefab` to Hierarchy. This prefab includes some particle effects(virtual breahing etc.)
6. Now you can desing your original scene. You can add our ready-mate exercises to your own scene. [Prefabs](https://www.exampleprefab.com)

#### Built with Addressables

1. Add Addressables library(Addressable Version 1.19.11.) to your unity project. This is very important. Otherwise there may be problems loading the scenes.
2. Build the scene with Addressable Default Build.
3. Addressables will give 4 files (two .bundle, one json and hash file)
4. Upload these 4 files to the website respectively.

#### Uploading .bunle files to the website

1. Upload these 4 files to the website respectively.
2. Add title and descriptionon website.
3. You can update the scene whenever you want.


# Development Tools and SDKs
[Unity3D Game Engine](https://unity.com/) <br/>
[Oculus Integration SDK](https://assetstore.unity.com/packages/tools/integration/oculus-integration-82022) <br/>
[Adressable Version 1.19.11.] <br/>
[DOTween(HOTween v2)](https://assetstore.unity.com/packages/tools/visual-scripting/dotween-pro-32416) <br/>

## Concepst And Categories
- Decide what category your target scene will be in. There are 3 category offers from the team but you can feel free either to add a new category or contribute a stage in one existing category.
1. *Calm* 
2. *Focus* 
3. *Excitement*

- Be careful not to be too similar to scenes that have been made before. <br/>
- Make sure the gameplay length is longer than 3 minutes and less than 12 minutes.

## Avoid doing these
- Don't add any C# script. (Addressables don't support extenal code)
- Don't change any ready prefabs, you can use it in your scene but never change it.
- Don't call at any time  `Application.Quit()` `SceneManager.LoadScene()` `SceneManager.LoadSceneAsync()`
- Don't delete or modify any files in the project
- Don't use coptright audios, logos , 3D models and any assets.
- Don't use canvas and UI objects.
- Disable hands and controllers.

## Requirements
- Consider the requirements of the category you choose. psychology documents below.
 > - [FOCUS](https://forms.gle/XvepfJQD45Uu37mT7) <br/>
 > - [CALM](https://forms.gle/XvepfJQD45Uu37mT7) <br/>
 > - [EXCITEMENT](https://forms.gle/XvepfJQD45Uu37mT7) <br/>

- [Consider the COLOUR & LIGHTING](https://forms.gle/XvepfJQD45Uu37mT7) <br/>
- [Consider the Sound & Music](https://forms.gle/XvepfJQD45Uu37mT7) <br/>
- [Consider the Mindfulness Principles](https://forms.gle/XvepfJQD45Uu37mT7) <br/>
