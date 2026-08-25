# BrightSign Model Package (BSMP) Demo using a BA:connected Presentation

This demo BA:con presentation showcases the tech behind the NPU that is enabled in Brightsign players.  This demo shows:

- Full motion video playing as an attract loop
- If one person is looking at the screen, a pizza video plays
- If more than one person is looking at the screen, a salad video plays

> **Looking for a complete solution?**
> [**Argus**](https://github.com/brightsign/argus-audience-measurement-extension) is BrightSign's
> reference audience-measurement application: person counting, gaze detection, dwell time,
> entry/exit events, and movement analytics, published over MQTT and Prometheus. This repository
> is a single-purpose example of one piece of that system.
>
> *For production audience analytics rather than a demo presentation, use Argus.*

## Building 

To use this you will need to have BrightAuthor:connected (BA:connected) installed.  You can open the presentation in the [preso](./preso/) folder.

Media for this presentation is in the [media](./media) folder.

## Ensure the BSMP is Installed

If your player needs the extension installed, download the latest
[gaze detection BSMP](https://github.com/brightsign/brightsign-npu-gaze-extension/releases/latest),
place the `.bsfw` file on the root of the SD card, and it will be installed automatically on the
next boot.


## Licensing

This project is released under the terms of the [Apache 2.0 License](./LICENSE.txt).

