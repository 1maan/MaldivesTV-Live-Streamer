# MaldivesTV Live Streamer

Welcome to MaldivesTV Live Streamer! This project allows you to easily access live TV channels from the Maldives through VLC Media Player using a collection of M3U8 stream links.

## Features
- Stream Maldives TV channels directly in VLC Media Player.
- Simple and straightforward setup with pre-configured links.
- Includes links to major Maldivian TV channels.

## Current Channels
1. **Raajje TV**  
   M3U8 Link: [Raajje TV Stream](https://stream.raajje.mv/live/rtv_live/index.m3u8)
   
2. **Maldives TV**  
   M3U8 Link: [Maldives TV Stream](https://live.maldivestv.mv/hls/stream/index.m3u8)
   
3. **SSTV**  
   M3U8 Link: [SSTV Stream](https://sstv.ssplay.mv/hls/sstv-live/index.m3u8)

## Installation

### Download and Install VLC Media Player
- [VLC Media Player](https://www.videolan.org/vlc/) is available for Windows, macOS, Linux, and other platforms. Download and install the version compatible with your operating system.

### Setup the Stream Links
1. Open VLC Media Player.
2. Go to `Media` > `Open Network Stream...`.
3. Copy and paste one of the M3U8 links from the list above into the URL field.
4. Click `Play` to start streaming the channel.

### Create Shortcuts for Convenience
- To simplify future access, you can create a shortcut on your desktop or in your preferred location:
  
  **Windows:**
  1. Right-click on your desktop and select `New` > `Shortcut`.
  2. Paste the M3U8 link into the location field and click `Next`.
  3. Name the shortcut (e.g., "Raajje TV") and click `Finish`.

  **macOS:**
  1. Open `Automator` and create a new `Application`.
  2. Add a `Run Shell Script` action with the following command: `open -a VLC "URL"`, replacing `"URL"` with the M3U8 link.
  3. Save the application with a suitable name and use it to launch VLC with the stream.

## Usage
- Launch VLC Media Player.
- Open the M3U8 link using the methods described above or double-click on your created shortcut.
- Enjoy live streaming of Maldives TV channels.

## Legal Considerations

- **Authorized Streams:** Ensure that the M3U8 links used are from official or authorized sources. Using or sharing unauthorized streams may infringe on copyright laws.
- **Terms of Service:** Review the terms of service or usage policies of the TV channels or streaming services to ensure compliance.
- **Personal Use:** Using these links for personal, non-commercial viewing is generally acceptable. Redistribution or public sharing of unauthorized streams is not permitted.
- **Local Regulations:** Be aware of and adhere to local laws and regulations regarding digital content and streaming.

## Troubleshooting

- **Playback Issues:** Ensure a stable internet connection. If the stream does not load, verify that the M3U8 link is valid or try accessing it through a web browser.
- **VLC Player Errors:** Make sure VLC Media Player is up to date. Consult VLC’s support documentation or forums for additional assistance if needed.

## Contributing

If you have additional channels or improvements to suggest, please feel free to contribute! You can submit pull requests or open issues in the project repository.

## License

This project is provided under the [MIT License](https://opensource.org/licenses/MIT). See the LICENSE file for more details.

---

Thank you for using MaldivesTV Live Streamer. We hope you enjoy seamless access to Maldivian TV channels!
