Font Family
======

> g4.font.family - [compass](http://http://compass-style.org/) mixin library

## Install
Via Bower

```sh
bower install g4.font.family
```

Open **config.rb** file in to compass root directory and add ( or edit ) font URL

```sh
http_fonts_path            = "/bower/g4.font.family/src/fonts/"
```
```sh
fonts_dir                  = "../public//bower/g4.font.family/src/fonts/"
```

## Usage

**Import**

Import bower package mixin for font-family in to project for example

```sh
@import             "../../public/bower/g4.font.family/src/font_family";
```
Now you need to declare font-family which you want to have on site

**Declare**


```sass


@include font_family(Font_name);


@include font_family(Roboto);


@include font_family(OpenSans);


```

All fonts has same naming convention

Name + sufix
OpenSans-LightItalic
Roboto-LightItalic

Now we have successfuly setup font family on our project. Default font it will be

font-family: Roboto
font-style: normal;
font-weight: 400;


**Custom weight**

You have possibility to load different fonts weight

for example:

```sh
.come_selector {
    @extend %f700;
}
```

**Limits**
You can't use this @extend method inside @mediaqueries


## License

Copyright (c) 2016 [g4code](http://http://g4code.com/) (https://github.com/g4code)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
