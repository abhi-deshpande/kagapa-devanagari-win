# kagapa-devanagari-win
This project is a Windows port of KaGaPa Phonetic layout for Devanagari script, which is originally written for XKB in GNU/Linux.
## Introduction
This repository contains KaGaPa Phonetic layout for Devanagari, which can be used to input Marathi, Hindi and Sanskrit language. This is one of the most missed layouts for devanagari typers who need to deal with both Linux and Windows.

Along with it, two more layouts are also provided, one of which is a port of my _"Sanskrit Symbols"_ layout in XKB, which can be used to type all vedic symbols currently supported by Unicode. These symbols are best rendered by [Adishila Fonts](https://adishila.com/fonts/). Another one is the port of my _"Modi KaGaPa Phonetic"_ layout used to type a historically important script called Modi. This script was prominantly used to write Marathi language in a seamless cursive fashion, and possess significant importance in the history of Maharashtra.

_Unfortunately, Windows text stack does not seem to have input support for Modi. Therefore, the keyboard layout fails to work. Still, I have provided it. Maybe somebody would be interested to figure out issues with it, or port it in some other way. Maybe it would work after a future update to Windows text stack...!_

Although, Modi is rendered fine on Windows. To render Modi, two Unicode fonts are currently available. They are [MarathiCursive](https://github.com/MihailJP/MarathiCursive) and [Noto Sans Modi](https://fonts.google.com/noto/specimen/Noto+Sans+Modi).
## Installation & Usage
Each of the folders of layouts have a zip archive named as _\<layout_name\>.zip_. Download it, extract and run _setup.exe_. After installation is completed, restart your computer. The folders also contain images of the layout layers. Refer to them if you get stuck.

## Customizing layouts
Layout folders have a _.klc_ file of the layout. It is intended to be edited using [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=102134) or [KBDEdit](http://www.kbdedit.com/). Both of these tools are extremely easy to use, pretty much self-explanatory. If you face any issues with the tools like wrong layout descriptions, you can manually edit the _.klc_ in any text editor to fix that.

## Licensing
This work is openly licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
