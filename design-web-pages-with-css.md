# Chapter 10: Introducing to CSS

## What CSS does?
### CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.
------------------------------------
> The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.

> CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.
------------------------------------------
## How CSS works?
### CSS works by associating rules with HTML elements. These rules govern how the content of specific elements should be displayed. A CSS rule contain two parts: a **_selector_** and **_declaration_**.
![selector and declaration](https://github.com/noureddein/reading-notes/blob/main/imgs/selector%20and%20declaration.png?raw=true)

### CSS properties affect how elements are displayed.
### CSS declarations sit inside curly brackets and each is made up of two parts: a **_property_** and a **_value_**, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.
### To use an external CSS you need to insert a link in side your HTML page <link href=””  type=”text/css” rel=”stylesheet”/>
> You can use more than on CSS style sheet.
### CSS selectors:
![CSS selectors](https://github.com/noureddein/reading-notes/blob/main/imgs/selector%20and%20declaration.png?raw=true)

--------------------------------------------- 

## Summary
  - 1 -CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look.
  - 2- Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like).
  - 3- Different types of selectors allow you to target your rules at different elements.
  - 4- Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.
  - 5- CSS rules usually appear in a separate document, although they may appear within an HTML page.

-----------------------------------------

# Chapter 11: Colors
### To specify a color in CSS there are several ways :
  - 1-	RGB values
     * Ex. rgb(102,205,170)
  - 2-	HEX codes
     * Ex. #66cdaa
  - 3-	Color names
     * Ex. MediumAquaMarine
  - 4-	HSLA (Hue, Saturation, Luminosity, Alpha) 
     * Ex. hsla(360, 100%, 100%, 0.5)

## Opacity 
### CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between **0.0** and **1.0** (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).

### The CSS3 **RGBa** property allows you to specify a color, just like you would with an RGB value, but adds **a** fourth value to indicate _opacity_. This value is known as an **_alpha-** value and is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity). The rgba value will only affect the element on which it is applied (not child elements).

### Margin, Padding, and Border
![Margin and Padding](https://github.com/noureddein/reading-notes/blob/main/imgs/Paddin%20and%20margin.png?raw=true)

### How to add styling to elements
![Add Properties](https://github.com/noureddein/reading-notes/blob/main/imgs/properteis%20and%20valuse.png?raw=true)

## Summary 
  - 1-Color not only brings your site to life, but also helps convey the mood and evokes reactions.
  - 2-There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
  - 3-Color pickers can help you find the color you want.
  - 4-It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
  - 5-CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
  - 6-CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.



