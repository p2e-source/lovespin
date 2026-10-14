# LoveSpin – Spin Into Love

**One Spin. Endless Surprises.** A standalone couples challenge game made for Play2Earn.world.

[Play LoveSpin online](https://play2earn.world/lovespin/)

![LoveSpin](lovespin-social.jpg)

## Download

- [Complete project and source code](LOVESPIN-complete-project.zip): extract this archive to browse and edit the modular JavaScript, CSS, SVG wheel, challenge library, tests, build script and production files.
- [Ready-to-deploy cPanel build](LOVESPIN-deploy.zip): the actual production files, with index.html at the archive root.
- [Portal upload kit](LOVESPIN-upload-kit.zip): deployment ZIP, cover, banner, screenshots, game metadata and instructions.

The complete source is distributed as a ZIP in this repository. Extract it before running development commands.

## Features

Five moods: Sweet Romance, Laugh Together, Flirty Sparks, Deep Connection and Mystery Mix. Includes 160 core challenges, 16 golden challenges and six cooperative finales, a twelve-segment animated wheel, mystery envelopes, double dares, rare golden spins, shared fictional Love Points, streak bonuses, badges, sound, optional music, saved progress and replay.

Every challenge is optional. Skip and exchange without losing points. Gentle affection requires both partners to opt in; long-distance mode excludes physical challenges. The Love Meter and scores are entertainment, not relationship assessments or cash rewards.

## Deploy

Extract **LOVESPIN-deploy.zip** directly into `public_html/lovespin/`. Open https://play2earn.world/lovespin/ . No Node server, database, account, API key or hosting build step is required. Relative assets keep the game independent from the portal.

For the portal admin: choose locally hosted, slug `lovespin`, category Romance / Couples, age 18+, and upload the deployment ZIP. Use lovespin-cover.jpg as cover and lovespin-social.jpg as featured banner. See [listing copy and SEO](GAME-METADATA.md).

## Develop

Download and extract LOVESPIN-complete-project.zip. Open the extracted `lovespin` directory, then run:

```sh
node build.mjs
node preview.mjs
```

Visit http://127.0.0.1:5230/lovespin/ . Run `node --test src/engine.test.js` for engine verification. No npm dependencies are needed. Details and the Windows launcher are included in the archive.

## Verification

Seven engine test groups passed, including 60,000 wheel-position cases and 2,500 complete simulated sessions. All five modes passed DOM integration checks. Desktop and mobile browser layouts, full gameplay, scoring, consent settings, save/resume and the extracted deployment ZIP were checked. The live deployment was verified after publication. See [QA notes and limits](QA.md).

## Assets and rights

Original SVG/CSS game graphics and promotional artwork created for LoveSpin. DM Sans and its license are included in the source and runtime archives. No third-party vehicle, character or game assets are used. No open-source license is granted for original game code or artwork by this repository; all rights reserved unless the owner adds a license.
