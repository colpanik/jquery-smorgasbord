smorgasbord
===========

jQuery plugin to generate "sample player" UI for HTML5 Audio.

###usage

First, make sure you've added some audio files to your markup. They should look like this:

```
<audio src="sounds/one.mp3" preload="auto"></audio>
<audio src="sounds/two.mp3" preload="auto"></audio>
<audio src="sounds/three.m4a" preload="auto"></audio>
<audio src="sounds/four.mp3" preload="auto"></audio>
```

Now, if you've included the smorgasbord plugin in your project, all you need to do is:

```
$('audio').bord();
```
###available options

```
$('audio').bord({
  keyboard: true,
  loopable: true
});
```

