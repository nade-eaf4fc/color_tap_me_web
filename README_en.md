# Color Tap me Image Generator

[日本語](README.md) | [English](README_en.md) | [中文](README_zh.md) | [한국어](README_ko.md)

A browser-based tool to generate X (formerly Twitter) "Tap me" color images.

**→ [Open Tool](https://nade-eaf4fc.github.io/color_tap_me_web/)**

![Screenshot](img/screenshot.png)

---

## Examples

| Before | After 1 (no gamma) | After 2 (gamma = 5) |
|--------|---------|----------|
| ![Before](img/woman_with_a_parasol_-_madame_monet_and_her_son_1983.1.29_short1920.jpg) | ![After1](img/apply_gamma/woman_with_a_parasol_-_madame_monet_and_her_son_1983.1.29_short1920_processed_gamma=0.png) | ![After2](img/apply_gamma/woman_with_a_parasol_-_madame_monet_and_her_son_1983.1.29_short1920_processed_gamma=5.png) |

→ [View Example Tweet](https://x.com/dare_aka2/status/2044358889244885471)

---

## Effect of Gamma Correction

Applying gamma correction helps preserve color information in darker images.

| Without gamma (gamma = 0) | With gamma (gamma = 5) |
|---|---|
| ![gamma=0](img/apply_gamma/woman_with_a_parasol_-_madame_monet_and_her_son_1983.1.29_short1920_processed_gamma=0.png) | ![gamma=5](img/apply_gamma/woman_with_a_parasol_-_madame_monet_and_her_son_1983.1.29_short1920_processed_gamma=5.png) |

---

## How to Use

1. Access the page
2. Drag and drop an image, or click to select a PNG / JPG / WebP file
3. Press the **Process** button
4. Review the After image and click **Save Image** to download
5. Post to X

### Guidelines for X Posts

- Single images display best at **2:1 to 3:4** aspect ratio
- **2048 px or larger** on one side works better
- Over **4096 px** may cause X compression, revealing the colors

---

## Disclaimer

- Due to various factors such as display environment, monitor, OS, and application, results may differ across environments.
- All image processing is performed locally in the browser. Uploaded images are not sent to or stored on any server.
- The creator assumes no responsibility for any damages or disadvantages resulting from the use of this tool.
- This tool uses Google Analytics for access analysis. Google Analytics uses cookies to collect data on site usage. For details, see [Google's Privacy Policy](https://policies.google.com/privacy).

---

## Example image

**Claude Monet**, *Woman with a Parasol – Madame Monet and Her Son* (1875)

- **Source:** National Gallery of Art / Wikimedia Commons
- **Source URL:** https://www.nga.gov/artworks/61379-woman-parasol-madame-monet-and-her-son
- **Original rights status:** Public domain / CC0-provided open-access image
- **Modifications:** Resized for repository example use
- **Credit:** Courtesy National Gallery of Art, Washington

---

## License

MIT License © [@dare_aka2](https://x.com/dare_aka2) & [@nade_eaf4fc](https://x.com/nade_eaf4fc)
