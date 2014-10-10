---
title: Show and hide line number in vim
author: Rituraj Ratan
layout: post
permalink: /2014-10-10-show-and-hide-line-number-in-vim
disqus: http://www.vim4u.com/2014-10-10-show-and-hide-line-number-in-vim
path: 2014-10-10-show-and-hide-line-number-in-vim.md

---

In vim default line number are not shown so to show the line number in vim we need to set it also we can unset.here i am describe how to show and hide line number.
Thsi command will not run in insert and visual mode it will work in command mode. to go command mode press ESC key then write below for       

### Show line number in vim
{% highlight html %}

:set number
or 
:set nu

{% endhighlight %}

### Hide line number in vim
{% highlight html %}
:set nonumber

or 

:set nonu

or 

:set nu!

{% endhighlight %}


-----

If you want by default when vim load this above setting then write in .vimrc file

{% highlight html %}

set number

or

set nu

like as we mention on above

Thanks!

{% endhighlight %}