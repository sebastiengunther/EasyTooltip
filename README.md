# EasyTooltip

<p align="center">
  <img src="https://github.com/sebastiengunther/EasyTooltip/blob/master/easy-tooltip-preview.png?raw=true"/>
</p>
<br/>

## About

[EasyTooltip](https://github.com/sebastiengunther/EasyTooltip/) is a Qlik Sense extension, which allows you to add tooltip on sheets.
<br/>
It can contain text or image URL. It's possible to use expression.
<br/>
This extension is developped by [EasyNeo](https://www.easyneo.fr/).
<br/>
<br/>

## Download
  
| Version | Date | Compatibility | Link |
| --- | --- | --- | --- |
| `v1.0` | 28/03/2019 | Feb 2019 <br/> Nov 2018 <br/> (not tested in earlier versions) | [`Download`](https://github.com/sebastiengunther/EasyTooltip/archive/master.zip) |
  
<br/>

## Usage

1. First of all, download the extension and import it.
  <br/>

2. Next, open the application and sheet on which you want to use EasyTooltip.
  <br/>

3. Then, edit the extension object and add the __first measure__.
    > Note that the first measure is the text in the __object__
    * `Expression` (string, can be an expression)
      * It's the text who's display in the object
      <br/>

    * You can edit appearance in the tab __appearance__, in __Easy Tooltip : Text__
      
      * `Type` (select)
        * It's the type of the tooltip
        * __Text__ : the text `Expression` is interpreted as HTML
        * __Image__ : the text `Expression` is interpreted as an image URL
        <br/>

      * `Text color` (color, only if `Type` is a text)
        * It's the color of the text displays in the object
        <br/>

      * `Text font size` (string, can be an expression, only if `Type` is a text)
        * It's the font size of the text in the object
        <br/>
      
      * `Border` (checkbox)
        * If it's checked, it add a border to the object
        <br/>
      
      * `Border color` (color, only if `Border` is checked)
        * It's the color of the border of the object
        <br/>
      
      * `Cursor` (select)
        * It's the cursor shape
        * __Pointer__ : ![pointer](https://developer.mozilla.org/@api/deki/files/3449/=pointer.gif)
        * __Default__ : ![default](https://developer.mozilla.org/@api/deki/files/3438/=default.gif)
        * __Help__ : ![help](https://developer.mozilla.org/@api/deki/files/3442/=help.gif)
        * __Crosshair__ : ![crosshair](https://developer.mozilla.org/@api/deki/files/3437/=crosshair.gif)
        <br/>

      * `Background color` (color)
        * It's the background color of the object
        <br/>

      * `Vetical position` (select)
        * It's the vertical position of the text in the object
        * __Top__ : the text will be at the top of the object
        * __Middle__ : the text will be at the middle of the object
        * __Bottom__ : the text will be at the bottom of the object
        <br/>

      * `Alignement` (select)
        * It's the alignement of the text in the object
        * __Left__ : the text will be left align
        * __Center__ : the text will be center align
        * __Right__ : the text will be right align
        <br/>

4. After, add the __second measure__.
    > Note that the second measure is the text in the __tooltip__
    * `Expression` (string, can be an expression)
      * It's the text who's display in the tooltip
      <br/>
      
    * You can edit appearance in the tab __appearance__, in __Easy Tooltip : Tooltip__

      * `Tooltip Type` (select)
        * It's the type of the tooltip
        * __Text__ : the `Tooltip` is interpreted as HTML
        * __Image__ : the `Tooltip` is interpreted as an image URL
        <br/>

      * `Tooltip text color` (color, only if `Tooltip type` is a text)
        * It's the color of the text in the tooltip
        <br/>

      * `Tooltip font size` (string, can be an expression, only if `Tooltip type` is a text)
        * It's the font size of the text in the tooltip
        <br/>

      * `Tooltip background` (color)
        * It's the background color of the tooltip
        <br/>

      * `Tooltip position` (select)
        * It's the position of the tooltip
        * __Left__ : the tooltip will be at the left of the object
        * __Right__ : the tooltip will be at the right of the object
        * __Top__ : the tooltip will be at the top of the object
        * __Bottom__ : the tooltip will be at the bottom of the object
        <br/>

      * `Tooltip alignement` (select)
        * It's the alignement of the text in the tooltip
        * __Left__ : the text will be left align
        * __Center__ : the text will be center align
        * __Right__ : the text will be right align
        <br/>

      * `Tooltip width` (string, can be an expression)
        * It's the max width of the tooltip
          > Note that if the `Width` is too small for the text, then the text will go on the line
        <br/>

5. Finally, you can quit the edit mode and put your mouse on the EasyTooltip to see the tooltip.


<br/>
<hr/>

[![EasyNEo](https://github.com/sebastiengunther/EasyTableTooltip/blob/master/resources/image/easyneo_transparent.png?raw=true)](https://www.easyneo.fr/)













