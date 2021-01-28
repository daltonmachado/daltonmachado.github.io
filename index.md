## About me

11+ years of experience in software development. I love to solve problems and to ship projects. I always try to keep things simple in order to find the practical solutions with the right balance between cost, quality and maintainability.

Please visit my <a target="_blank" href="https://www.linkedin.com/in/dalton-machado-20442b18/">LinkedIn</a> profile to know more about my education, where I worked, job titles etc.

## Projects
Here are some projects that I have worked on before:

- [VR Escape Room Game](#vr-escape-room-game--studio-abacate)
- [Wibx GO](#wibx-go--studio-abacate)
- [Darumania](#darumania--blanka-studio)
- [Space Words](#space-words--studio-abacate)
- [Memory Game](#memory-game--studio-abacate)
- [Via Varejo AR/VR](#)

---

### VR Escape Room Game | <a target="_blank" href="http://studioabacate.com.br/">Studio Abacate</a>
`Engine: Unity | Language(s): C# | Platform(s): PC VR`

VR game in which the player has to solve puzzles to escape from a dark morgue. Developed using SteamVR SDK, which makes the game run on every major VR headset. Oculus Rift and HTC Vive were the headsets used for development.

#### What I did in this project
- Overall Game Design and puzzle design;

- Project management;

- Gameplay programming (all object interactions and puzzle validations, generic system for turning objects like keys and handles and pouring/filling system for liquids);

- UI programming for some electronic objects with screens;

- Audio programming (SFX management and playback for a lot of continuous interactions, sharing AudioSources for multiple objects whenever possible);

- Scene setup (interactable objects placement);

- SteamVR setup (input, teleporting, scene loading, skeleton poses and pose interpolation for hands);

- Changes and extensions in SteamVR scripts to fit the project's needs.

<a target="_blank" href="https://daltonmachado.github.io/escape#gifs"><img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/escape/escape_196.gif" width="196">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/escape/escape_key_196.gif" width="196">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/escape/escape_switch-box_30fps_196.gif" width="196">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/escape/escape_pouring_30fps_196.gif" width="196">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/escape/escape_stirrer_30fps_196.gif" width="196">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/escape/escape_radiography_30fps_196.gif" width="196">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/escape/escape_safe_196.gif" width="196">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/escape/escape_heart-monitor_196.gif" width="196">
</a>

_(Click any image to see it larger)_

---

### Wibx GO | <a target="_blank" href="http://studioabacate.com.br/">Studio Abacate</a>
`Engine: Unity | Language(s): C#, JavaScript/Node.js | Platform(s): Android, iOS`

Geolocation-based game with Augmented Reality features made using Mapbox SDK and ARKit/ARCore through Unity's AR Foundation package. Players can walk around the real world to catch frogs in traditional 3D or AR (like in Pokémon GO) and earn cryptocurrency in spots sponsored by brands that use the Wibx platform. Players can also customize their avatars, keep a record of captured frogs and engage in missions to win bonus cryptocurrency or real world goods. Developed for Wibx.

#### What I did in this project
- Game Design;

- Project management, planning and monitoring tasks and deadlines for all team members (myself, a junior developer, a 3D artist and an UI/UX designer) and interacting with Wibx's backend team to define core API features;

- Mentoring and code review for a junior developer who did part of the gameplay and UI programming;

- Gameplay programming (AR mode);

- UI programming (login, loading screen, missions, item pooling for dynamic lists);

- Game systems programming (Mapbox SDK integration and customization, frog spawn system, missions, AssetBundle loading, settings);

- Audio programming (music and SFX playback and management);

- Network programming (integration with game's backend API and Wibx platform API, user authentication, AssetBundle downloading and caching);

- AssetBundle build pipeline setup;

- Mapbox service setup (map styles, datasets and tilesets);

- <a target="_blank" href="https://app.swaggerhub.com/apis-docs/studioabacate/WibxGo-Full/1">Game's REST API</a> design, documentation and implementation (data management and access for frog types, spawn areas, missions, gameplay transactions validation, game settings) using Swagger, Postman, AWS Lambda (Node.js/JavaScript) and API Gateway;

- Game's backend services programming (Mapbox datasets and tilesets update automation);

- Database modeling and setup using AWS DynamoDB;

- Setup and management of other AWS services for the game's backend (IAM roles, S3, CloudFront, CloudWatch, Systems Manager Parameter Store);

- Backend migration between AWS accounts from Studio Abacate to Wibx;

- Demo releases through Unity Cloud Build;

- <a target="_blank" href="https://github.com/aws/aws-sdk-net/pull/1295">Bug fix</a> for AWS SDK.

<a target="_blank" href="https://daltonmachado.github.io/wibxgo#gifs"><img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/wibxgo/wibxgo.gif" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/wibxgo/wibxgo_map.gif" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/wibxgo/wibxgo_dodge.gif" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/wibxgo/wibxgo_catch3.gif" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/wibxgo/wibxgo_profile.gif" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/wibxgo/wibxgo_ar.gif" width="132"></a>

_(Click any image to see it larger)_

---

### Darumania | Blanka Studio
`Engine: Unity | Language(s): C# | Platform(s): Android`

Casual game in which the player has to tap the eyes of Daruma dolls before they fall off the screen. The game has 4 background levels, 10 unlockable characters and 4 power-up types. The player can also watch ad videos to earn coins to play a Gashapon Machine and unlock characters. Blanka Studio is just a name I used to self-publish this game.

Game Art by <a target="_blank" href="https://linktr.ee/lrcouto">Laura Couto.</a>

#### What I did in this project
- Overall Game Design;

- Gameplay programming;

- Audio programming;

- UI setup and programming;

- Localization management using Smart Localization plugin;

- Animations (splash screen, UI, Gashapon Machine);

- Ads integration using Appodeal SDK;

- Unity Analytics setup and tagging;

- Play Store publishing.

<a target="_blank" href="https://daltonmachado.github.io/darumania#gifs">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/darumania/darumania.gif" width="114">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/darumania/blanka.gif" width="114">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/darumania/darumania_gameplay.gif" width="114">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/darumania/darumania_gates.gif" width="114">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/darumania/darumania_characters.gif" width="114">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/darumania/darumania_powerups.gif" width="114">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/darumania/darumania_gashapon.gif" width="114">
</a>

_(Click any image to see it larger)_

---

### Space Words | <a target="_blank" href="http://studioabacate.com.br/">Studio Abacate</a>
`Engine: Unity | Language(s): C# | Platform(s): Android, iOS`

Augmented Reality game made using Vuforia SDK. The enemies in the game have a word in english associated to each one of them and one of these words is shown in portuguese in the HUD, so the player needs to shoot the enemy with the right translated word to score. The player can choose between some different characters and keep best score records. Developed for Pearson's Wizard English School.

#### What I did in this project 
- Overall Game Design;

- Gameplay programming (spawn system, enemy behavior, word display for enemies and HUD, shooting system, SFX playback, scoring, game over conditions, object pooling for enemies, bullets and particles);

- Game systems programming (character selection and persistence, best score persistence, pause, settings, scene loading);

- UI setup and programming (title screen, character selection screen, tutorial screen, HUD, enemy words, game over screen, settings screen, exit screen);

- Design and implementation of all UI animations using tweening, with custom tools that I developed on top of LeanTween plugin;

- Character and enemy movement animations, also using tweening;

- Use of TexturePacker to manually pack sprites in order to improve quality and lower the use of storage and memory on mobile devices.

<a target="_blank" href="https://daltonmachado.github.io/spacewords#gifs">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/space-words/sw_title3.gif" width="200">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/space-words/sw_cs30fps.gif" width="200">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/space-words/sw_hud.gif" width="200">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/space-words/sw_gameplay_30fps.gif" width="200">
</a>

_(Click any image to see it larger)_

---

### Memory Game | <a target="_blank" href="http://studioabacate.com.br/">Studio Abacate</a>
`Engine: Unity | Language(s): C# | Platform(s): Android, iOS`

Augmented Reality game made using Vuforia SDK. A memory game in which the player needs to match a word card with the relative image card for the word. The player can unlock 3 difficult levels and keep best score records. Developed for Pearson's Wizard English School.

#### What I did in this project
- Overall Game Design, although pretty standard in this type of game;

- Gameplay programming (cards display, card selection, hit and miss conditions, win and lose conditions, particles playback, scoring);

- Game systems programming (asset and data management for cards using ScriptableObjects, difficult level unlocking and selection, best score persistence, pause, settings, scene loading);

- Audio setup and programming (mixer and audio effects setup and management, music and SFX playback with audio pronunciation for each card pair);

- UI setup and programming (title screen, difficult level selection screen, tutorial screen, HUD, game over screen, settings screen, exit screen);

- Design and implementation of all UI animations using tweening, with custom tools that I developed on top of LeanTween plugin;

- Card animations, also using tweening;

- Sprite animation setup (animation clip, AnimatorController) for the animated character in game over screen;

- Use of TexturePacker to manually pack sprites in order to improve quality and lower the use of storage and memory on mobile devices.

<a target="_blank" href="https://daltonmachado.github.io/memorygame#gifs">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/memory-game/mg_title.gif" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/memory-game/mg_tutorial.gif" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/memory-game/mg_difficult.gif" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/memory-game/mg_gameplay.gif" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/memory-game/mg_gameover.gif" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/memory-game/mg_exit.gif" width="132">
</a>

_(Click any image to see it larger)_

---

### Via Varejo AR/VR | <a target="_blank" href="http://studioabacate.com.br/">Studio Abacate</a>
`Engine: Unity | Language(s): C#, JavaScript/Node.js | Platform(s): Android, iOS, HTC Vive`

Furniture visualization apps in AR (Kudan SDK) and VR (VRTK on HTC Vive) with heavy use of AssetBundles to provide a catalog of 200+ products. Users can view and interact with furniture in VR in physical stores or download the mobile app to have an AR experience in their homes. Developed for Via Varejo Casas Bahia retail chain.

#### What I did in this project

- AR SDKs tests to define which one would be used in the project (Kudan was the best option in markerless tracking at the time that would run in a large range of devices so I chose it among Vuforia, MAXST, ARToolKit, EasyAR and VOID AR);

- Feature design and implementation (product handling, material change, product dimensions display, doors and drawers interactions);

- AR and VR programming (interacting directly with Kudan and VRTK SDKs to build the user interactions);

- Systems programming (AssetBundle loading, product selection and spawning, favorites, settings, data persistence, camera and sharing API access in Android and iOS through plugins);

- UI setup and programming optimizing dynamic product lists using item pooling;

- Network programming (AssetBundle uploading, downloading and caching, use of AWS SDK for Unity);

- Tools programming (asset pipeline automation, workflow tools for tech artists, AssetBundles build automation using AssetGraph, asset review tools for stakeholders at Via Varejo; all of those custom tools were essential to maintain the service running with daily updates);

- Custom Analytics solution that saves data to AWS DynamoDB to be viewed in QuickSight;

- AWS setup and management (IAM roles, S3, CloudWatch, DynamoDB).

<a target="_blank" href="https://daltonmachado.github.io/viavarejo#gifs">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/via-varejo/vvar_handling_30fps.gif" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/via-varejo/vvar_colors_30fps.gif" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/via-varejo/vvar_ruler_30fps.gif" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/via-varejo/approval_system-1.png" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/via-varejo/approval_system-2.png" width="132">
<img src="https://github.com/daltonmachado/daltonmachado.github.io/raw/main/images/via-varejo/build_system.png" width="132">
</a>

_(Click any image to see it larger)_

---