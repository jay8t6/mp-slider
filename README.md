[![Build Status](https://travis-ci.org/mpachnis/mp-slider.svg?branch=master)](https://travis-ci.org/mpachnis/mp-slider)  [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/mpachnis/mp-slider)
  
[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/mpachnismp-slider)
[![Stars on vaadin.com/directory](https://img.shields.io/vaadin-directory/star/mpachnismp-slider.svg)](https://vaadin.com/directory/component/mpachnismp-slider)


## &lt;mp-slider&gt;


## Demo

[mp-slider docs & demo](https://www.webcomponents.org/element/mpachnis/mp-slider)


## Install the component using [Bower](http://bower.io/):

```bash
$ bower install --save mp-slider
```

## Usage

1. Import Web Components' polyfill:

```html
<script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="bower_components/mp-slider/mp-slider.html">
```

3. Start using it!

    Wrap the image into a div. To add a caption to your image just include the `mp-caption` element. `mp-caption` available properties: `slider-header` and `slide-content`.

<!--
```
<custom-element-demo>
    <template>
        <script src="../webcomponentsjs/webcomponents-lite.js"></script>
        <link rel="import" href="mp-slider.html">
        <next-code-block></next-code-block>
    </template>
</custom-element-demo>
```
-->

```html
<mp-slider controls bullets show-thumbs>
    <div>
        <img src="demo/images/img1.jpg" />
        <mp-caption slider-header="Kung Fu Panda"
                    slider-content="Po and the legends of awesomeness">
        </mp-caption>
    </div>

    <div>
        <img src="demo/images/img2.jpg" />
        <mp-caption slider-header="Despicable Me"></mp-caption>
    </div>

    <div>
        <img src="demo/images/img3.jpg" />
        <mp-caption slider-content="The incredible Scart"></mp-caption>
    </div>
</mp-slider>
```

Available styles.

Properties | Description
---------- | -----------
--caption-background | Caption's background color
--pause-icon-background | pause icon's background color
--pause-icon-stroke-color | pause icon's color
--pause-icon-stroker-width | pause icon's stroke width

### Big Thanks

Cross-browser Testing Platform and Open Source <3 Provided by [Sauce Labs](https://saucelabs.com)

![](http://info.saucelabs.com/rs/468-XBT-687/images/powered_by_sauce_labs_badges_white_1x.png)


## License

MIT License
