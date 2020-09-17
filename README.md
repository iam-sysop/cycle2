# Cycle2 - 2nd Generation Cycling!

## UPDATED REPO
**This repo contains fixes and updates for Cycle2 to remain compatible with NEWER versions of jQuery 3.x and up.**  

## Getting Started
In your web page:

```html
<!-- include jQuery 3 -->
<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
<!-- OR include jQuery 2 -->
<script src="https://code.jquery.com/jquery-2.2.4.min.js"></script>

<!-- include Cycle2 -->
<script src="http://path/to/your/copy/of/jquery.cycle2.min.js"></script>
```

```html
<!-- declare a slideshow -->
<div class="cycle-slideshow">
    <img src="http://malsup.github.com/images/p1.jpg">
    <img src="http://malsup.github.com/images/p2.jpg">
    <img src="http://malsup.github.com/images/p3.jpg">
</div>
```

That's it!  You don't need to write any script to initialize the slideshow, Cycle2 will auto-initialize if you use the class <code>cycle-slideshow</code>.

## Documentation, Demos, and FAQ
Everything you need to know can be found here: 
[http://jquery.malsup.com/cycle2/](http://jquery.malsup.com/cycle2/)

## Build
If you want to make changes to Cycle2 and build it yourself, you can do so by installing the node build dependencies:
<pre>npm install</pre>
and then running the build
<pre>npm run build-dist</pre>

## Copyright and License
Copyright &copy; 2012-2014 M. Alsup.

The Cycle2 plugin is dual licensed under the [MIT](http://malsup.github.com/mit-license.txt) and [GPL](http://malsup.github.com/gpl-license-v2.txt) licenses.

You may use either license.  The MIT license is recommended for most projects because it is simple and easy to understand and it places almost no restrictions on what you can do with the plugin.

If the GPL suits your project better you are also free to use the plugin under that license.

You do not have to do anything special to choose one license or the other and you don't have to notify anyone which license you are using. You are free to use the Cycle2 plugin in commercial projects as long as the copyright header is left intact.
