---
layout: post
author: Ricardo Sanchez
---
API Data Formats

There are many different data formats used for your applications to communicate with a wide range of APIs available on the Internet. Each format represents syntax conding data that could be read by another machine but in such a way that is wasy to understand for humands, too.

You will most likely encounter these common data formats:

* YAML Ain't Markup Language (YAML)
* JavaScript Object Notation (JSON)
* eXtensible Markup Language (XML)

YAML

{% highlight yaml %}
---
user:
 name: john
 location:
  city: Austin
  state: TX
 roles:
  -admin
  -user
{% endhighlight %}



JSON
{% highlight json%}
{
 "user":{
  "location":{
   "city":"Austin",
   "state":"TX"
  },
  "roles":[
    "admin",
    "user"
   ]
 }
}
{% endhighlight %}



XML
{% highlight xml %}
<?xml version="1.0" encoding="UTF-8" ?>
<user>
  <name>John</name>
  <location>
    <city>Austin</city>
    <state>TX</state>
  </location>
  <roles>admin</roles>
  <roles>user</roles>
</user>
{% endhighlight %}



Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].


[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
