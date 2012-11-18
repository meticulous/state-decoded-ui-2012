# ReadMe for The State Decoded design

This is the static breakout of The State Decoded design created in the fall of 2012. This is a combination of boilerplate as well as other functions that come from a variety of resources online, including the Ruby/Sass community. Any questions can be directed at myself (John Athayde) or Waldo Jaquith.

Cheers,
John Athayde
jmpa@meticulous.com
November 2012

## Setup

### Favicons, Apple Touch Icons

Each of these icons should somehow correlate to your State or Commonwealth. With Virginia, we used the seal icon that was created for the site. The larger touch icons have bitmapped 0 and 1s fading across, representing digital bits being "decoded" as it were. Feel free to edit the images in the source_psd folder to suit your needs. We recommend running any images through ImageOptim (http://imageoptim.com) to squeeze out excess file size.

### Sass, Compass, etc.

This site was built with future flexibility and reuse in mind. To that end, the site basically is a styleguide as well as a design. We use Sass/SCSS to allow the power of variables in CSS. This lets other groups who may be implementing this on their own to rapidly change colors and fonts without having to do massive find and replace or worry about color math variations in Photoshop.

This does create a layer of complexity, but one that I feel is worth having. You, as an end user, can write regular CSS in an SCSS file and it will compile normally.

To run this, there are a few setups you need. You need to either run CodeKit, Scout, CompassApp, or do a manual setup with Ruby on your system. This is documented on the Compass site (http://compass-style.org/install/).