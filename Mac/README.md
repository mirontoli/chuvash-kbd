# Chuvash Keyboard Layout for Mac OS
Chuvash Keyboard Layout (Input Source) is created using Ukulele according the steps described in [Salvatore Testas blog post](https://saltesta.com/hack/customizing-mac-input-source-icon/).


![Choosing Chuvash Input source](../docs/img/cv-kbd-mac-000.png?raw=true)

## How to install

Follow the instructions provided in the [`docs` section](../docs/setup-en.md#mac)

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
|ӑ|<kbd>⌥</kbd>-а|Cyrillic a breve, press <kbd>⇧</kbd> to capitalize|
|ӗ|<kbd>⌥</kbd>-е|.|
|ҫ|<kbd>⌥</kbd>-с|.|
|ӳ|<kbd>⌥</kbd>-у|.|
|ү|<kbd>⌥</kbd>-к|.|
|њ|<kbd>⌥</kbd>-н|.|
|ҥ!|<kbd>⌥</kbd>-г|.|
|ә|<kbd>⌥</kbd>-ш|.|
|ө|<kbd>⌥</kbd>-щ|.|
|'|<kbd>⌥</kbd>-з|.|
|һ|<kbd>⌥</kbd>-х|.|
|ћ|<kbd>⌥</kbd>-в|.|
|◊|<kbd>⌥</kbd>-п|.|
|†|<kbd>⌥</kbd>-р|.|
|┐|<kbd>⇧</kbd><kbd>⌥</kbd>-р|.|
|‖|<kbd>⇧</kbd><kbd>⌥</kbd><kbd>\</kbd>|.|
|љ|<kbd>⌥</kbd>-л|.|
|җ|<kbd>⌥</kbd>-ж|.|
|є|<kbd>⌥</kbd>-э|.|
|ђ|<kbd>⌥</kbd>-ч|.|
|і|<kbd>⌥</kbd>-и|.|
|ң|<kbd>⌥</kbd>-т|.|
|ї|<kbd>⌥</kbd>-.|.|


## Dead keys

|Dead key|State|Entering|Combinations|
|--------|-----|--------|------------|
|Diaeresis|0|<kbd>⌥</kbd>-<kbd>AD01</kbd>|ӱёӟӹӓӧӝӵӥ|
|Special|1|<kbd>⌥</kbd>-<kbd>AС01</kbd>|үәөҕ|
|Descender|2|<kbd>⇧</kbd><kbd>⌥</kbd>-<kbd>AC02</kbd>|қџңҗҳ|
|Cedilla|3|<kbd>⌥</kbd>-<kbd>AС02</kbd>|ҫҙ|
|Stroke|4|<kbd>⌥</kbd>-<kbd>AB01</kbd>|ұҡғҥ|
|Breve|5|<kbd>⌥</kbd>-<kbd>AD02</kbd>|ўӗӑо̆|
|Acute|6|<kbd>⌥</kbd>-<kbd>AE01</kbd>|ќѓ|
|Latin Chuvash|7|<kbd>⌥</kbd><kbd>AС09</kbd>|ÿĕçă|
|Double Acute|8|<kbd>⇧</kbd><kbd>⌥</kbd><kbd>AD01</kbd>|ӳ ő (lat)|
|Caron|9|<kbd>⌥</kbd><kbd>AB04</kbd>|р̌ т̌ Ť (lat)|


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