---
layout: post
title: Game´s im a part of!
subtitle: 3D/2D art + Programming
tags: [test]
comments: false
mathjax: true
author: João Lopes
---

{: .box-success}
In this post i go in more detail in the projects i have been apart of, whyle i was a member of student group GameDevTecnico.
Full credit for the games are avalable at the games page at itch.io, linked in itch game i´ll present.

**Most of these games were developed during game jams, a few are internal projects**

## 3D games
### [Winds of Berkana]((https://antunes10.itch.io/winds-of-berkana))


![DYQPto](https://github.com/user-attachments/assets/fe3d6aea-053d-483d-8902-1da9e6e07045)
This is the most ambicios project im apart of, for the past 3 years we have been developing this idea of an hight quality game around Huge Bastions and an awesom character story. In this game i have been responsable for heliping in concep art, and latter deveoping the models for the huge bastions the player can explore.


[Here]([https://deanattali.com/](https://antunes10.itch.io/winds-of-berkana)) i have made avalable all art and models i can share.

### [Final QuackDown]([https://deanattali.com/](https://antunes10.itch.io/winds-of-berkana))


![DYQPto](https://github.com/user-attachments/assets/fe3d6aea-053d-483d-8902-1da9e6e07045)
This is the most ambicios project im apart of, for the past 3 years we have been developing this idea of an hight quality game around Huge Bastions and an awesom character story. In this game i have been responsable for heliping in concep art, and latter deveoping the models for the huge bastions the player can explore.


[Here]([https://deanattali.com/](https://antunes10.itch.io/winds-of-berkana)) i have made avalable all art and models i can share.

It can also be centered!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})
