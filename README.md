# Style Text with Unicode for Raycast

Style text using various Unicode styles like bold, italic, monospace, script, gothic, and more.

## Features

- **Interactive Styler**: Browse and preview all Unicode text styles with live preview
- **Quick Commands**: Individual commands for each style that can be bound to hotkeys
- **Smart Text Handling**: Automatically uses selected text from any app
- **Multiple Actions**: Paste back to app, copy to clipboard, or view details

## Commands

### Style Text with Unicode
Main command with interactive UI where you can:
- Enter or edit text (automatically uses selected text)
- Browse all available Unicode styles
- See large preview of styled text
- View styling details
- Paste directly back or copy to clipboard

### Quick Styling Commands
Each style has its own command that instantly styles selected text:
- Style as Bold
- Style as Italic
- Style as Monospace
- Style as Bold Italic
- Style as Script
- Style as Gothic
- Style as Double-struck
- Style as Sans-serif
- Style as Bold Sans-serif

Bind these to hotkeys for instant styling!

## Available Styles

- **Monospace**: 𝙷𝚎𝚕𝚕𝚘 𝚆𝚘𝚛𝚕𝚍
- **Bold**: 𝐇𝐞𝐥𝐥𝐨 𝐖𝐨𝐫𝐥𝐝
- **Italic**: 𝐻𝑒𝑙𝑙𝑜 𝑊𝑜𝑟𝑙𝑑
- **Bold Italic**: 𝑯𝒆𝒍𝒍𝒐 𝑾𝒐𝒓𝒍𝒅
- **Script**: ℋℯ𝓁𝓁ℴ 𝒲ℴ𝓇𝓁𝒹
- **Bold Script**: 𝓗𝓮𝓵𝓵𝓸 𝓦𝓸𝓻𝓵𝓭
- **Gothic**: ℌ𝔢𝔩𝔩𝔬 𝔚𝔬𝔯𝔩𝔡
- **Gothic Bold**: 𝕳𝖊𝖑𝖑𝖔 𝖂𝖔𝖗𝖑𝖉
- **Double-struck**: ℍ𝕖𝕝𝕝𝕠 𝕎𝕠𝕣𝕝𝕕
- **Sans-serif**: 𝖧𝖾𝗅𝗅𝗈 𝖶𝗈𝗋𝗅𝖽
- **Bold Sans**: 𝗛𝗲𝗹𝗹𝗼 𝗪𝗼𝗿𝗹𝗱
- **Italic Sans**: 𝘏𝘦𝘭𝘭𝘰 𝘞𝘰𝘳𝘭𝘥
- **Bold Italic Sans**: 𝙃𝙚𝙡𝙡𝙤 𝙒𝙤𝙧𝙡𝙙
- **Parenthesis**: ⒣⒠⒧⒧⒪ ⒲⒪⒭⒧⒟
- **Circled**: Ⓗⓔⓛⓛⓞ Ⓦⓞⓡⓛⓓ
- **Circled Negative**: 🅗🅔🅛🅛🅞 🅦🅞🅡🅛🅓
- **Squared**: 🄷🄴🄻🄻🄾 🅆🄾🅁🄻🄳
- **Squared Negative**: 🅷🅴🅻🅻🅾 🆆🅾🆁🅻🅳
- **Fullwidth**: Ｈｅｌｌｏ Ｗｏｒｌｄ

## Installation

### From Raycast Store
Search for "Style Text with Unicode" in Raycast Store (coming soon)

### Manual Installation
1. Clone or download this repository
2. Navigate to the extension directory
3. Run `npm install` or `pnpm install`
4. Run `npm run dev` to develop or `npm run build` to build
5. Import in Raycast: Open Raycast → Extensions → Add Extension → Select this directory

## Development

```bash
# Install dependencies
npm install
# or
pnpm install

# Start development mode
npm run dev

# Build for production
npm run build

# Lint
npm run lint

# Fix linting issues
npm run fix-lint
```

## How It Works

This extension uses Unicode's Mathematical Alphanumeric Symbols block (U+1D400–U+1D7FF) to create styled text. Instead of using formatting (like HTML `<bold>` tags or CSS styles), it uses actual Unicode characters that look bold, italic, etc.

This means the styled text:
- Works anywhere: social media, messaging apps, plain text files
- Copies and pastes perfectly
- Doesn't require special fonts or rendering
- Is permanent (not just visual styling)

## Credits

Conversion logic based on [toUnicodeVariant](https://github.com/davidkonrad/toUnicodeVariant) by David Konrad.

## License

MIT
