# Welcome !
============

Here is a modest modification I made to transform the basic Image Modal from [w3schools](https://www.w3schools.com/howto/howto_css_modal_images.asp).

The goal here was to adapt it from **native JS** to **jQuery library** !

I modified it a bit so you no longer need to click on a special button to close the modal.

Working pretty well, you can even put it in fonction if you need !

[Here is an example](https://rawgit.com/Rdyx/jQuery-Snippet-Image-Modal/master/index.html)


#### How to make it work
=======================

  * **npm install**, there's a package.json in case you need to get **jQuery** files
  * You will have to **set** the **modal** in you **HTML** first (aka *copypasta* ;)).
  * **Link css**.
  * **Link script**.


#### How it works
================

  * Click on your img with **.myImg class** to trigger the script.
  * This will change **css style display to "block"** to show Modal (transition trick is in **CSS**).
  * The **source** of modal image is set to match the image you clicked.
  * There's also a bonus **caption** that is set by getting the **image's alt**.
  * To close the modal, you simply click **anywhere**. Why ? Because the **closing class** is on the **WHOLE** modal ! :)


## Enjoy ! :)