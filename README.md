# Notat

**Calm, private notes for Windows.** Notat (Norwegian for *note*) is a small notes app made to sit next to [Kalendar](https://github.com/ecnot/kalendar). It has the same soft glass look, the same themes, and it can even share Kalendar's theme, so the two feel like one family.

Everything stays on your PC. There's no account, no cloud and no tracking.

![Notat with a note open: a cover picture, an icon, folders and highlighted text](docs/screenshots/notat-light.png)

## What it does

- **Write the way you like.** Headings, lists, checklists you can tick off, quotes, links and pictures. Paste or drop a picture straight into a note.
- **Covers and icons.** Give a note a cover (a soft gradient or one of your own pictures) and an emoji. Put the title on the cover for a magazine-like header.
- **Four fonts.** Default, Serif, Mono, and Hand (Patrick Hand) for notes that should feel handwritten.
- **Six heading styles.** Plain, Colour, Tag, Marker, Line, or Icon, with a small icon of your choice beside each heading.
- **A highlighter that matches your theme.** Select some text and pick a colour: three shades of your theme, four contrasting colours chosen to go with it, or your own.
- **Folders with icons.** Pick an icon and a colour for each folder, drag notes into them, and fold the list away when you don't need it.
- **Pin, tag and search.** Pinned notes stay at the top. Search looks through titles, text and #tags.
- **Eight themes, light and dark.** The same pale gradients as Kalendar, with a transparency slider and Windows 11's frosted glass.
- **Same theme as Kalendar.** Switch it on in both apps, and changing the theme in one changes it in the other.
- **English and Norwegian (bokmål).**

<table>
<tr>
<td><img src="docs/screenshots/notat-title-on-cover.png" alt="A note with the title on a green gradient cover, written in the Hand font with Icon headings"></td>
<td><img src="docs/screenshots/notat-dark.png" alt="Dark mode with a blue gradient cover and Line headings"></td>
</tr>
<tr>
<td align="center">Title on the cover, Hand font, Icon headings</td>
<td align="center">Dark mode, Line headings</td>
</tr>
<tr>
<td><img src="docs/screenshots/notat-highlighter.png" alt="The highlighter popover over selected text"></td>
<td><img src="docs/screenshots/notat-style.png" alt="The Style popup with fonts, heading styles, page width and title position"></td>
</tr>
<tr>
<td align="center">The highlighter, in your theme's colours</td>
<td align="center">Style: font, headings, width, title</td>
</tr>
<tr>
<td><img src="docs/screenshots/notat-cover-picker.png" alt="Choosing a gradient cover"></td>
<td><img src="docs/screenshots/notat-folders.png" alt="Choosing a folder's icon and colour"></td>
</tr>
<tr>
<td align="center">Gradient covers, or your own pictures</td>
<td align="center">Folders with icons and colours</td>
</tr>
</table>

![Settings: light or dark, transparency, themes and Same theme as Kalendar](docs/screenshots/notat-settings.png)

## Keyboard

| Keys | What it does |
|---|---|
| Ctrl+N | New note |
| Ctrl+F | Search |
| Ctrl+B, Ctrl+I | Bold, italic |
| Ctrl+Alt+2 | Heading |
| Ctrl+Shift+9 | Checklist |
| Tab, Shift+Tab | Indent a list line, or move it back |
| Ctrl+click | Open a link |
| Esc | Close a popup |

## Privacy

Your notes are kept in `%APPDATA%\Notat` on your PC. Notat only goes online when you ask it to get a picture from a web address. "Same theme as Kalendar" uses a small file on your PC (`%APPDATA%\Kalendar and Notat\shared-theme.json`) and never leaves it.

## Getting Notat

Notat is for Windows 10 and 11. The frosted glass needs Windows 11 version 22H2 or newer; on older versions Notat uses a solid background instead. Installers will be on the [Releases](https://github.com/ecnot/notat/releases) page.

## Thanks

Icons from [Tabler Icons](https://tabler.io/icons) (MIT). The Hand font is [Patrick Hand](https://fonts.google.com/specimen/Patrick+Hand) by Patrick Wagesreiter (SIL Open Font License).
