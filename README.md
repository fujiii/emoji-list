# Emoji List

Display random emojis instead of HTML list bullet points on every page refresh!

## Preview

[fujiii.github.io/emoji-list](https://fujiii.github.io/emoji-list)

## Installation

Run `npm i emoji-html-list`

Or include `<script src="https://unpkg.com/emoji-html-list@latest/emoji-list.min.js"></script>`

## Usage

Simply add `data-emoji-list` attribute to HTML list, like this:

```
<ul data-emoji-list>
  <li>Lorem ipsum dolor sit amet</li>
  <li>Aenean massa</li>
  <li>Donec quam felis, ultricies nec</li>
  <li>In enim justo, rhoncus ut</li>
  <li>Vivamus elementum semper nisi</li>
  <li>Aliquam lorem ante, dapibus in, viverra quis</li>
  <li>Donec sodales sagittis magna</li>
</ul>
```

You can specify `category` option, like this:

```
<ul data-emoji-list='{ "category": "foodAndDrinks" }'>
  <li>Lorem ipsum dolor sit amet</li>
  <li>Aenean massa</li>
  <li>Donec quam felis, ultricies nec</li>
  <li>In enim justo, rhoncus ut</li>
  <li>Vivamus elementum semper nisi</li>
  <li>Aliquam lorem ante, dapibus in, viverra quis</li>
  <li>Donec sodales sagittis magna</li>
</ul>
```

## Possible categories

`animalsAndNature` which is also a default category, `smileysAndPeople`, `foodAndDrinks`, `activities`, `travelAndPlaces`, `objects`, `symbols`
