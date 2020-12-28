# Chuvash Keyboard Layout for Mac OS
Chuvash Keyboard Layout (Input Source) is created using Ukulele according the steps described in [Salvatore Testas blog post](https://saltesta.com/hack/customizing-mac-input-source-icon/).


![Choosing Chuvash Input source](../docs/img/cv-kbd-mac-000.png?raw=true)

## How to install

Follow the instructions provided in the [`docs` section](../docs/setup-en.md#mac). 
The installation has been tested on macOS 10.11 (El capitan) - 11.0 (Big Sur).  

## Design principles

* It should support Chuvash
* It should facilitate the digitalization of Ašmarin's dictionary (with all the special characters)
* It should enable an easy input in other Cyrillic-based languages like Tatar, Udmurt, Mari, Bashkir, Sakha, Erzyan, Mokshan, Tuva etc. 
* It should work on both ISO and ANSI keyboard layouts (meaning the AB00 key should duplicated or avoided)

## Layout

The layout is the same as the one for Windows. Instead of AltGR, on Mac we can use Option (left and right) to type ӐӑӖӗҪҫӲӳ. Details about the layout are in the [ChuvashKeyboardOSX.pdf file](ChuvashKeyboardOSX.pdf)

## Option Modifier
|Symbol|Keys|Description|
|------|----|-----------|
|ӑ|<kbd>⌥</kbd>-а|Cyrillic a with breve, press <kbd>⇧</kbd> to capitalize|
|ӗ|<kbd>⌥</kbd>-е|Cyrillic e with breve|
|ҫ|<kbd>⌥</kbd>-с|Cyrillic s with cedilla|
|ӳ|<kbd>⌥</kbd>-у|Cyrillic u with double acute|
|ү|<kbd>⌥</kbd>-к|Cyrillic ue|
|њ|<kbd>⌥</kbd>-н|Nje|
|ҥ|<kbd>⌥</kbd>-г|En-ghe|
|ә|<kbd>⌥</kbd>-ш|Cyrillic schwa|
|ө|<kbd>⌥</kbd>-щ|Cyrillic oe|
|'|<kbd>⌥</kbd>-з|Apostroph|
|һ|<kbd>⌥</kbd>-х|Shha|
|ћ|<kbd>⌥</kbd>-в|Tshe|
|◊|<kbd>⌥</kbd>-п|Lozenge|
|†|<kbd>⌥</kbd>-р|Obelisk|
|┐|<kbd>⇧</kbd><kbd>⌥</kbd>-р|Box-drawing character|
|‖|<kbd>⇧</kbd><kbd>⌥</kbd><kbd>\\</kbd>|Magnitude|
|љ|<kbd>⌥</kbd>-л|Lje|
|җ|<kbd>⌥</kbd>-ж|Zhje|
|є|<kbd>⌥</kbd>-э|Ukrainian Ye|
|ђ|<kbd>⌥</kbd>-ч|Dje|
|і|<kbd>⌥</kbd>-и|Cyrillic Dotted I|
|ң|<kbd>⌥</kbd>-т|En with descender|
|ї|<kbd>⌥</kbd>-.|Cyrillic Yi|


## Dead keys

|Dead key|State|Entering|Combinations|
|--------|-----|--------|------------|
|Diaeresis|0|<kbd>⌥</kbd>-<kbd>й</kbd>|ӱёӟӹӓӧӝӵӥ|
|Special|1|<kbd>⌥</kbd>-<kbd>ф</kbd>|үәөҕ|
|Descender|2|<kbd>⇧</kbd><kbd>⌥</kbd>-<kbd>ы</kbd>|қџңҗҳ|
|Cedilla|3|<kbd>⌥</kbd>-<kbd>ы</kbd>|ҫҙ|
|Stroke|4|<kbd>⌥</kbd>-<kbd>я</kbd>|ұҡғҥ|
|Breve|5|<kbd>⌥</kbd>-<kbd>ц</kbd>|ўӗӑо̆|
|Acute|6|<kbd>⌥</kbd>-<kbd>1</kbd>|ќѓ|
|Latin Chuvash|7|<kbd>⌥</kbd><kbd>д</kbd>|ÿĕçă|
|Double Acute|8|<kbd>⇧</kbd><kbd>⌥</kbd><kbd>1</kbd>|ӳ ő (lat)|
|Caron|9|<kbd>⌥</kbd><kbd>м</kbd>|р̌ т̌ Ť (lat)|


## Accented characters

The names of the keyboard keys are from the [ISO 9995 standard](https://en.wikipedia.org/wiki/ISO/IEC_9995#Physical_division_and_reference_grid)

* 

## Support for other languages
2016-11-01 support for Tatar, Bashkir, Udmurt, Mari, Kazakh and Uzbek was added, which is implemented through dead keys. Use keyboard preview to find out how to type these letters.

## CVLat
CVLat is a Latin based Chuvash writing system, formalized by @armuti. It is based on the English alphabet and additional ă ĕ ş š ü. To write them you only need to use the International Extended Keyboard Layout on Mac OS and choose diacritics before printing the main letter.

| Diacritics|Dead Key                | Then|Result|
| ----------|------------------------|-----|------|
| Breve     |<kbd>⌥</kbd><kbd>b</kbd>|a e  |ă ĕ   |
| Cedilla   |<kbd>⌥</kbd><kbd>c</kbd>|s    |ş     |
| Diaeresis |<kbd>⌥</kbd><kbd>u</kbd>|u    |ü     |
| Caron     |<kbd>⌥</kbd><kbd>v</kbd>|s    |š     |
