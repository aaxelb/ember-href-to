# ember-href-to

A lightweight alternative to `{{link-to}}`. No views, no class bindings - just a bound anchor href and a click handler.

## Why use it?

Every time you use a `{{link-to}}`, you create a view. This is usually fine, but in cases where you're creating may of thse, performance can suffer. `{{href-to}}` is [10x faster](https://github.com/GavinJoyce/ember-performance/pull/1) than `{{link-to}}` in Ember 1.13.4.

Questions? Ping me [@gavinjoyce](https://twitter.com/gavinjoyce)

## Installation

This is an Ember CLI addon, to install:

`npm install ember-href-to --save`

## Usage Instructions

```html
<a href="{{href-to 'contacts.contact' contact}}">View Contact</a>
```

![href-to2](https://cloud.githubusercontent.com/assets/2526/8709271/0a8b934a-2b39-11e5-8f24-89ece7d6c45d.gif)

## Development Instructions

* `git clone` this repository
* `npm install`
* `bower install`

### Running

* `ember server`
* Visit your app at http://localhost:4200.
