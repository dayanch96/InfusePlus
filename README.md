# InfusePlus
<p align="center">
<img src=https://github-production-user-asset-6210df.s3.amazonaws.com/38832025/241606359-e48135e8-147c-4687-a2f8-d2556d5301c9.png?raw=true) />
</p>

## Screenshots

| ![ss1](https://raw.githubusercontent.com/dayanch96/InfusePlus/refs/heads/main/Resources/screenshot1.png) | ![ss2](https://raw.githubusercontent.com/dayanch96/InfusePlus/refs/heads/main/Resources/screenshot2.png) | ![ss3](https://raw.githubusercontent.com/dayanch96/InfusePlus/refs/heads/main/Resources/screenshot3.png) |
| --- | --- | --- |
| ![ss4](https://raw.githubusercontent.com/dayanch96/InfusePlus/refs/heads/main/Resources/screenshot4.png) | ![ss5](https://raw.githubusercontent.com/dayanch96/InfusePlus/refs/heads/main/Resources/screenshot5.png) | ![ss6](https://raw.githubusercontent.com/dayanch96/InfusePlus/refs/heads/main/Resources/screenshot6.png) |


<p align="center">
Enhancer for Infuse iOS app.
</p>

## Features

<details>
  <summary>Premium settings</summary>
  <ul>
    <li>Pro features</li>
    <li>Background playback</li>
  </ul>
</details>

<details>
  <summary>Player settings</summary>
  <ul>
    <li>Play/Pause playback using double tap</li>
    <li>Playback speed settings in context menu</li>
    <li>Volume boost settings in context menu</li>
    <li>Skip to the Next/Previous using long press on rewind buttons</li>
    <li>Speed up playback by long pressing Play/Pause button
      <ul>
        <li>Adjustable playback rate</li>
      </ul>
    </li>
    <li>Tap to playback duration to change between total duration, left duration and exact time when playback ends</li>
    <li>Separated custom skip times for double tap and rewind buttons</li>
  </ul>
</details>

<details>
  <summary>Other settings</summary>
  <ul>
    <li>Ability to set Title and Poster for the player in control center</li>
    <li>Startup tab selection</li>
    <li>New available tweak update notification</li>
    <li>Auto-update localizations</li>
  </ul>
</details>

**Infuse Plus preferences can be found in the Settings tab**

## How to build a Infuse Plus app using Github actions
> [!NOTE]
> If this your first time, complete following steps before starting:
>
> 1. Fork this repository using the fork button on the top right
> 2. On your forked repository, go to **Actions** tab and click **I understand my workflows, go ahead and enable them**.

<ol>
  <li>Click on <strong>Sync fork</strong>, and if your branch is out-of-date, click on <strong>Update branch</strong>.</li>
  <li>Navigate to the <strong>Actions tab</strong> in your forked repository and select <strong>Build Infuse Plus app</strong>.</li>
  <li>Click the <strong>Run workflow</strong> button located on the right side.</li>
  <li>Prepare a decrypted .ipa file <em>(we cannot provide this due to legal reasons)</em>, then upload it to a file provider (e.g., filebin.net, filemail.com, or Dropbox is recommended). Paste the URL of the decrypted IPA file in the provided field.</li>
  <li><span style="color: red; font-weight: bold;">NOTE:</span> Make sure to provide a direct download link to the file, not a link to a webpage. Otherwise, the process will fail.</li>
  <li>Enter the tweak version from the releases (the latest release is selected by default). You can also change the BundleID and Display Name if desired.</li>
  <li>Make sure all inputs are correct, then click <strong>Run workflow</strong> to start the process.</li>
  <li>Wait for the build to finish. You can download the Infuse Plus app from the releases section of your forked repo. (If you can't find the releases section, go to your forked repo and add /releases to the URL, i.e., github.com/user/InfusePlus/releases.)</li>
</ol>