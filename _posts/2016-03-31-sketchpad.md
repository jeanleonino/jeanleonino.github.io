---
title:  "Sketchpad"
date:   2016-03-31 10:18:00
description: Doodling with JavaScript
---

In 2014 [Nihey][nihey] and me were building an [application][crewee] for designers, something like inVision, it was our
first startup. One of the features was being able to make sketches on top of images, which is why we felt compeled to
create a sketchpad library using SVG, thus [sketchpad][https]//github.com/yiom/sketchpad) was born.

It is a simple to use addon to any application,

{% highlight js %}
var sketchpad = new Sketchpad({
  element: '#sketchpad',
  width: 400,
  height: 400
});
{% endhighlight %}

and point it to a `<canvas>` element:

{% highlight html %}
<canvas class="sketchpad" id="sketchpad"><canvas>
{% endhighlight %}

Nice things about it:

- Uses SVG :)
- Works on mobile
- Has undo/redo options
- You can "animate"
- Use any color you want

---

You can check it in action [here][yiom]. Our plans for the future: wrap as Ember.js component, React, and what else the
community ask us to do.

Did you like? Give us a star on [Github][sketchpad].

[yiom]:      http://yiom.github.io/sketchpad/
[nihey]:     http://github.com/nihey
[crewee]:    https://angel.co/crewee
[sketchpad]: https://github.com/yiom/sketchpad
