> This is my attempt to thank every single individual who knowingly or unknowingly contributed to the development of this website. To checkout the colophon of this website, simply <a id="toggle">toggle</a> the blanks.

Typography
----------
<table>
  <tr>
    <td>Primary fonts</td>
    <td>
      1. Chaparral Pro<br>
      <strong>Classification: </strong>Serif, <strong>Designers:</strong> Carol Twombly, <strong>Design date:</strong> 1997-2000, <strong>Publisher:</strong> Adobe<br>
      2. FF Tisa Web Pro<br>
      <strong>Classification: </strong>Serif, <strong>Designers:</strong> Mitja Miklavcic, <strong>Design date:</strong> 2008, <strong>Publisher:</strong> FontFont</strong><br>
    </td>
  </tr>
  <tr>
    <td>Fallback fonts</td>
    <td>
      Palatino Linotype, Baskerville, Garamond, Georgia, serif<br>
      <strong>Classification:</strong> serif, <strong>Tool:</strong> FFFFallback
    </td>
  </tr>
  <tr>
    <td>Served via</td>
    <td>
      TypeKit<br>
      <strong>Embedded using:</strong> @font-face rule in CSS.
    </td>
  </tr>
  <tr>
    <td>Baseline</td>
    <td>
      24px<br>
      <strong>Tool:</strong> Em Baseline Generator (by Joshua Hibbert), <strong>Measured using:</strong> GridWax (by Kevin Altman)                                      
    </td>
  </tr>
</table>

Colors
------
Color schemes are heavily based on the [Android Color Swatches](http://developer.android.com/design/style/color.html). The color contrast ratio is measured with the help of a neat little [tool](http://leaverou.github.com/contrast-ratio/) made by [Lea Varou](http://lea.verou.me/). Colors in the stylesheet are embedded in the [hsla()](http://css-tricks.com/yay-for-hsla/) format. [ColorHexa](http://www.colorhexa.com/) is always my best friend to find out the closest web safe color.

Framework
---------
[HTML5 Boilerplate](http://html5boilerplate.com/) is the framework behind this website. Coding standards are based on the [NA Isobar Coding Standards](http://isobar-idev.github.io/code-standards/) and the book [Dive Into HTML5](http://diveintohtml5.info/) by [Mark Pilgrim](http://en.wikipedia.org/wiki/Mark_Pilgrim_(software_developer) has always been a source of inpiration for me.

Images
------
All the images are individually smushed using [Smush.it](http://www.smushit.com/ysmush.it/) and sprited using the [SpritePad](http://spritepad.wearekiss.com/) and then compressed again. The SVG Icons are brought to you by [The Noun Project](http://thenounproject.com/) and the logo for personal branding is done by [Abhjijeet Wankehede](http://www.sokratus.in/). Images and SVG Icons are embedded directly via CSS using base64 encoded Data-URI generated using [Image to Data URI Converter](http://websemantics.co.uk/online_tools/image_to_data_uri_convertor/) by [Web Semantics](http://websemantics.co.uk). All the images are manufactured by [Adobe Photoshop CS6](www.adobe.com/in/products/cs6.html) as 24-bit PNG image with full alpha channel transparency. Subsequently these images are then injected through [TinyPNG](http://tinypng.org/) to compress them into 8-bit indexed color images with 100% support for transparency.

Plugins
-------
This site currently doesn't use any jQuery plugin but if you are in search for plugins, then [UnHeap ](http://www.unheap.com/) and [JSDB.io](http://www.jsdb.io/?sort=trending) are always a good place to start.

Stylesheet
----------
CSS code is formatted is using [ProCSSor](http://procssor.com/) and compressed using the [Online YUI Compressor](http://refresh-sf.com/yui/). CSS reset is based on the [reset.css](http://meyerweb.com/eric/tools/css/reset/reset.css) of [Eric Meyer](http://meyerweb.com/) for old and legacy browsers, while modern browsers rely on [normalise.css](http://necolas.github.io/normalize.css/) by [Nicolas Gallagher](http://nicolasgallagher.com/). [Helium-css](https://github.com/geuis/helium-css) and [CSS Trashman](http://www.csstrashman.com/styles/20386) has been extensivley used to churn out the unused css across pages. CSS code is verified for errors using [CSS Lint](http://csslint.net/) and [W3C CSS Validator](http://jigsaw.w3.org/css-validator/). Special unicode characters are brought to you by [Copy-Paste Character](http://copypastecharacter.com/).

Scripts
-------
All the JavaScript files are compressed using [Uglify.js](http://marijnhaverbeke.nl//uglifyjs) and [YUI Compressor](http://refresh-sf.com/yui/). Performance optimisation is carried out with the help of [jsPerf](http://jsperf.com/)

Design
------
Initial layout for the website was designed and conceived using wireframing technique with the help of a neat little free app - [Wireframe.cc](http://wireframe.cc/). Charts and Infographics are brought to you by [xCharts](http://tenxer.github.com/xcharts/) and [Chart.js](http://www.chartjs.org/).

Browser
-------
Compatible with the latest versions of all modern browsers and tested with [BrowserStack](http://www.browserstack.com/) for both desktop and mobile. A/B testing done with [Optimizely](https://www.optimizely.com/). Screenshots are generated with the help of [PlaceIt](http://placeit.breezi.com/) by [Breezi](http://breezi.com/). Performance for mobile devices is measured with [Mobitest](http://mobitest.akamai.com/) and the test results are available [here](http://mobitest.akamai.com/m/results.cgi?testid=130420_FD_10).

Hosting
-------
This website is hosted on [GitHub](https://github.com/) and version controlled by Git. The domain is brought to you by [BigRock](http://bigrock.com/) and Email with personal domain was made possible by [Google Apps](http://www.google.com/intl/en/enterprise/apps/business/).

Desk
----
Completely handcrafted and coded in [Sublime Text 3](http://www.sublimetext.com/3) on [13-inch Retina MacBook Pro](http://www.apple.com/in/macbook-pro/specs-retina/). The [Editor](http://blog.alexmaccaw.com/sublime-text) uses the [Soda theme](https://github.com/buymeasoda/soda-theme/) and the dock icon is from [Elliot Jackson](http://dribbble.com/shots/872166-Sublime-Text-2-Replacement-Icon). Early versions of this website were coded in [VIM](http://www.openvim.com/tutorial.html). [H5BP Ant Build Script](https://github.com/h5bp/ant-build-script) is used to concatenate and minify the assests and make it production ready.

Testing
-------
Testing for all browsers done via BrowserStack. Testing for mobile devices done using Ghostlab and Adobe Edge Inspect (formerly Adobe Shadow). [Web Page Test](http://www.webpagetest.org/result/130615_BN_AKW/), [Pingdom](http://tools.pingdom.com/fpt/), Google PageSpeed used to test the performance and optimisation.
