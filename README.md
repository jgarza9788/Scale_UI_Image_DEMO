<!--
Version: 1.0

**Change Log**

-->

Scale_UI_Image
-------------------------------------
[Asset Store Link](http://u3d.as/1ZD0)  
© 2017 Justin Garza

PLEASE LEAVE A REVIEW OR RATE THE PACKAGE IF YOU FIND IT USEFUL!
Enjoy! :)

## Table of Contents

<!--TOC-->
- [Scale_UI_Image](#scale_ui_image)
- [Table of Contents](#table-of-contents)
- [Contact](#contact)
- [Description Features](#description-features)
- [Terms of Use](#terms-of-use)
- [Overview/Setup](#overviewsetup)
- [Prefab](#prefab)
    - [standard components](#standard-components)
        - [UpdateMaterial.cs](#updatematerialcs)
        - [scaleUIImage_RoundedEdge](#scaleuiimage_roundededge)
- [Other Scripts](#other-scripts)

<!--TOC-->


## Contact  

Questions, suggestions, help needed?  
Contact me at:  
Email: jgarza9788@gmail.com  
Cell: 1-818-251-0647  
Contact Info: [jgarza9788 - UnityPortfolio](https://github.com/jgarza9788/UnityPortfolio)  


## Description Features

Easily create a cool over effect on images or buttons.

Change:
* Scale
* Lightness
* Tint
* Saturation
Simple and easy 
Based on ShaderGraph (easily modifiable!)

## Terms of Use

Required:
please follow [Unity's EULA](https://unity3d.com/legal/as_terms) 

Suggestion/Optional:
please put my name in the credits, or in the special thanks section. :)  

## Overview/Setup 

Make sure you have the ShaderGraph and URP added from the package manager.

![Imgur](https://i.imgur.com/vb6CuOw.png)

## Prefab 

**Assets\Scale_UI_Image\Prefab\Button.prefab**
### standard components 
* Image 
    * this contains the Material (and thus the shader)
* Button
* Animator
    * this will update the UpdateMaterial.cs (Anim) with controls the Material 
* UpdateMaterial.cs
    * This acts as a bridge to update the Material

![Imgur](https://i.imgur.com/QHgIFnq.png)

#### UpdateMaterial.cs
This allows the animator to control the Anim in the Material.

#### scaleUIImage_RoundedEdge
* Anim  
a float between 0 and 1 to determine at what stang of the animation it's at
* minScale/maxScale  
the scale of the image when Anim is at 0 and 1
* offset0/offset1  
the offset of the image when Anim is at 0 and 1
* lightness0/lightness1  
the lightness of the image when Anim is at 0 and 1
* tint0/tint1  
the tint of the image when Anim is at 0 and 1
* saturation0/saturation1  
the saturation of the image when Anim is at 0 and 1

## Other Scripts
there are other scripts in this package that are used for the demo, and are not needed for the main asset.



<!-- ## FAQs  -->




