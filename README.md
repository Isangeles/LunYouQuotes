## Introduction
lyq(Lun Yu Quotes) is simple bash script that displays one random quote from Lun Yu(Analects of Confucius) in your bash.

![gf1](/lyq_preview.gif)

Available translations:
  
*Polish by Jaroslaw Zawadzki(tlumacz-chinskiego.pl).
  
*English by Confucius Publishing Co. Ltd.(confucius.org)
  

Default quotes base contains specific quotes that are my personal selection. 

## Installation 
run:

```
./install
```

## Usage
to run script simply type:

```
$ lyq
```

if command does not work try to relog.

### Command options:
```
$ lyq -ll
```
Description: Lists all supported languages.
```
$ lyq -lq
```
Description: Lists all verses for current language.
```
$ lyq -q [verse number]
```
Description: Prints verse of the selected number.
```
$ lyq -sl [language]
```
Description: Changes language(only english and polish supported).

## Remove
Run:
```
./uninstall
```

## License
Copyright (c) 2017-2019 Dariusz Sikora <<dev@isangeles.pl>>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.