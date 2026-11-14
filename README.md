<p align="center">
  <img src=".github/logo.png" width="112" alt="Tiger Media Tools">
</p>

<h1 align="center">Tiger Media Tools</h1>

<p align="center">Speed Batch · Smart Frame · Camera Ingest</p>

<p align="center">
  <a href="https://github.com/tigerlabco-png/tiger-media-tools/releases/download/hub/Tiger-Media-Tools.dmg">
    <img src="https://img.shields.io/badge/%E2%AC%87%20Download%20for%20Mac-F45D00?style=for-the-badge" height="56" alt="Download for Mac">
  </a>
</p>

<p align="center"><sub>Apple silicon Mac (M1 or newer) · macOS 13 Ventura or later · always the latest version</sub></p>

---

## What it is

**Tiger Media Tools** brings Tiger's video tools together in one app. You download only Tiger Media Tools,
sign in once, and install, open and update the other three from inside it:

| App | What it does |
|---|---|
| **Speed Batch** | Processes video in batches: speed ramps, LUTs, exposure, music and rotation, exported in parallel. |
| **Smart Frame** | Pulls full-quality photos out of your videos, in batches, with LUTs and color adjustments. |
| **Camera Ingest** | Brings files straight from the camera to your Mac, over USB or Wi-Fi, into a working folder. |

Each app works on its own, and they are built to work together: Camera Ingest delivers files to a folder, and
Speed Batch and Smart Frame can **watch that folder** and pick up each file as soon as it arrives.

**One plan covers all three apps.** Everything is processed on your Mac. No video is ever uploaded.

### Speed Batch

For delivering many videos with the same treatment, without opening an editor for each one.

- **Queue:** drag in files or whole folders. Each video is analyzed automatically and added to the queue.
- **Speed ramps (curves):** pick a curve per video, or let *Automatic distribution* spread the videos across
  your active curves. Create, duplicate and rename curves in Settings.
- **Automatic frame rate:** the recording frame rate is read from the file (and from Sony's XML). You can set it
  by hand when the camera doesn't record it, as with Canon and Nikon.
- **LUT with intensity** and **exposure** from −2 to +2 EV. The preview shows exactly what will be exported.
- **Music:** keep the original audio, replace it with a track from your library, or remove it.
- **Automatic rotation** for videos shot vertically.
- **Parallel export** with pause, cancel, per-video progress and time remaining for the whole batch.
  With **Export automatically** on, each video is exported as soon as it is ready.
- **Safe with your files:** originals are never deleted or moved, and an exported file is never overwritten
  without asking.

### Smart Frame

For taking photos from video without losing quality.

- **Library** in grid or list view. Import by dragging, clicking, a watched folder, or from Camera Ingest.
- **Frames per video:** choose how many photos to take from each video, or per second of video.
- **Pick a frame by hand:** a player with a scrubber to export the exact frame you want.
- **LUT (0 to 200%), exposure and color adjustments**, with a preview of the result.
- **Full-quality export**, read straight from the original video, with pause and cancel.
- **Duplicate warning** on import. Nothing is ever deleted.

### Camera Ingest

For getting files off the camera without a card reader.

- **Sony:** cameras supported by the Sony Camera Remote SDK, over Wi-Fi or USB. Tested on the ZV-E1, A6700 and
  A7 V (the A7 III does not work).
- **Canon (EOS R)** over USB or Wi-Fi (CCAPI) and **Nikon (Z)** over USB: available, still being tested with real cameras.
- **Fujifilm:** the camera doesn't give computers access to its files. Use a card reader.
- **Automatic import rules:** choose which media types come in on their own, and whether that applies to new
  files, files already on the card, or both.
- A built-in **How to connect a camera** guide, brand by brand.

---

## How to install

1. Click **Download for Mac** above.
2. Open the downloaded file and drag **Tiger Media Tools** into your **Applications** folder.
3. **First launch only:** the apps don't have Apple's paid developer certificate yet, so macOS may say it
   *"can't verify the developer"* or that the app *"is damaged"*. That's expected. Open **Terminal**
   (Applications → Utilities → Terminal), paste this command and press Return:
   ```bash
   xattr -cr "/Applications/Tiger Media Tools.app"
   ```
   It only affects Tiger Media Tools and changes nothing else on your Mac. The apps you install from
   Tiger Media Tools don't need it.
4. Open Tiger Media Tools and click the round account button in the top-right corner.
   - **Already use Speed Batch:** sign in with the same email and password.
   - **New here:** click **Create Account**, fill in your details and confirm through the link sent to your email.
5. Click **Install** on any app. Without an active plan, the plans screen opens: choose **Monthly** or **Annual**,
   pay by **credit card** or **PIX**, and click **Subscribe**. When payment is done, come back and click
   **I've Paid, Check**.
6. With your plan active, click **Install** on Speed Batch, Smart Frame or Camera Ingest, then **Open**.

## Updates

When a new version is out, the app shows **Update** in Tiger Media Tools. You can update right away or keep
opening the version you have. There's no need to come back to this page.

## Account and subscription

- You sign in only in Tiger Media Tools. The three apps share that account and never ask you to log in.
- Each app checks your license when it opens and every hour. Without internet it keeps working for up to
  **7 days** and shows *"Couldn't verify your account"*.
- Each app's menu bar has **Check Account** and **Sign Out**. Signing out of one signs you out of all.
- Payments and cancellation are in the Tiger Media Tools account menu.
- Accounts are personal. Please don't share yours with other people.

## Privacy

- Videos are processed **entirely on your Mac**. Nothing is uploaded.
- Your name, email and subscription are used only for sign-in and access to the apps.
- Payments go through a specialized payment provider. The apps never store your card details.

## FAQ

**macOS says the app is damaged. Is it a virus?**
No. That's the standard warning for apps without Apple's paid certificate. Follow step 3 of *How to install*.

**Does it run on Intel Macs?**
Not yet. Only on Macs with Apple silicon (M1 or newer).

**Do I pay for each app separately?**
No. One plan covers all three.

**Are my original videos changed?**
Never. The apps only read the originals and save results to the folder you choose.

**Can I use it offline?**
Yes, for up to 7 days in a row. After that, connect so the app can check your account.

**How do I get files from Camera Ingest into Speed Batch or Smart Frame?**
In Speed Batch or Smart Frame, turn on **Watch Folder** and point it at the folder Camera Ingest delivers to.

## Support

Found a problem, something confusing, or have a suggestion? Contact the Tiger Media Tools team through the
channel you were given.
