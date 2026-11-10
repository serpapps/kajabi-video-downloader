# Kajabi Video Downloader (Browser Extension) | How to Download Kajabi Videos

> Browser extension that downloads Kajabi course and lesson videos as MP4, whether the lesson uses Wistia, Vimeo, Loom or YouTube, on kajabi.com, mykajabi.com and custom-domain schools.

Kajabi Video Downloader is a browser extension for saving the Kajabi lessons you have access to. Kajabi lessons can use different video players; the extension detects the player on the lesson page and saves the video as an MP4 for offline study.

- Download Kajabi lesson videos as MP4
- Works with lessons that use Wistia, Vimeo, Loom or YouTube players
- Works on kajabi.com, mykajabi.com and custom-domain Kajabi sites
- Choose from the qualities the source player provides
- Track progress for each download

<a href="https://www.youtube.com/watch?v=eyUMedWRo2Q" target="_blank">
<img src="https://raw.githubusercontent.com/devinschumacher/uploads/refs/heads/main/images/kajabi-video-downloader-save-videos-before-they-disappear.jpg" width="700px">
</a>

## Links

- :rocket: Get it here: [Kajabi Video Downloader](https://serp.ly/kajabi-video-downloader?via=github)
- :new: Latest release: [GitHub Releases](https://github.com/serpapps/kajabi-video-downloader/releases/latest)
- :question: Help center: [SERP Help](https://help.serp.co/en/)
- :beetle: Report bugs: [GitHub Issues](https://github.com/serpapps/kajabi-video-downloader/issues)
- :bulb: Request features: [Feature Requests](https://github.com/serpapps/kajabi-video-downloader/issues)

## Why Kajabi Video Downloader

Kajabi lessons stream through embedded players such as Wistia, Vimeo, Loom or YouTube, each with its
own way of delivering video, and many Kajabi schools run on their own domain. A generic downloader usually
handles one player, or none of them behind a login.

Kajabi Video Downloader detects the player on the lesson page you have open, handles that provider's
download flow and saves a single MP4.

## Features

- **Multi-player detection**: Wistia, Vimeo, Loom and YouTube lesson players
- **Kajabi domains**: kajabi.com, mykajabi.com and custom-domain lesson pages (allow the site once when asked)
- **Quality selection**: lists the renditions the source player exposes
- **MP4 output**: one standard file for offline playback
- **Download manager**: several downloads at once with progress
- **Private by design**: detection and MP4 generation run in your browser; videos never pass through our servers

### Supported Lesson Players

| Player inside the Kajabi lesson | Supported |
|---|---|
| Wistia | ✅ |
| Vimeo | ✅ |
| Loom | ✅ |
| YouTube | ✅ |

## Supported Browsers

| Browser | Supported |
|---|---|
| Google Chrome | ✅ |
| Microsoft Edge | ✅ |
| Brave | ✅ |
| Opera | ✅ |
| Naver Whale | ✅ |
| Yandex Browser | ✅ |
| Firefox, Safari, mobile browsers | ❌ Not supported |

Works on Windows, macOS and Linux desktops. Every release ships one ZIP per browser
(for example `kajabi-downloader-chrome.zip`).

## How to Download Kajabi Videos (Step-by-Step)

1. Install the extension (see [Installation Instructions](#installation-instructions)) and sign in with your email.
2. Sign in to the Kajabi site and open the lesson.
3. Press play so the lesson's video player loads.
4. Click the extension icon, choose a quality and click **Download**. The MP4 is saved to your Downloads.

**Custom domain?** If the school uses its own web address, the popup asks you to allow the site once.

## Supported Formats

- **Output:** MP4
- **Sources:** Wistia, Vimeo, Loom and YouTube players inside Kajabi lessons
- **Not saved:** captions, transcripts and attachments

## Who It's For

- **Students** who want offline copies of Kajabi courses they bought
- **Coaching clients** keeping recorded sessions
- **Creators** backing up lessons on their own Kajabi site

## Troubleshooting

**The video is not detected**  
Press play first so the player loads, then click the extension again. Refresh if needed.

**Nothing happens on a custom-domain school**  
Click the extension icon on the lesson page and allow the site when asked, then reload.

## Free Trial & Pricing

You get **3 free downloads a week** with no credit card. A **subscription** gives unlimited downloads, with updates included.

- Sign in with your email and a one-time code; no password to create.
- Your free downloads reset every week. In current versions only finished downloads count; a failed or cancelled download does not use one.
- See current plans on the [product page](https://serp.ly/kajabi-video-downloader?via=github).

## Installation Instructions

1. Download the ZIP for your browser from the [latest release](https://github.com/serpapps/kajabi-video-downloader/releases/latest) (for example `kajabi-downloader-chrome.zip`).
2. Unzip it. You get a folder that contains `manifest.json`.
3. Open your browser's extensions page: `chrome://extensions` (Chrome), `edge://extensions` (Edge), `brave://extensions` (Brave), `opera://extensions` (Opera), `whale://extensions` (Whale) or `browser://extensions` (Yandex).
4. Turn on **Developer mode**.
5. Click **Load unpacked** and select the unzipped folder.
6. Pin the extension, click its icon, and sign in with your email and the one-time code we send you.

Prefer a guided setup? The [product page](https://serp.ly/kajabi-video-downloader?via=github) walks you through the same steps.
When a newer version is published, the extension shows an update notice; download the new ZIP from
[GitHub Releases](https://github.com/serpapps/kajabi-video-downloader/releases/latest) and load it the same way.

## FAQ

### How do I download Kajabi videos?

Open the Kajabi lesson page, press play so the video source loads, then click the extension icon and choose the quality you want. The extension handles the provider-specific download flow and saves the file as MP4.

### Which video players are supported?

The common players used inside Kajabi lessons: Wistia, Vimeo, Loom and YouTube, when the video is visible in your session.

### Does it work on Kajabi custom domains?

Yes, in many cases. It works on kajabi.com, mykajabi.com and custom-domain lesson pages that use Kajabi; on a custom domain you allow the site once.

### Can I download a whole Kajabi course at once?

No. The extension downloads lesson by lesson, with several downloads running at once in the download manager. It is not a full-course bulk exporter.

### What quality can I download?

Quality depends on the lesson's video player. The extension lists the renditions the source exposes and lets you choose.

### Does it download subtitles or transcripts?

No. It saves the video. Captions, transcripts and attachments should be saved from the course platform.

### Which browsers are supported?

Chrome, Edge, Brave, Opera, Whale and Yandex on Windows, macOS and Linux. Firefox, Safari and mobile browsers are not supported.

### Is there a free trial?

Yes. You get **3 free downloads a week** with no credit card. A **subscription** gives unlimited downloads, with updates included.

## Notes

- Only download content you own or have permission to save.
- The extension works with videos your own account can already watch in the browser. It does not unlock paid, private or locked content.
- Quality depends on what the source player serves; the extension cannot make a video sharper than the original.
- Site updates can affect detection. If something stops working, [open an issue](https://github.com/serpapps/kajabi-video-downloader/issues) and include the page type (not private links).

## License

This repository is distributed under the proprietary SERP Apps license in the [LICENSE](LICENSE) file. Review that file before copying, modifying, or redistributing any part of this project.

## Related

- [Thinkific Video Downloader](https://github.com/serpapps/thinkific-downloader)
- [Teachable Video Downloader](https://github.com/serpapps/teachable-video-downloader)
- [Skool Video Downloader](https://github.com/serpapps/skool-downloader)
- [GoHighLevel Video Downloader](https://github.com/serpapps/gohighlevel-downloader)

## About Kajabi

Kajabi is an all-in-one platform for creators to sell online courses, coaching, memberships and
communities, often on their own domain. Lessons stream in the browser and the Kajabi app without a
download option. Kajabi Video Downloader saves the lessons you have access to.
