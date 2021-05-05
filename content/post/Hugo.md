---
title: "Hugo"
date: 2021-04-05T20:03:58-05:00
draft: false
---
{{< rawhtml >}}
<br />
{{< /rawhtml >}}

***
{{< rawhtml >}}
<p>Setting up a basic site with <a href="https://gohugo.io/">Hugo</a> and adding a theme was super fast, however as I add more content I have run into a few issues that I will address here.  

<h3>Markdown vs HTML</h3>
<p>If you are planing on simple blog posts, Markdown gives plenty of flexibility, however if you would like more control in styling the content html may be a better option. This <a href="https://anaulin.org/blog/hugo-raw-html-shortcode/">post</a> shows how to set up a simple shortcode so you can use HTML instead of Markdown in the content files. This video explains what shortcodes can do and how you can create your own. Hugo also provides its own <a href="https://gohugo.io/content-management/shortcodes/#use-hugos-built-in-shortcodes">list of shortcodes </a>that can be used with Markdown as well. </p>
<br/>

<iframe width="350" height="200" src="https://www.youtube.com/embed/2xkNJL4gJ9E" class="center" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br/>

<h3>File Structure</h3>
<p>After some trial and error I was able to add a custom CSS sheet.  First the css file must be added in the config.toml as part of the customCSS array. The file(s) must be stored in a folder called "assets" at the root level. Images must also be placed in a specific location, a folder at the root level named "static" with a "images" subfolder.</p>
<br/>
<img src="/images/Structure.png" class="center" width="700" height="350">


{{< /rawhtml >}}
