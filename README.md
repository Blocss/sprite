# Blocss Sprite – v1.0.0

A [Blocss](https://github.com/Blocss/blocss/) component to create sprites & icons.

Read more about [Blocss](https://blocss.github.io/blocss).

## Installation

* [Bower](http://bower.io/): `bower install --save blocss-sprite`
* Download: [zip](https://github.com/Blocss/sprite/zipball/master)
* Git: `git clone https://github.com/Blocss/sprite`

## Available classes

* `.sprite` - The core sprite component class
* `.icon` - The core icon component class
* `.icon--medium` - Icon rendered @ 24px ratio
* `.icon--large` - Icon rendered @ 32px ratio
* `.icon--huge` - Icon rendered @ 64px ratio
* `.icon--normalis` - Icon rendered @ parents font size

## Usage

```html
<i class="sprite  [sprite--your-modifier-name]"></i> Help and FAQ
<i class="icon  [icon--medium|icon--large|icon--huge|icon--normalis|icon--your-modifier-name]" data-icon="t"></i> follow us on twitter
```

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 8+