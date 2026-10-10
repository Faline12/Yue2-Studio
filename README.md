# Yue2 Studio

Yue2 Studio is a free desktop app for generating songs on your own computer.
This repository publishes installers only.

Yue2 Studio is an independent app. It is not made or endorsed by m-a-p or ShugoAI.

## Download

Get the latest installer from [Releases](../../releases).

| Computer | File | How to install |
| --- | --- | --- |
| Windows 64-bit | `Yue2 Studio Setup.exe` | Run the setup and follow the steps |
| Mac with Apple silicon | `Yue2 Studio.dmg` | Open the disk image and move Yue2 Studio to Applications |

The Windows app is unsigned, so SmartScreen may warn you. Choose **More info**, then **Run anyway**.

The Mac app is unsigned. The first time, right-click the app, choose **Open**, then choose **Open** again.

## First launch

The app downloads its engine and model files after you start it. Those files are large and stay on your computer. Your songs and API keys stay in the app's local data folder.

Windows needs an NVIDIA GPU. Mac needs an Apple silicon Mac.

## Models and licenses

The installers do not include the model weights. The app downloads them from their authors' pages.

- Song models are released under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). That license covers the model weights.
- The Windows engine is [audio.cpp](https://github.com/0xShug0/audio.cpp), Apache 2.0, Copyright 2026 ShugoAI LLC. The Mac engine includes [mlx-Yue](https://github.com/vanch007/mlx-Yue), also Apache 2.0.

This repository does not grant a license to use or modify the app's source code.

## Support

If you want to support development, you can [buy a coffee](https://buymeacoffee.com/jandev). The app stays free either way.
