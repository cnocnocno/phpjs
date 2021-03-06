---
layout: page
title: "JavaScript cos function"
comments: true
sharing: true
footer: true
sidebar: false
alias:
- /functions/view/cos:373
- /functions/view/cos
- /functions/view/373
- /functions/cos:373
- /functions/373
---
<!-- Generated by Rakefile:build -->
A JavaScript equivalent of PHP's cos

{% codeblock math/cos.js lang:js https://raw.github.com/kvz/phpjs/master/functions/math/cos.js raw on github %}
function cos (arg) {
  // http://kevin.vanzonneveld.net
  // +   original by: Onno Marsman
  // *     example 1: cos(8723321.4);
  // *     returns 1: -0.18127180117607017
  return Math.cos(arg);
}
{% endcodeblock %}

 - [view on github](https://github.com/kvz/phpjs/blob/master/functions/math/cos.js)
 - [edit on github](https://github.com/kvz/phpjs/edit/master/functions/math/cos.js)

### Example 1
This code
{% codeblock lang:js example %}
cos(8723321.4);
{% endcodeblock %}

Should return
{% codeblock lang:js returns %}
-0.18127180117607017
{% endcodeblock %}


### Other PHP functions in the math extension
{% render_partial _includes/custom/math.html %}
## Legacy comments
These were imported from our old site. Please use disqus below for new comments
<div style="overflow-y: scroll; max-height: 500px;">
{% render_partial functions/cos/_comments.html %}
</div>
