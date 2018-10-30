---
title: Hello World in Every Language
layout: default
---

# Hello World

Hello World is a standard program used to introduce a programming language.
As a result, the rules are pretty simple: print "Hello, World!" to standard
output. Ideally, the solution should be as simple as possible.

## Requirements

To properly implement Hello World, submit a file called Hello World using the
appropriate naming conventions for your language of choice. Upon execution, this
file should print "Hello, World!" to standard output. That's it!

## Testing

Verify that the actual output matches the expected output. See the
[requirements][2] section for an example of the expected output.

## Articles

{% for article in site.hello_world %}    
  {% unless article.title contains 'Every Language' %}
  - [{{ article.title }}]({{ article.url | relative_url }})
  {% endunless %}
{% endfor %}

## Further Reading

-   [Hello World in Every Language by The Renegade Coder][1]

[1]: https://therenegadecoder.com/series/hello-world-in-every-language/

[2]: #requirements