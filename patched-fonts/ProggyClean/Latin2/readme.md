The ProggyClean.ttf contains the Latin-1 character set (ISO 8859-1 I think)
The ProggyCleanCE.ttf can be used for the Czech language, but I assume it's just
Latin-2, so you can try it if the caracters you want are missing... and you can read
English enough to understand this readme :)

## Which font?

### TL;DR

* Pick your font family and then select from the `'complete'` directory.
  * If you are on Windows pick a font with the `'Windows Compatible'` suffix.
    * This includes specific tweaks to ensure the font works on Windows, in particular monospace identification and font name length limitations
  * If you are limited to monospaced fonts (because of your terminal, etc) then pick a font with the `'Mono'` suffix.
    * This denotes that the Nerd Font glyphs will be monospaced not necessarily that the entire font will be monospaced

### Explanation

Once you narrow down your font choice of family (`Droid Sans`, `Inconsolata`, etc) and style (`bold`, `italic`, etc) you have 2 main choices:

#### `Option 1: Download already patched font`

 * download an already patched font from the `complete` folder
   * This is most likely the one you want. It includes **all** of the glyphs from all of the glyph sets. Only caution here is that some fonts have glyphs in the _same_ code point so to include everything some had to be moved to alternate code points.

#### `Option 2: Patch your own font`

 * patch your own variations with the various options provided by the font patcher (see each font's readme for full list of combinations available)
   * This is the option you want if the font you use is _not_ already included or you want maximum control of what's included
   * This contains a list of _all permutations_ of the various glyphs. E.g. You want the font with only [Octicons][octicons] or you want the font with just [Font Awesome][font-awesome] and [Devicons][vorillaz-devicons]. The goal is to provide every combination possible in this folder.


For more information see: [The FAQ](https://github.com/ryanoasis/nerd-fonts/wiki/FAQ-and-Troubleshooting#which-font)


[vim-devicons]:https://github.com/ryanoasis/vim-devicons
[vorillaz-devicons]:https://vorillaz.github.io/devicons/
[font-awesome]:https://github.com/FortAwesome/Font-Awesome
[octicons]:https://github.com/primer/octicons
[gabrielelana-pomicons]:https://github.com/gabrielelana/pomicons
[Seti-UI]:https://atom.io/themes/seti-ui
[ryanoasis-powerline-extra-symbols]:https://github.com/ryanoasis/powerline-extra-symbols
[SIL-RFN]:http://scripts.sil.org/cms/scripts/page.php?item_id=OFL_web_fonts_and_RFNs#14cbfd4a


## Variations (Combinations)

> The combinations and total number of combinations are provided here for reference if you want to create your own variation of a patched Nerd Font.

### Why aren't all variations included ?

Combinations are no longer included by default because of the large inflation in size it caused the Repository _and_ the amount of time it takes to rebuild all of the combinations. This issue would exponentially get worse as the numbers of Fonts and Glyph Sets provided increase.


```sh
# 510 Possible Combinations:

./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --octicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontlinux
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesome
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontlinux
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --octicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontlinux
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --windows
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontlinux
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --octicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontlinux
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesome
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontlinux
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --octicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontlinux
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --pomicons
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --powerlineextra
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs --powersymbols
./font-patcher ProggyCleanCE.ttf  --use-single-width-glyphs
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontlinux
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --pomicons
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --octicons
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontlinux
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --pomicons
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesome
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontlinux
./font-patcher ProggyCleanCE.ttf  --windows --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --octicons --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --octicons --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --pomicons
./font-patcher ProggyCleanCE.ttf  --windows --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --octicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --octicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --octicons
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontlinux
./font-patcher ProggyCleanCE.ttf  --windows --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --pomicons
./font-patcher ProggyCleanCE.ttf  --windows --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --powerlineextra
./font-patcher ProggyCleanCE.ttf  --windows --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --windows --powersymbols
./font-patcher ProggyCleanCE.ttf  --windows
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontlinux
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --pomicons
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --octicons
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontlinux
./font-patcher ProggyCleanCE.ttf  --fontawesome --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --fontawesome --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --pomicons
./font-patcher ProggyCleanCE.ttf  --fontawesome --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --powerlineextra
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontawesome --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesome
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --fontlinux
./font-patcher ProggyCleanCE.ttf  --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --octicons --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --octicons --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --pomicons
./font-patcher ProggyCleanCE.ttf  --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --octicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --octicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --octicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --octicons
./font-patcher ProggyCleanCE.ttf  --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontlinux --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontlinux --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontlinux --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontlinux --pomicons
./font-patcher ProggyCleanCE.ttf  --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontlinux --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontlinux --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontlinux --powerlineextra
./font-patcher ProggyCleanCE.ttf  --fontlinux --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontlinux --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --fontlinux --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontlinux
./font-patcher ProggyCleanCE.ttf  --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --pomicons --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --pomicons --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --pomicons --powerlineextra
./font-patcher ProggyCleanCE.ttf  --pomicons --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --pomicons --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --pomicons --powersymbols
./font-patcher ProggyCleanCE.ttf  --pomicons
./font-patcher ProggyCleanCE.ttf  --powerlineextra --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --powerlineextra --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --powerlineextra --powersymbols
./font-patcher ProggyCleanCE.ttf  --powerlineextra
./font-patcher ProggyCleanCE.ttf  --fontawesomeextension --powersymbols
./font-patcher ProggyCleanCE.ttf  --fontawesomeextension
./font-patcher ProggyCleanCE.ttf  --powersymbols
```