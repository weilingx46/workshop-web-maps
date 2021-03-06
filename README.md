# CS52: A Tutorial for Mapbox!

[<img width="981" alt="Mapbox GL gallery" src="https://raw.githubusercontent.com/mapbox/mapbox-gl-js/master/docs/pages/assets/gallery.png">](https://www.mapbox.com/gallery/)

Today, we will go over the basics of using mapbox, a JavaScript library mainly used for interactive, customizable maps. The tutorial is based loosely off mapbox's [GitHub repo](https://github.com/mapbox/mapbox-gl-js).

Let's get started!

## Overview

By the end of the workshop, you should have done the following:
* [ ] Make a mapbox account
* [ ] Have a website with integrated Mapbox
* [ ] Customize the map
* [ ] ?
* [ ] ?

## Creating a mapbox account

Let's get started!

First of all, make a mapbox account.

[Make an account](https://www.mapbox.com/signup/)

[<img width="981" alt="Mapbox Signup" src="img/screenshot-1.png">](https://www.mapbox.com/signup/)

When you make an account, it should give you your access token. Save this and keep it handy! We will need it later.

## Forking the repo

Scroll to the top of this page and fork the repo. We have provided a skeleton of a website that you can insert your map into!

## Adding a map to the website!

Tim has opened up a pizza place. Let's help him out by inserting a basic map into their website so they can expand globally.

Open up index.html and add the GL JS JavaScript and CSS files in the head of your HTML file.

```html
<script src='https://api.tiles.mapbox.com/mapbox-gl-js/v0.44.2/mapbox-gl.js'></script>
<link href='https://api.tiles.mapbox.com/mapbox-gl-js/v0.44.2/mapbox-gl.css' rel='stylesheet' />
```

Add the following code to the body.

```html
<div id='map' style='width: 400px; height: 300px;'></div>
<script>
mapboxgl.accessToken = 'REPLACE WITH YOUR OWN';
var map = new mapboxgl.Map({
    container: 'map',
    style: 'mapbox://styles/mapbox/streets-v9'
});
</script>
```

**Remember to switch out the accessToken with your own.**

Fantastic, now you have a map embedded in the webpage!


##

## Step by Step

* Explanations of the what **and** the why behind each step. Try to include:
  * higher level concepts
  * best practices

Remember to explain any notation you are using.

```javascript
/* and use code blocks for any code! */
```

![screen shots are helpful](img/screenshot.png)

:sunglasses: GitHub markdown files [support emoji notation](http://www.emoji-cheat-sheet.com/)

Here's a resource for [github markdown](https://guides.github.com/features/mastering-markdown/).


## Summary / What you Learned

* [X] Make a mapbox account
* [X] Have a website with integrated Mapbox
* [X] Customize the map
* [X] ?
* [X] ?

## Resources

* cite any resources
