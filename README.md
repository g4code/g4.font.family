Font Family
======

> g4.font.family - [compass](http://http://compass-style.org/) mixin library

## Install
Via npm

```sh
npm install g4code.font.family
```

## Usage

**Import**

Import bower package mixin for font-family in to project for example

```sh
@import             "../../public/node_modules/g4code.font.family/src/font_family";
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
.some_selector {
    @extend %f700;
}
```

**Limits**
You can't use this @extend method inside @mediaqueries


## License

Copyright (c) 2016 [g4code](http://http://g4code.com/) (https://github.com/g4code)
(The MIT License) see LICENSE file for details.
