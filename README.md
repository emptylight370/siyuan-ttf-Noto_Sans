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

> [!NOTE]
> This plugin modifies the font range: global. Modifies the variable: `--b3-font-family`.
> Compatible with editor font in settings, compatible with other plugins/code snippets that edit other variables.

## [ChangeLog](https://github.com/emptylight370/siyuan-ttf-Noto_Sans/blob/main/changelog.md)

- 2025-11-14 Compress image size
- 2025-11-02 Change load method
- 2026-01-07 Fixed the issue where the non-English language input symbol <code>\`</code> wasn't displayed correctly
- 2026-02-23 Update sponsorship link
- 2026-06-30 Adapt to SiYuan 3.7.0
- 2026-09-05 Adapt to SiYuan 3.8.2, 3.8.3

## Acknowledgments

Template repo: [TCOTC/siyuan-ttf-HarmonyOS_Sans_SC-and-Twemoji](https://github.com/TCOTC/siyuan-ttf-HarmonyOS_Sans_SC-and-Twemoji)

Support development: [Link](https://emptylight370.github.io/sponsor)
