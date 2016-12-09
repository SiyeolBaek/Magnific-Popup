# Magnific Popup Repository

[![Build Status](https://travis-ci.org/dimsemenov/Magnific-Popup.png)](https://travis-ci.org/dimsemenov/Magnific-Popup) 
[![Flattr](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/thing/1310305/Magnific-Popup-by-dimsemenov)

Fast, light and responsive lightbox plugin, for jQuery and Zepto.js.

- [Documentation and getting started guide](http://dimsemenov.com/plugins/magnific-popup/documentation.html).
- [Examples and plugin home page](http://dimsemenov.com/plugins/magnific-popup/).
- More examples in [CodePen collection](http://codepen.io/collection/nLcqo).

Optionally, install via Bower `bower install magnific-popup` or npm: `npm install magnific-popup`.
[Ruby gem](https://rubygems.org/gems/magnific-popup-rails): `gem install magnific-popup-rails`.


## Extensions

- WordPress plugin - [under development](http://dimsemenov.com/plugins/magnific-popup/wordpress.html).
- [Drupal module](https://drupal.org/project/magnific_popup).
- [Concrete5 add-on](https://github.com/cdowdy/concrete5-Magnific-Popup).
- [Redaxo add-on](http://www.redaxo.org/de/download/addons/?addon_id=1131).
- [Contao extension](https://github.com/fritzmg/contao-magnific-popup).

If you created an extension for some CMS, email me and I'll add it to this list.

## Location of stuff

- Generated popup JS and CSS files are in folder [dist/](https://github.com/dimsemenov/Magnific-Popup/tree/master/dist). (Online build tool is on [documentation page](http://dimsemenov.com/plugins/magnific-popup/documentation.html)).
- Source files are in folder [src/](https://github.com/dimsemenov/Magnific-Popup/tree/master/src). They include [Sass CSS file](https://github.com/dimsemenov/Magnific-Popup/blob/master/src/css/main.scss) and js parts (edit them if you wish to submit commit). 
- Website (examples & documentation) is in folder [website/](https://github.com/dimsemenov/Magnific-Popup/tree/master/website).
- Documentation page itself is in [website/documentation.md](https://github.com/dimsemenov/Magnific-Popup/blob/master/website/documentation.md) (contributions to it are very welcome).



## Using Magnific Popup?

If you used Magnific Popup in some interesting way, or on site of popular brand, I'd be very grateful if you <a href="mailto:diiiimaaaa@gmail.com?subject="Site that uses Magnific Popup"">shoot me</a> a link to it.


## Build 

Original Magnific-Pop from Here(https://github.com/dimsemenov/Magnific-Popup)

1) Copy repository

	git clone https://github.com/SiyeolBaek/Magnific-Popup.git


## Usage(only Naver Tvcast)

1. Copy Video's iframe share code

	```
<iframe src='http://serviceapi.rmcnmv.naver.com/flash/outKeyPlayer.nhn?vid=BE321B33E1E6EE82E1D26AE103366ED235C6&outKey=V1273992fe2df5898548820d7d30b154282768740399982c4c6ba20d7d30b15428276&controlBarMovable=true&jsCallable=true&isAutoPlay=true&skinName=tvcast_white' frameborder='no' scrolling='no' marginwidth='0' marginheight='0' WIDTH='544' HEIGHT='306' allowfullscreen></iframe>
	```
2. Extract url from code's src

	```
http://serviceapi.rmcnmv.naver.com/flash/outKeyPlayer.nhn?vid=BE321B33E1E6EE82E1D26AE103366ED235C6&outKey=V1273992fe2df5898548820d7d30b154282768740399982c4c6ba20d7d30b15428276&controlBarMovable=true&jsCallable=true&isAutoPlay=true&skinName=tvcast_white
	```
3. Use this url (like Original)

## [Changelog](https://github.com/dimsemenov/Magnific-Popup/releases)

v1.2.0 - Add Naver Tvcast for video popup

## License

Script is MIT licensed and free and will always be kept this way. But has a small restriction from me - please do not create public WordPress plugin based on it(or at least contact me before creating it), because I will make it and it'll be open source too ([want to get notified?](http://dimsemenov.com/subscribe.html)).

Created by [@dimsemenov](http://twitter.com/dimsemenov) & [contributors](https://github.com/dimsemenov/Magnific-Popup/contributors).

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/dimsemenov/magnific-popup/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

## Bugs & contributing

Please report bugs via GitHub and ask general questions through [StackOverflow](http://stackoverflow.com/questions/tagged/magnific-popup). Feel free to submit commit [pull-request](https://github.com/dimsemenov/Magnific-Popup/pulls), even the tiniest contributions to the script or to the documentation are very welcome.


