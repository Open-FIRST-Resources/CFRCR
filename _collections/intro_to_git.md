---
title: Introduction to Git
resources:
-
  title: Collection Specific Content
  type: custom
-
  title: What is Git?
  type: term
  term: git
-
  title: "Cloning: CLI"
  type: document
  path: git/cli/cloning.md
-
  title: "Cloning: EGit"
  type: document
  path: git/egit/cloning.md
-
  title: Video!!!
  type: youtube
  id: EMiNmJW7enI
  companion:
    title: What is Git?
    type: term
    term: git
-
  title: Non-existant type
  type: none
-
  title: Non-existant document
  type: document
  path: ":()"
---
{% include collection/custom_begin title="Collection Specific Content" %}
This is how you would add custom resources to the thing. You know, the thing stored in {% include term text="git" %}. Besides `liquid` includes, markdown (if the collection file ends with .md) works normally:
- Item
- Item
- Another Item

1. Thing 1
2. Thing 2
3. Etc...

# ALL CAPS!!!

{% highlight liquid linenos %}{% raw %}
{% if this == that %}

{% endif %}
{% endraw %}{% endhighlight %}