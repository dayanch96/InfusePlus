# InfusePlus
<p>Enhancer for <a href="https://apps.apple.com/us/app/id1136220934">Infuse</a></p>

## Screenshots
<table>
   <tr>
      <td><img src="Resources/screenshot1.png" alt="Screenshot 1" /></td>
      <td><img src="Resources/screenshot2.png" alt="Screenshot 2" /></td>
      <td><img src="Resources/screenshot3.png" alt="Screenshot 3" /></td>
   </tr>
</table>

<details>
  <summary>More screenshots</summary>
  <table>
    <tr>
      <td><img src="Resources/screenshot4.png" alt="Screenshot 4" /></td>
      <td><img src="Resources/screenshot5.png" alt="Screenshot 5" /></td>
      <td><img src="Resources/screenshot6.png" alt="Screenshot 6" /></td>
    </tr>
  </table>
</details>

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

## How to build an Infuse Plus app using Github actions
> [!NOTE]
> If this is your first time, complete following steps before starting:
>
> 1. Fork this repository using the fork button on the top-right
> 2. On your forked repository, go to **Repository Settings** > **Actions**, enable **Read and Write** permissions.

### Step-by-step build process
<li>Click on <strong>Sync fork</strong>, and if your branch is out of date, click on <strong>Update branch</strong>.</li>
<li>Navigate to the <strong>Actions tab</strong> in your forked repository and select <strong>Create Infuse Plus app</strong>.</li>
<li>Click the <strong>Run workflow</strong> button located on the right side.</li>
<li>Prepare a decrypted .ipa file, then upload it to a file provider (e.g., filebin.net, filemail.com, or Dropbox - these are recommended). Paste the URL of the decrypted IPA file in the provided field.</li>
<li><strong>NOTE:</strong> Make sure to provide a <em>direct download link</em> to the file, not a link to a webpage. Otherwise, the process will fail.</li>
<li>Enter the tweak version from the releases (the latest release is selected by default). You can also change the Bundle ID and Display Name if desired.</li>
<li>Make sure all inputs are correct, then click <strong>Run workflow</strong> to start the process.</li>
<li>Wait for the build to finish. After that, you can download the Infuse Plus app from the releases section of your forked repository. (If you can't find the releases section, go to your forked repository and add <em>/releases</em> to the URL, i.e., <em>https://github.com/YOUR_USERNAME/InfusePlus/releases</em>)</li>