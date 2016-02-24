---
title:  "Teste 1"
date:   2016-01-21 10:18:00
description: Post teste
published: true
category: snippets
tags: ruby
---

## Mais um post teste

https://twitter.com/Raspberry_Pi/status/702189870991745029

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

<h1>An embedded video</h1>
{{ oembed http://www.youtube.com/watch?v=Sv5iEK-IEzw }}

<h1>An embedded presentation</h1>
{{ oembed http://www.slideshare.net/AmitRanjan/quick-tour }}

{% tweet https://twitter.com/Raspberry_Pi/status/702189870991745029 %}

