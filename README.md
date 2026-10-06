# Borozdov Kite

A theme from the Borozdov collection. Two faces — light **Pasture**, an open meadow in
morning light, and dark **Hangar**, the same fleet at night. Cream paper, black outlines at
20px, tall condensed headlines and one drone violet for what you act on.

![Borozdov Kite in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/kite/main/screenshots/light.png)

![Borozdov Kite in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/kite/main/screenshots/dark.png)

## Principles

- **Stamped, not set.** The title, the two largest headings and pull quotes are a tall
  condensed bold in capitals with tight leading, like a nature-magazine cover; the
  platform's own sans carries everything else.
- **Cream and a black outline.** The page is meadow cream, never white; callouts, tables,
  embeds, fields and buttons are drawn with a 1px ink outline instead of a fill or a
  shadow.
- **One drone violet.** The plain note is a violet feature block with cream text; violet
  also fills a checked task, a toggle and the open file. Links stay ink with an underline
  and turn violet under the pointer.
- **One radius.** Every corner is 20px: cards, buttons, fields, tags, code, images.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts as outlined cream cards with the title in the type's colour
- Tags and property values as outlined pills that fill violet on hover
- The main button is filled ink with cream text
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Trellis**. Install Borozdov Trellis under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Kite** under Style Settings → Borozdov Trellis → Variant. The variant brings this
theme's palette, type and corners; its own layout, and its embedded font if it has one,
come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/kite/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Kite/`, then choose Borozdov Kite under
Settings → Appearance → Themes.

## Font

Kite Sans is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font License
1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). It is a Latin and Cyrillic subset of Cuprum Bold
(© 2006–2012 Jovanny Lemonad), renamed because a modified copy may not use the original's
Reserved Font Name. One weight, for the title, the two largest headings and pull quotes
only.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Пастбище» — открытый луг в
утреннем свете, и тёмный «Ангар» — тот же парк дронов ночью. Кремовая бумага, чёрные контуры
со скруглением 20px, высокие узкие заголовки капителью (Kite Sans) и один фиолетовый для
того, что вы делаете. В каталоге тема живёт вариантом Borozdov Trellis: установите Borozdov Trellis и плагин Style Settings, затем выберите Kite в Style Settings → Borozdov Trellis → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
