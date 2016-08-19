# Mobile Operators Vector Icons
MOVI - it`s an easy way to integrate mobile operators icons in your website.  
All you need is just one CSS file.

*Curently includes only 3 Ukrainian mobile operators*

## Setup
 1. Download icons css file (it includes base64 decoded icons)
 2. Include icons css file to your project `<link rel="stylesheet" type="text/css" href="movi.css">`
 3. Use icons in your project `<i class="moi-iconname"></i>`

## Icons
 - ![kyivstar](https://raw.githubusercontent.com/vov1/movi/master/readme-images/kyivstar.png "Kyivstar") `<i class="movi-kyivstar"></i>`
 - ![lifecell](https://raw.githubusercontent.com/vov1/movi/master/readme-images/lifecell.png "Lifecell") `<i class="movi-lifecell"></i>`
 - ![vodafone](https://raw.githubusercontent.com/vov1/movi/master/readme-images/vodafone.png "Vodafone") `<i class="movi-vodafone"></i>`

## Styling
You could style icons as you want by:
 - extending movi css clases  
 Example: ![vodafone-custom](https://raw.githubusercontent.com/vov1/movi/master/readme-images/vodafone-custom.png "Vodafone custom")
 ```css
 [class*=movi-] {
    width: 15px;
    height: 15px;
 }

 .movi-vodafone {
    background-color: #bbb;
    border-radius: 10px;
 }
 ```

 - or using your own clases
 ```css
   .header-phone {
      margin-right: 10px;
   }
 ```

 ```html
    <i class="movi-kyivstar header-phone"></i>
 ```

## Author
[Volodymyr Stelmakh (vov1)](https://github.com/vov1)  
[knopix.net](http://knopix.net/)

## license
[MIT](https://opensource.org/licenses/MIT)