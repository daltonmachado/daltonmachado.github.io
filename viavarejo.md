---
title: Via Varejo AR/VR
permalink: /viavarejo/
---

[← Home page](https://daltonmachado.github.io/)

## Via Varejo AR/VR | <a target="_blank" href="http://studioabacate.com.br/">Studio Abacate</a>
`Engine: Unity | Language(s): C#, JavaScript/Node.js | Platform(s): Android, iOS, HTC Vive`

Furniture visualization apps in AR (Kudan SDK) and VR (VRTK on HTC Vive) with heavy use of AssetBundles to provide a catalog of 200+ products. Users can view and interact with furniture in VR in physical stores or download the mobile app to have an AR experience in their homes. Developed for Via Varejo Casas Bahia retail chain.

### What I did in this project

- AR SDKs tests to define which one would be used in the project (Kudan was the best option in markerless tracking at the time that would run in a large range of devices so I chose it among Vuforia, MAXST, ARToolKit, EasyAR and VOID AR);

- Feature design and implementation (product handling, material change, product dimensions display, doors and drawers interactions);

- AR and VR programming (interacting directly with Kudan and VRTK SDKs to build the user interactions);

- Systems programming (AssetBundle loading, product selection and spawning, favorites, settings, data persistence, camera and sharing API access in Android and iOS through plugins);

- UI setup and programming optimizing dynamic product lists using item pooling;

- Network programming (AssetBundle uploading, downloading and caching, use of AWS SDK for Unity);

- Tools programming (asset pipeline automation, workflow tools for tech artists, AssetBundles build automation using AssetGraph, asset review tools for stakeholders at Via Varejo; all of those custom tools were essential to maintain the service running with daily updates);

- Custom Analytics solution that saves data to AWS DynamoDB to be viewed in QuickSight;

- AWS setup and management (IAM roles, S3, CloudWatch, DynamoDB).

### Videos, GIFs and Screenshots

<iframe width="832" height="466" src="https://www.youtube.com/embed/sHuyqyh-C2s" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="832" height="466" src="https://www.youtube.com/embed/mK8v69T_NZQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
![](https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/via-varejo/vvar_handling_30fps.gif)
![](https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/via-varejo/vvar_colors_30fps.gif)
![](https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/via-varejo/vvar_ruler_30fps.gif)
![](https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/via-varejo/approval_system-1.png)
![](https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/via-varejo/approval_system-2.png)
![](https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/via-varejo/build_system.png)

[← Home page](https://daltonmachado.github.io/) | [↑ Top](#)