# SiYuan NotoSans Plugin

The font files comes from: [Noto - Google Fonts](https://fonts.google.com/noto), converted from .ttf format to .woff format using [rudymohammadbali/FontConverter](https://github.com/rudymohammadbali/FontConverter).

## Notice

- This plugin may not be compatible with other fonts or Emoji plugins in the bazaar, please disable other fonts or Emoji plugins when using this plugin.
- This plugin first tries to use the system's own NotoSans font, then fallback to the font files in the plugin if can't load font. System font only tested available in Windows system.
- The font files included in this plugin is Variable Font, have some requires on system version, see the general scope below:
  - Computer: Windows 10 (1607+) or macOS 10.13+
  - Mobile Phone: iOS 11+ or Android 8.0+
  - Browser: Chrome 62+, Firefox 62+, Safari 11+, Edge (Chromium)
- If your system doesn't match the requirements above, it is recommended to install the fonts yourself within the system to prevent the use of variable fonts from becoming unavailable.

Since SiYuan note version 3.1.25, there's a problem makes texts can't load when exporting image. And it is fixed in unknown version. If you're using an old version of SiYuan, and can't load text when exporting image, please upgrade SiYuan/downgrade plugin, and let me know what version of SiYuan you are using.

## [ChangeLog](https://github.com/emptylight370/siyuan-ttf-Noto_Sans/blob/main/changelog.md)

- 2025-11-14 Compress image size
- 2025-11-02 Change load method

## Acknowledgments

Template repo: [TCOTC/siyuan-ttf-HarmonyOS_Sans_SC-and-Twemoji](https://github.com/TCOTC/siyuan-ttf-HarmonyOS_Sans_SC-and-Twemoji)
