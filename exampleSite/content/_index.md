+++
draft = false
title = "Home"
description = ""
date = "2017-04-24T18:36:24+02:00"


creatordisplayname = "Valere JEANTET"
creatoremail = "valere.jeantet@gmail.com"
lastmodifierdisplayname = "Valere JEANTET"
lastmodifieremail = "valere.jeantet@gmail.com"

+++

<span id="sidebar-toggle-span">
<a href="#" id="sidebar-toggle" data-sidebar-toggle=""><i class="fa fa-bars"></i></a>
</span>


# Hugo docDock theme
[Hugo-theme-docdock {{%icon fa-github%}}](https://github.com/vjeantet/hugo-theme-docdock) is a theme for Hugo, a fast and modern static website engine written in Go. Hugo is often used for blogs, **this theme is fully designed for documentation.**

This theme is a partial porting of the [Learn theme of matcornic {{%icon fa-github%}}](https://github.com/matcornic/hugo-theme-learn), a modern flat-file CMS written in PHP.

{{%panel%}}docDock works with a "page tree structure" to organize content : All contents are pages, which belong to other pages. [read more about this]({{%relref "organisation.md"%}}) {{%/panel%}}

## Main features

* [Search]({{%relref "search.md" %}})
* **Unlimited menu levels**
* [Generate RevealJS presentation]({{%relref "page-slide.md"%}}) from markdown (embededed or fullscreen page)
* Automatic next/prev buttons to navigate through menu entries
* [Image resizing, shadow...]({{%relref "shortcode/image.md" %}})
* [Attachments files]({{%relref "shortcode/attachments.md" %}})
* [List child pages]({{%relref "shortcode/children.md" %}})
* [Excerpt]({{%relref "shortcode/excerpt.md"%}}) ! Include segment of content from one page in another
* [Mermaid diagram]({{%relref "shortcode/mermaid.md" %}}) (flowchart, sequence, gantt)
* [Icons]({{%relref "shortcode/icon.md" %}}), [Buttons]({{%relref "shortcode/button.md" %}}), [Alerts]({{%relref "shortcode/alert.md" %}}), [Panels]({{%relref "shortcode/panel.md" %}}), [Tip/Note/Info/Warning boxes]({{%relref "shortcode/notice.md" %}}), [Expand]({{%relref "shortcode/expand.md" %}})




![](https://raw.githubusercontent.com/vjeantet/hugo-theme-docdock/master/images/tn.png?width=33pc&classes=border,shadow)

## Contribute to this documentation
Feel free to update this content, just click the **Edit this page** link displayed on top right of each page, and pullrequest it
{{%alert%}}Your modification will be deployed automatically when merged.{{%/alert%}}


## Documentation website
This current documentation has been statically generated with Hugo with a simple command : `hugo -t docdock` -- source code is [available here at GitHub {{%icon fa-github%}}](https://github.com/vjeantet/hugo-theme-docDock)

{{% panel theme="success" header="Automated deployments" footer="Netlify builds, deploys, and hosts  frontends." %}}
Automatically published and hosted thanks to [Netlify](https://www.netlify.com/).

Read more about [Automated HUGO deployments with Netlify](https://www.netlify.com/blog/2015/07/30/hosting-hugo-on-netlifyinsanely-fast-deploys/)
{{% /panel %}}

