<p align="center">
    <a href="https://apps.apple.com/us/app/mailtrackerblocker/id6450760473">
      <img width="635px" src="https://is2-ssl.mzstatic.com/image/thumb/PurpleSource126/v4/80/5e/89/805e89f7-5c32-18c9-fed1-2927ad0aecf3/c3e28da9-c084-4416-8b4b-dcb164718ca5_New_Project__U00281_U0029.png/2880x1800bb.png">
    </a>
</p>

**MailTrackerBlocker** is a tracker blocker for Mail. Email marketers and other interests often embed invisible trackers in HTML emails so they can track how often, when and where you open your emails. Enable the included Mail extension to find out who is tracking you and to block spy pixels from your emails.

> [!WARNING]  
> Many users have reported that [[FB12796974] emails take a long time to load](https://github.com/apparition47/MailTrackerBlockerApp/issues/2). This is a bug on Mail's side. If you experience this specific bug, please report it to Apple via Feedback Assistant referencing ticket `FB12796974`.


#### Available in the Mac App Store

[![Mac App Store](Assets/download_mac_app_store.svg)](https://apps.apple.com/us/app/mailtrackerblocker/id6450760473)

#### Free Demo

Try out the latest beta for free. [Enroll on TestFlight here](https://testflight.apple.com/join/cQLJpecQ)!

## Features

- Mail extension.

- Privacy protection: Blocks most spy pixels which may capture your IP address and function as read receipts and more.

- Be informed: Identifies nearly 300 of the most common email marketing vendors.

- Tracker report: See a 30-day overview of blocked trackers in your emails.
  

## Requirements

- macOS Sonoma 14.3 or newer
- Apple Mail


## Usage

<img align="right" src="Assets/mail_settings.png" width="386px">


### How to enable the tracker

1. Open the Mail app.
2. Goto Mail > Settings > Extensions.
3. Check `MailTrackerBlocker` to enable it. If you have multiple message security extensions installed, set "Message security extension" to `MailTrackerBlocker` to ensure trackers are blocked.
4. [Recommended] Goto Mail > Settings > Privacy > disable "Block All Remote Content".


#### Tracking Report

Open the MailTrackerBlocker app or tap the 🧩 jigsaw puzzle icon in Mail that appears over the message pane header (note: the 🧩 jigsaw puzzle icon is hidden if the selected e-mail has an attachment). The Tracking Report shows a rolling 30-day overview of e-mails grouped by tracker along with some frequency statistics.


## FAQ

### Does this work with Mail Privacy Protection?

Yes, even in network environments (e.g. VPN) where Mail Privacy Protection doesn't work, MailTrackerBlocker will still block and identify trackers if you choose to "Load Remote Content".

Note: [Mail Privacy Protection's proxy will still fetch the tracker image, triggering the tracker after an unknown period of time](https://www.mailbutler.io/blog/news/why-apples-mail-privacy-protection-does-not-break-mailbutlers-tracking-feature/). In the period of time before this happens, if you open your email without MailTrackerBlocker, the proxy will fetch the tracking image and trigger the tracker at that moment still letting the tracker know your exact opening time.


## Contact

Feel free to send me a message on [X (Twitter)](https://www.twitter.com/apparition47) or [GitHub](https://www.github.com/apparition47).
