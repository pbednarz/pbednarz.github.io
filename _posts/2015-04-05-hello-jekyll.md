---
layout:     post
title:      Hello Jekyll and Pixyll
date:       2015-04-05 17:00:00
summary:    My first post using Jekyll with Pixyll theme.
categories: jekyll pixyll
---

### Jekyll is awesome
Jekyll is a static website and blog generator, so we don't need to worry about database, comments, updates.
To start using Jekyll please start with [Jekyll NOW](https://github.com/barryclark/jekyll-now)

Using Jekyll is super easy. I will try to keep this blog updated with a lot of code ;)

Pixyll at the moment has a couple of bugs, but I hope most of them will be fixed soon.

### Future plan of content that I want to post

  * Android applications (using RxJava, ORMs, Rest API),
  * more Android stuff (like custom views, performance tips),
  * Debian Live project - How to create your own Debian based distro,
  * and more...
  
For now I want to present basic markdown based post with Jekyll features from modified Pixyll demo below.
Enjoy! :)

## Let's start with Jekyll demo
### Headings!

They're responsive, and well-proportioned (in `padding`, `line-height`, `margin`, and `font-size`).
They also heavily rely on the awesome utility, [BASSCSS](http://www.basscss.com/).

##### They draw the perfect amount of attention

This allows your content to have the proper informational and contextual hierarchy. Yay.

### There are lists, too

  * Apples
  * Oranges
  * Potatoes
  * Milk

  1. Mow the lawn
  2. Feed the dog
  3. Dance

### Images look great, too

![nature](http://lorempixel.com/800/480/nature/3/)


### There are also pretty colors

Also the result of [BASSCSS](http://www.basscss.com/), you can <span class="bg-dark-gray white">highlight</span> certain components
of a <span class="red">post</span> <span class="mid-gray">with</span> <span class="green">CSS</span> <span class="orange">classes</span>.

I don't recommend using blue, though. It looks like a <span class="blue">link</span>.

### Stylish blockquotes included

You can use the markdown quote syntax, `>` for simple quotes.

> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse quis porta mauris.

However, you need to inject html if you'd like a citation footer. I will be working on a way to
hopefully sidestep this inconvenience.

<blockquote>
  <p>
    Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away.
  </p>
  <footer><cite title="Antoine de Saint-Exupéry">Antoine de Saint-Exupéry</cite></footer>
</blockquote>


### Code, with syntax highlighting

Code blocks use the [solarized](http://ethanschoonover.com/solarized) theme. Both the light and
dark versions are included, so you can swap them out easily. _Solarized Dark_ is the default.

{% highlight java %}
public class HelloJekyll {
    public static void main(String[] args) {
        System.out.println("Hello, Jekyll");
    }
}
{% endhighlight %}