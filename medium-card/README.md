# medium-card

> Embed beautiful Medium Stories, Collections or even Profiles with this easy-to-use custom element.

## Installation

Using [Bower](http://bower.io), run:

```shell
$ bower install medium-card
```

## Usage

1. Import Web Components' polyfill:

	```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
    ```

2. Import Custom Element:

	```html
	<link rel="import" href="medium-card.html">
	```

3. Start using it!

	```html
	<medium-card></medium-card> 
	```

## Options

1. Embed Profile

    ```html
    <medium-card type="profile" href="@pankajparashar"></medium-card>
    ```
    
2. Embed Story

    ```html
    <medium-card type="story" href="@manicho/how-a-password-changed-my-life-7af5d5f28038"></medium-card>
    ```
    
3. Embed Collection

    ```html
    <medium-card type="collection" href="front-end-developers"></medium-card>
    ```
    
## License

[MIT License](http://opensource.org/licenses/MIT)
