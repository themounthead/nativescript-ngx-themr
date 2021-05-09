# Nativescript-ngx-themr

This is a SASS utlity that extends the Angular Material Theming to create custom
palettes. You can create your own custom palette by defining the _Primary_, _Secondary_ and _Tertiary_ Colors and Accents in the
theme file.

It includes support for both Light and Dark themes.

## What do I get ?

A large collection of Css Root variables i.e. Material Palette that can be used to define your own Sass variables
or simply create custom Css classes by extending the variables.

## Getting Started

- Step 1: Copy the Theme folder and place it in your NS Project
- Step 2: Include the _theme_ scss import in your app.scss file
- Step 3: Add you own Css classes by extending the variables

## Quick Demo

Run the below command providing your main input Sass/Scss file, after including the
_theme_ import and view the output generated Css.

``` node-sass source/app.scss dest/app.css

## Examples

The Project contains a sample demo, along with several sample Theme files
