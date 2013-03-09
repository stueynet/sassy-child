Responsive Child theme with Sass!
=================================

A child theme for the Responsive WordPress theme that uses SASS/SCSS for editing the style.

  - Use SASS to create sexy css 
  - Be amazing
  - Comes with a config.rb file


What you need
-------------

You need/want/should have compass and sass rolling. To do that fire up Terminal on your mac and do the following:

   sudo gem install compass

Uh thats it. You are done. If you want to learn more about SASS or CSS you should check out this thing called Google.


How to do stuff
---------------

So the way this works is you have all your delicious sassy files in the /sass folder. That is what you want to edit. There is currently a file called style.scss in there. When you compile your sass or if you are running "watch", it will compile to the theme's main style.css file.

So you're gonna edit sass/style.scss using any combination of css, or scss and then compile it and because of the config.rb file up in there, it will compile it to your theme's style.css file. You may notice in the style.css file there is a ! after the * in the main theme comment at the top. This is so that if you decide to use the compression option, it will not remove that comment and WordPress will still be able to recognize your child theme.