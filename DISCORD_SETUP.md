# 🎙️ Connecting VoiceDominator to Discord

Follow these steps to send your processed voice from the web dashboard directly into a Discord voice channel.

## 1. Requirement: Virtual Audio Cable
You need a "bridge" to send audio from your browser to Discord.
- Download and install **VB-CABLE Driver**: [Download Link](https://vb-audio.com/Cable/)
- **Note**: Restart your computer after installation.

## 2. Windows Settings (Browser Output)
You must tell Windows to send the browser's audio into the Virtual Cable.
1. Open **Settings** > **System** > **Sound**.
2. Scroll down to **Advanced sound options** > **App volume and device preferences**.
3. Find your browser (Chrome/Edge) in the list.
4. Set its **Output** to **"CABLE Input (VB-Audio Virtual Cable)"**.

## 3. Discord Settings (Microphone Input)
Now, tell Discord to listen to that Virtual Cable.
1. Open **Discord** > **User Settings** (Gear icon).
2. Go to **Voice & Video**.
3. Set **Input Device** to **"CABLE Output (VB-Audio Virtual Cable)"**.
4. Set **Output Device** to your usual **Headphones/Speakers**.

## 4. Final Verification
1. On the VoiceDominator dashboard, turn **Broadcast Mode** to **ON**.
2. Click **INJECT** and start speaking.
3. In Discord, use the "Let's Check" mic test to hear your processed voice.

### 💡 Pro Tips:
- **Echo Cancellation**: Turn this **OFF** in Discord settings for the best effect quality.
- **Hearing Yourself**: Use the **"Hear Myself (Sidetone)"** toggle on the dashboard if you want to monitor your own voice while speaking.
