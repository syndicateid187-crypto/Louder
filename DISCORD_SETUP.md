# 🎙️ Discord Connection Guide

If you want to send your processed audio from this website to Discord, follow these steps.

## Step 0: Install VB-CABLE (MANDATORY)
If you don't see "CABLE Input" in your settings, you must install the driver first.
1.  **Download**: [VB-Audio Virtual Cable](https://vb-audio.com/Cable/)
2.  **Install**: Extract the ZIP and run `VBCABLE_Setup_x64.exe` as Administrator.
3.  **RESTART**: You **MUST restart your computer** after installation.

## Step 1: Route Browser Audio
1. Open Windows **Sound Settings**.
2. Scroll to **"App volume and device preferences"** (at the bottom).
3. Find your Browser (Chrome/Edge/etc.) in the list.
4. Change the **Output** dropdown to **"CABLE Input (VB-Audio Virtual Cable)"**.

## Step 2: Configure Discord
1. Open Discord **User Settings** > **Voice & Video**.
2. Set **Input Device** to **"CABLE Output (VB-Audio Virtual Cable)"**.
3. **IMPORTANT**: Turn OFF "Echo Cancellation" and "Noise Suppression" in Discord for the best audio quality.

## Troubleshooting
**"CABLE Input" is not in the list?**
- Make sure you ran the installer as Administrator.
- Make sure you have restarted your computer.
- Check if the device is enabled in "Control Panel" > "Sound" > "Playback" tab.

**Can't hear anything in Discord?**
- Make sure "Broadcast Mode" is ON on the website.
- Make sure you have selected the correct input in Discord.
