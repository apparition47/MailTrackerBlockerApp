<p align="center">
    <a href="https://apps.apple.com/us/app/mailtrackerblocker/id6450760473">
      <img width="635px" src="https://is2-ssl.mzstatic.com/image/thumb/PurpleSource126/v4/80/5e/89/805e89f7-5c32-18c9-fed1-2927ad0aecf3/c3e28da9-c084-4416-8b4b-dcb164718ca5_New_Project__U00281_U0029.png/2880x1800bb.png">
    </a>
</p>

**MailTrackerBlocker** is a tracker blocker for Mail. Email marketers and other interests often embed invisible trackers in HTML emails so they can track how often, when and where you open your emails. Enable the included Mail extension to block spy pixels from your emails.

#### Available in the Mac App Store

[![Mac App Store](Assets/download_mac_app_store.svg)](https://apps.apple.com/us/app/mailtrackerblocker/id6450760473)

## Features

- Mail extension.
- Privacy protection: Blocks most spy pixels which may capture your IP address and function as read receipts and more.
  

## Requirements

- macOS Ventura 13 or newer
- Apple Mail


## Usage

<img align="right" src="Assets/mail_settings.png" width="386px">

### How to enable the tracker

1. Open the Mail app.
2. Goto Mail > Settings > Extensions.
3. Check `MailTrackerBlocker (Block-only)` to enable it.

Enabling Mail > Privacy > "Block All Remote Content" with MailTrackerBlocker enabled is redundant; disable "Block All Remote Content" for the best experience.

### (Optional) Advanced Tracker

In your Mail > Settings > Extensions, you may check `MailTrackerBlocker` instead of `MailTrackerBlocker (Block-only)` for a more advanced blocker (can block unindentified spy pixels) with tracker labeling functionality (enabling the Tracker Report). If you have multiple message security extensions installed, set "Message security extension" to `MailTrackerBlocker` to ensure trackers are blocked.

> [!WARNING]
> If you experience **[Mail crashing](https://github.com/apparition47/MailTrackerBlockerApp/issues/1) or [slow attachment email loading](https://github.com/apparition47/MailTrackerBlockerApp/issues/2)**, please disable this `MailTrackerBlocker` extension and enable the `MailTrackerBlocker (Block-only)` extension instead. I've filed these two bugs with Apple (FB12794488, FB12796974) because these will need to be addressed by them (in the form of a macOS update, most likely). I recommend filing your own issues with Apple's [Feedback Assistant](https://feedbackassistant.apple.com) to bring more visibility to these bugs. If you're having trouble starting Mail due to crashing on startup, deleting `~/Library/Mail/V10/MailData/AppExtensionUserPreferences.plist` will disable Mail extensions.

#### Tracking Report

Open the MailTrackerBlocker app or tap the 🧩 jigsaw puzzle icon in Mail that appears over the message pane header (note: the 🧩 jigsaw puzzle icon is hidden if the selected e-mail has an attachment). The Tracking Report shows a rolling 30-day overview of e-mails grouped by tracker along with some frequency statistics.

> [!IMPORTANT]  
> The Tracking Report does not work with the `MailTrackerBlocker (Block-only)` extension.


## FAQ

### Does this work with Mail Privacy Protection?

Yes, even in network environments (e.g. VPN) where Mail Privacy Protection doesn't work, MailTrackerBlocker will still block and identify trackers if you choose to "Load Remote Content".


## Contact

Feel free to send me a message @apparition47 on [Twitter](https://www.twitter.com/apparition47) or [GitHub](https://www.github.com/apparition47).
