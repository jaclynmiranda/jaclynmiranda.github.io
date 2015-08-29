---
layout: page
title: Welcome to Jackie's Site!
tagline: with all the cool stuff
animal: turtle
---
{% include JB/setup %}

[comment]: <> (This is a comment. It won't appear in your site.)
[comment]: <> (Ignore the include thing above.)

[comment]: <> (This file is a Markdown file.)
[comment]: <> (We can mostly just write normal text.)

Hi, my name is Jackie!

[comment]: <> (But we can also do fun things, like line breaks:)

<br>

[comment]: <> (And images:)

<img src="/assets/images/cat.png" alt="Cat Pic!" style="width: 200px;"/>

[comment]: <> (You can see all of this rendered in the home page of your site.)

[comment]: <> (Those lines between the ---s up above define the page's variables.)
[comment]: <> (See how animal is set to turtle?)
[comment]: <> (That let's us do this:)

I like {{ page.animal }}s a lot!

[comment]: <> (On the main page of your site, you'll see:)
[comment]: <> (I like turtles!)
[comment]: <> (The magic website inserted the value of animal between the {{}}s!)

[comment]: <> (There are also variables set for the whole site.)
[comment]: <> (In the _config.yml file, a line says:)
[comment]: <> (food: banana)
[comment]: <> (So we can also do:)

I also like {{ site.food }}s!

[comment]: <> (It did it again!)

[comment]: <> (For more help, ask me anything!)
[comment]: <> (Or google it:)

[Google](http://google.com) has all the answers!

### A Heading

This `thing` is cool I guess.

    So is this,
    I guess...

I like *italics* and **bold** things.

Let's list some stuff

  1. One Fish
  2. Two Fish

Also:

  - <font color='red'>Red Fish</font>
  - <font color='blue'>Blue Fish</font>




