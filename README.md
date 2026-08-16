<p align="center">
  <img src="./assets/readme/hero.svg" width="100%" alt="DeepSeek Harness Visual Handbook: a source-locked 103-page visual guide across 10 chapters">
</p>

<p align="center">
  <strong>Understand the runtime layer that turns a model into a working agent.</strong>
</p>

<p align="center">
  <a href="./chapters/chapter-01.md">Start reading</a> ·
  <a href="./ALL_PAGES.md">Continuous reader</a> ·
  <a href="https://github.com/BeatAPI/deepseek-harness-visual-handbook/releases/latest">Download PDF</a> ·
  <a href="./SOURCES.md">Official sources</a>
</p>

> [!IMPORTANT]
> This is an unofficial, community-made visual guide. It is source-locked to DeepSeek Harness commit [`47f9438`](https://github.com/deepseek-ai/deepseek-harness/commit/47f943859bef60e4160492346772ded9b24f765a), which corresponds to the `dsh@0.1.0-rc.5` developer-preview release. The [official repository](https://github.com/deepseek-ai/deepseek-harness) remains the technical source of truth.

## See the ideas before the implementation details

<p align="center">
  <a href="./chapters/chapter-01.md"><img src="./images/chapter-01/page-02.webp" width="32%" alt="A model is not a working agent"></a>
  <a href="./chapters/chapter-05.md"><img src="./images/chapter-05/page-06.webp" width="32%" alt="Projection builds the model view from the event log"></a>
  <a href="./chapters/chapter-06.md"><img src="./images/chapter-06/page-12.webp" width="32%" alt="One complete agent turn from input claim to turn end"></a>
</p>

DeepSeek Harness is more than a model wrapper. It composes the model adapter, tool registry, session log, agent loop, permissions, and product entry points as replaceable runtime capabilities. This handbook turns those relationships into a visual learning path instead of duplicating the official documentation as another wall of text.

## Choose a chapter

<table>
  <tr>
    <td width="50%"><a href="./chapters/chapter-01.md"><img src="./images/chapter-01/page-01.webp" alt="Chapter 1 cover"></a><br><b>01 · The Missing Layer Around the Model</b><br>8 pages</td>
    <td width="50%"><a href="./chapters/chapter-02.md"><img src="./images/chapter-02/page-01.webp" alt="Chapter 2 cover"></a><br><b>02 · Your First Safe Harness Task</b><br>10 pages</td>
  </tr>
  <tr>
    <td width="50%"><a href="./chapters/chapter-03.md"><img src="./images/chapter-03/page-01.webp" alt="Chapter 3 cover"></a><br><b>03 · Everything Is a Plugin</b><br>11 pages</td>
    <td width="50%"><a href="./chapters/chapter-04.md"><img src="./images/chapter-04/page-01.webp" alt="Chapter 4 cover"></a><br><b>04 · Capability Seams</b><br>9 pages</td>
  </tr>
  <tr>
    <td width="50%"><a href="./chapters/chapter-05.md"><img src="./images/chapter-05/page-01.webp" alt="Chapter 5 cover"></a><br><b>05 · Memory Is an Event Log</b><br>9 pages</td>
    <td width="50%"><a href="./chapters/chapter-06.md"><img src="./images/chapter-06/page-01.webp" alt="Chapter 6 cover"></a><br><b>06 · Inside the Agent Loop</b><br>12 pages</td>
  </tr>
  <tr>
    <td width="50%"><a href="./chapters/chapter-07.md"><img src="./images/chapter-07/page-01.webp" alt="Chapter 7 cover"></a><br><b>07 · Profiles, Presets, and Permissions</b><br>11 pages</td>
    <td width="50%"><a href="./chapters/chapter-08.md"><img src="./images/chapter-08/page-01.webp" alt="Chapter 8 cover"></a><br><b>08 · Subagents and Portable Execution Worlds</b><br>11 pages</td>
  </tr>
  <tr>
    <td width="50%"><a href="./chapters/chapter-09.md"><img src="./images/chapter-09/page-01.webp" alt="Chapter 9 cover"></a><br><b>09 · Introspection, Runtime Extensions, and Compaction</b><br>11 pages</td>
    <td width="50%"><a href="./chapters/chapter-10.md"><img src="./images/chapter-10/page-01.webp" alt="Chapter 10 cover"></a><br><b>10 · From Demo to Production</b><br>11 pages</td>
  </tr>
</table>

## Pick a reading path

| If you want to... | Read |
| --- | --- |
| Understand why a model is not yet an agent | Chapters [1](./chapters/chapter-01.md)–[2](./chapters/chapter-02.md) |
| Build plugins and replace runtime capabilities | Chapters [3](./chapters/chapter-03.md)–[4](./chapters/chapter-04.md), then [9](./chapters/chapter-09.md) |
| Design memory, execution, and governance | Chapters [5](./chapters/chapter-05.md)–[8](./chapters/chapter-08.md) |
| Move from a demo toward production | [Chapter 10](./chapters/chapter-10.md) |

## Source-locked by design

The reference PDFs that inspired the presentation were used only to study visual storytelling. Technical content comes from the official DeepSeek Harness repository at one immutable commit.

- [Chapter-by-chapter official source map](./SOURCES.md)
- [Locked upstream commit](https://github.com/deepseek-ai/deepseek-harness/commit/47f943859bef60e4160492346772ded9b24f765a)
- [Asset and edition manifest](./manifest.json)
- [Independence, accuracy, and third-party notices](./DISCLAIMER.md)

Source drift should produce a new handbook edition, not a silent rewrite of this one.

## Formats

| Format | Use | Distribution |
| --- | --- | --- |
| WebP | Fast GitHub reading | Versioned in this repository |
| PDF | Complete offline handbook with chapter bookmarks | [GitHub Releases](https://github.com/BeatAPI/deepseek-harness-visual-handbook/releases/latest) |
| PNG | Original-resolution master pages | Maintained outside Git history |

The 103 GitHub reading images total about 16 MiB. The PDF is kept out of Git history so clones stay small.

## Corrections and contributions

Found a technical, text, source, or visual problem? Open a correction issue and include the chapter, page, proposed correction, exact locked upstream source, and verification date. See [CONTRIBUTING.md](./CONTRIBUTING.md).

This project welcomes precise corrections and source-drift reports. It does not accept third-party characters, logos, or visual assets without a compatible license.

## License and acknowledgements

Original handbook text and visual material owned by this project are licensed under [CC BY-SA 4.0](./LICENSE.md). Third-party names, trademarks, and referenced visual elements are excluded from that grant; see [DISCLAIMER.md](./DISCLAIMER.md).

DeepSeek Harness is maintained by DeepSeek and released under its own MIT license. README design methodology was informed by [beautify-github-readme](https://github.com/oil-oil/beautify-github-readme).
