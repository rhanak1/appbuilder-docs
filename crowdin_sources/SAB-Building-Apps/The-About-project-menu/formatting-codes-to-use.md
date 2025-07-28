---
title: Which formatting codes can I use in the About page?
sidebar_position: 2
slug: /formatting-codes-to-use
---



# **Which formatting codes can I use in the About page?** {#23780858a4b6800bb678e4a67d03b187}


You can use the following formatting codes:


:::caution

Docu-notion does not allow for html tags to appear as text. Replace all { } with angle brackets

:::




|                                       |                                                                                                                                                                                                                                                                                                                                                                                        |
| ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Bold text**                         | Surround the text you want in bold with {b} and {/b} markers.<br/>Example: {b}This is in bold{/b}                                                                                                                                                                                                                                                                                      |
| **Italic text**                       | Surround the text you want in italics with {i} and {/i} markers.<br/>Example: {i}This is in italics{/i}                                                                                                                                                                                                                                                                                |
| **Underlined text**                   | Surround the text you want underlined with {u} and {/u} markers.<br/>Example: {u}This is underlined{/u}                                                                                                                                                                                                                                                                                |
| **Website links**                     | Use the format [website](http://www.example.com)                                                                                                                                                                                                                              |
| **Email links**                       | Use the format [text] (mailto:address), where ‘text’ is the text to display and ‘mailto:address’ contains the email address.<br/>Example: Contact us by [email](mailto:contact@example.com)                                                                                                                                                                                            |
| **Phone numbers**                     | Use the format [text] (tel:number), where ‘text’ is the text to display and ‘tel:number’ contains the number to call.<br/>Example: Our number is [012-345-678] (tel:012345678)                                                                                                                                                                                                         |
| **Image**                             | To add an image, first add the image file to the app illustrations (**Images** → **Illustrations**) and use the following HTML code:<br/>   {img src="image1.jpg"/}<br/>You can specify width information, as a percentage (e.g. "80%") or a fixed number of pixels (e.g. "80px"), or in the **img.about-image style**:<br/>   {img width="80%" src="image1.jpg"/}                     |
| **Left, right or centered alignment** | To align text or images, surround them with the following {div} markers:<br/>   {div align="center"}This is centered{/div}<br/>   {div align="left"}This is left aligned{/div}<br/>   {div align="right"}This is right aligned{/div}<br/>To center an image:<br/>   {div align="center"}{img width="75%" src="img2.jpg"/}{/div}                                                        |
| **Styles**                            | To apply styles (defined in the **Styles** page):<br/>   {div class="q2"}This is styled as poetry{/div}                                                                                                                                                                                                                                                                                |
| **Fonts**                             | To apply specific fonts to text, first make sure that the fonts are specified on the **Fonts** page. Then use the following syntax:<br/>   {span style="font-family:font1;"}This is in font1{/span}<br/>   {span style="font-family:font2;"}This is in font2{/span}                                                                                                                    |
| **Links within the About box**        | Set a marker to jump to when a text phrase is clicked. For example, set a language marker (Eng) to allow the user to jump to About box text in English—if you want to have multiple languages in the text.<br/>{h3 id="Eng"}English{/h3} (sets the id **Eng** associated with this section)<br/>{a href="#Eng"}(Click here for the English version){/a} (marks the section to jump to) |


:::tip

_To center all the text in the About box, add “__**text-align: center;**__“ to the CSS in the_ _**body.about**_ _UI style_

:::




| **To modify this…**           | **Adjust this text style…** |
| ----------------------------- | --------------------------- |
| About page formatting         | body.about                  |
| Background block for an image | div.about-image-block       |
| Image size / width            | Img.about-image             |

