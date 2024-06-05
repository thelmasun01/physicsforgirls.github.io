---
layout: post
title: About Physics For Girls Summer Workshop
subtitle:  What is our mission?
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
mathjax: true
author: Yongwen Sun
---

{: .box-success}
Physics for Girls Summer Workshop's mission is to offer a hands on, immersive, and fun introduction to physics for girls in Grades 7-9.

**4-Year's history**

Physics is a very daunting and intimidating subject to approach at first, which is why many students shy away from learning it. However, physics is everywhere! It is the basics to all sciences, and therefore it is a very important subject as well. With growing stereotypes about girls in STEM, my goal is to help girls trespass that boundary and allow them to freely explore the fun and interesting elements of physics.

This workshop is cost-free, and offers introductory mini-lessons on mechanics (dynamics and kinematics), hands-on labs, guest speakers, and much more. The class capacity is 20, and is first come first serve, so make sure to sign up as soon as possible! Classes will take place from August 7-August 11, from 9:00 AM - 12:00 PM at Ferguson Township Elementary School. Further information will be sent out once a class is established. Deadline to signup is July 30th.

If you have further questions, please email me at thelmasun01@gmail.com

​

Hope to see you there!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg)

It can also be centered!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})
