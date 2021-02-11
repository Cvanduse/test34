+++
author = "Hugo Authors"
title = "Emoji Support test"
date = "2019-03-05"
description = "Guide to emoji usage in Hugo"
tags = [
    "emoji",
]
+++

Emoji can be enabled in a Hugo project in a number of ways. 
<!--more-->
The [`emojify`](https://gohugo.io/functions/emojify/) function can be called directly in templates or [Inline Shortcodes](https://gohugo.io/templates/shortcode-templates/#inline-shortcodes). 

To enable emoji globally, set `enableEmoji` to `true` in your site's [configuration](https://gohugo.io/getting-started/configuration/) and then you can type emoji shorthand codes directly in content files; e.g.

<p><span class="nowrap"><span class="emojify">🙈</span> <code>:see_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙉</span> <code>:hear_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙊</span> <code>:speak_no_evil:</code></span></p>
<br>

The [Emoji cheat sheet](http://www.emoji-cheat-sheet.com/) is a useful reference for emoji shorthand codes.

***

**N.B.** The above steps enable Unicode Standard emoji characters and sequences in Hugo, however the rendering of these glyphs depends on the browser and the platform. To style the emoji you can either use a third party emoji font or a font stack; e.g.


<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Hugo 0.24 Released: Big archetype update + <a href="https://twitter.com/Netlify?ref_src=twsrc%5Etfw">@Netlify</a> _redirects etc. file support<a href="https://t.co/X94FmYDEZJ">https://t.co/X94FmYDEZJ</a> <a href="https://twitter.com/hashtag/gohugo?src=hash&amp;ref_src=twsrc%5Etfw">#gohugo</a> <a href="https://twitter.com/hashtag/golang?src=hash&amp;ref_src=twsrc%5Etfw">#golang</a> <a href="https://twitter.com/spf13?ref_src=twsrc%5Etfw">@spf13</a> <a href="https://twitter.com/bepsays?ref_src=twsrc%5Etfw">@bepsays</a></p>&mdash; GoHugo.io (@GoHugoIO) <a href="https://twitter.com/GoHugoIO/status/877500564405444608?ref_src=twsrc%5Etfw">June 21, 2017</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


{{< highlight html >}}
.emoji {
  font-family: Apple Color Emoji, Segoe UI Emoji, NotoColorEmoji, Segoe UI Symbol, Android Emoji, EmojiSymbols;
}
{{< /highlight >}}

{{< css.inline >}}
<style>
.emojify {
	font-family: Apple Color Emoji, Segoe UI Emoji, NotoColorEmoji, Segoe UI Symbol, Android Emoji, EmojiSymbols;
	font-size: 2rem;
	vertical-align: middle;
}
@media screen and (max-width:650px) {
  .nowrap {
    display: block;
    margin: 25px 0;
  }
}
</style>
{{< /css.inline >}}
