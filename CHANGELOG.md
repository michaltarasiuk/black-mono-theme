# Change Log

All notable changes to the "black-mono" extension will be documented in this file.

## 1.0.2

- Bracket pair colorization uses a flat gray foreground so “unexpected bracket” pairing does not pick up saturated default reds.
- Bracket pair guides (including mismatched-guide lanes) use translucent grays aligned with indentation guides.
- Symbol highlight overlays use the same subdued gray range as range/hover highlights for Peek and related navigation cues.
- List and Explorer focus outlines use the theme `focusBorder` gray (`#272727`) instead of the default accent (gold/yellow) focus ring.
- Sidebar section chrome: `sideBarSectionHeader.border` and `sideBarStickyScroll` backgrounds and borders blended with `#121212` so the explorer header stays monochrome.
- Chat: neutral `chat.editedFileForeground` and gray slash-command chips; inline chat widget, inline chat diff insert/remove regions, overview ruler, minimap chat-edit markers, and related keys match existing diff and workbench grays.

## 1.0.1

- Patch release extending editor UI colors: bracket pair highlights and bracket matching affordances, overview ruler markers for diagnostics, find matches, and selection highlights, linked (paired tag) editing background, and editor info diagnostic foreground/border—kept within the Black Mono grayscale palette.

## 1.0.0

- Initial release
