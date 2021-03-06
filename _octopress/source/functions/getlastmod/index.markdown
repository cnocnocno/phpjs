---
layout: page
title: "JavaScript getlastmod function"
comments: true
sharing: true
footer: true
sidebar: false
alias:
- /functions/view/getlastmod:595
- /functions/view/getlastmod
- /functions/view/595
- /functions/getlastmod:595
- /functions/595
---
<!-- Generated by Rakefile:build -->
A JavaScript equivalent of PHP's getlastmod

{% codeblock info/getlastmod.js lang:js https://raw.github.com/kvz/phpjs/master/functions/info/getlastmod.js raw on github %}
function getlastmod () {
  // http://kevin.vanzonneveld.net
  // +   original by: Brett Zamir (http://brett-zamir.me)
  // %        note 1: Will not work on browsers which don't support document.lastModified
  // *     example 1: getlastmod();
  // *     returns 1: 1237610043
  return new Date(this.window.document.lastModified).getTime() / 1000;
}
{% endcodeblock %}

 - [view on github](https://github.com/kvz/phpjs/blob/master/functions/info/getlastmod.js)
 - [edit on github](https://github.com/kvz/phpjs/edit/master/functions/info/getlastmod.js)

### Example 1
This code
{% codeblock lang:js example %}
getlastmod();
{% endcodeblock %}

Should return
{% codeblock lang:js returns %}
1237610043
{% endcodeblock %}


### Other PHP functions in the info extension
{% render_partial _includes/custom/info.html %}
