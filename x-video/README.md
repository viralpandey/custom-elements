# x-video

> Simplified extension to the HTML5 `video` element that supports all types of videos with flash fallback.

## Installation

Using [Bower](http://bower.io), run:

```shell
$ bower install x-video
```

## Usage

1. Import Web Components' polyfill:

	```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
    ```

2. Import Custom Element:

	```html
	<link rel="import" href="x-video.html">
	```

3. Start using it!

	```html
	<x-video src="//clips.vorwaerts-gmbh.de/big_buck_bunny.mp4"></x-video>
	```

## Options

1. With Source

    ```html
    <x-video src="//clips.vorwaerts-gmbh.de/big_buck_bunny.mp4"></x-video>
    ```

2. With Alt

    ```html
    <x-video src="http://clips.vorwaerts-gmbh.de/big_buck_bunny.mp4" alt="Big Buck Bunny"></x-video>
    ```

3. With Dimensions

    ```html
    <x-video src="http://clips.vorwaerts-gmbh.de/big_buck_bunny.mp4" width="400" height="300"></x-video>
    ```

## License

[MIT License](http://opensource.org/licenses/MIT)
