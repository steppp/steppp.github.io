---
title: About
description: This is my website. It is still under development, so come back in a few days to check if it is ready.
---

# Le Me

<p>
{{ page.description }}
</p>

<p>
If you <strong>really</strong> want to know something about me, I can tell you
that my name is Stefano, and I'm from Italy 🇮🇹.
</p>

<p>
I love programming and everything related to PCs and things that you can run
code on.
I am currently studying Computer Science at UniBo (almost finished) and I have
some experience in various tech stacks/frameworks/languages.
Some of these include:

<ul>
<li>iOS programming: Swift, SwiftUI and a bit of Objective-C</li>
<li>Web pages: Angular, Javascript, Typescript, CSS, HTML, a bit of Vue</li>
<li>OS: C kernel programming, Python, Java, C++, C#</li>
</ul>
</p>

<p>
Speaking of something else, I also like videogames, movies, rock/metal music.
Avid coffee drinker and lover of good food 🍕.
</p>

<figure class="imgfigure">
<img src="https://live.staticflickr.com/4851/44966982075_e6a168e2cc_b.jpg" alt="SpaceX docking pad"/>
<figcaption>
SpaceX docking pad
</figcaption>
</figure>

<p>
You can find more info in my <a href="https://www.linkedin.com/in/stefanoandriolo/">LinkedIn page</a>
or see my work in my <a href="https://github.com/steppp">Github profile</a>.
Follow me on Twitter @<a href="https://twitter.com/andri_step">andri_step</a>.

If you want, don't hesitate to contact me at <a href="mailto:stefano.andriolo3@studio.unibo.it">stefano.andriolo3@studio.unibo.it</a>.
</p>

<p>
This is the <code>CSS</code> used to show the separator under the navigation bar:
{% highlight css %}
nav::after {
  content: " ~ ";
  display: inline-block;
  margin: 0px 5%;
  margin-top: $nav-sep-height;
  height: 0.1rem;
  width: 100%;
  text-align: center;
  font-size: 1.5rem;
  font-family: $mono-font;
  color: #ccc;
  line-height: 0.2rem;

  background-image: linear-gradient(to right, $content-bg-col, #ddd 15% 45%, $content-bg-col 45% 55%, #ddd 55% 85%, $content-bg-col);
}
{% endhighlight %}
</p>

Sometimes in this site you will see a paragraph like this:

<p class="payattention">
This paragraph indicates that this text is important and you should carefully read and be sure you understood what is written here.
</p>

When I will quote someone else's words, when I report something taken from another source or when I want to emphasize some particular content, it will have this style:

<blockquote>
This is the reported text with my custom styling. It can be used to highlight some content that could be not as crucial as the one that is contained in a paragraph with the style of the previous one.
</blockquote>

<p>
<strong>Thank you</strong> for visiting my page! Have a nice day!
</p>
