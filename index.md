## About me

11+ years of experience in software development. I love to solve problems and to ship projects. I always try to keep things simple in order to find the practical solutions with the right balance between cost, quality and maintainability.

Please visit my <a target="_blank" href="https://www.linkedin.com/in/dalton-machado-20442b18/">LinkedIn</a> profile to know more about my education, where I worked, job titles etc.

## Projects
Here are some projects that I have worked on before:

- [VR Escape Room Game](#vr-escape-room-game--studio-abacate)
- [Wibx GO](#wibx-go--studio-abacate)

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