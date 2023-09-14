# Lil Grotesk

[![][Fontbakery]](https://noirblancrouge.github.io/LilGrotesk/fontbakery/fontbakery-report.html)
[![][Universal]](https://noirblancrouge.github.io/LilGrotesk/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://noirblancrouge.github.io/LilGrotesk/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://noirblancrouge.github.io/LilGrotesk/fontbakery/fontbakery-report.html)
[![][Shaping]](https://noirblancrouge.github.io/LilGrotesk/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/LilGrotesk/fontbakery/overall.json
[GF Profile]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/LilGrotesk/fontbakery/GoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/LilGrotesk/fontbakery/OutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/LilGrotesk/fontbakery/ShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/LilGrotesk/fontbakery/Universal.json

![Cover](https://raw.githubusercontent.com/noirblancrouge/LilGrotesk/master/documentation/images/lil-grotesk.jpg)

Lil Grotesk is a geometric sans serif font family, it is circular in style but with a slightly naive appearance.
It comes in six weights, and a variable version, including multilingual support and openType features.

Lil Grotesk font is perfect for headlines, short texts, posters, logos, branding and more.

![Specimen](https://raw.githubusercontent.com/noirblancrouge/LilGrotesk/master/documentation/images/lil-grotesk-charset.jpg)

## ChangeLog

When you make modifications, be sure to add a description of your changes,
following the format of the other entries, to the start of this section.

27 Jul 2023 (Bastien Sozeau)
- Add glyphs, add variable version, overall cleanup and redesign

04 Feb 2019 (Bastien Sozeau)
- Update License, add real sources

17 Jan 2013 (Bastien Sozeau)
- Initital release.

## Bio

Bastien Sozeau is the founder of NoirBlancRouge, an independent type foundry based in Paris since 2019. Specializing in retail and custom typefaces, Bastien has crafted unique fonts for renowned brands such as Kipling, Christian Louboutin and The Olympic Museum. Beyond their commercial work, NoirBlancRouge has also been actively involved in designing free and open-source typefaces since 2013.

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at [noirblancrouge.github.io/LilGrotesk](https://noirblancrouge.github.io/LilGrotesk).

## License

Developed by [NoirBlancRouge Type Foundry](https://noirblancrouge.com) (Originally distributed by graphic design studio [Uplaod](https://uplaod.fr)), LilGrotesk is open source and licensed under OFL, the SIL Open Font License allows the licensed fonts to be used, studied, modified and redistributed freely as long as they are not sold by themselves.

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
