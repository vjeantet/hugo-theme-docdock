+++
draft = false
title = "children"
description = "List the child pages of a page"

[menu.main]
parent = "shortcodes"
identifier = "children"
+++


Use the children shortcode to list the child pages of a page and the further descendants (children's children). By default, the shortcode displays links to the child pages.

## Usage

| Parameter | Default | Description |
|:--|:--|:--|
| style | "li" | Choose the style used to display descendants. It could be any HTML tag name |
| nohidden | "false" | When true, child pages hidden from the menu will not display |
| description  | "false" | Allows you to include a short text under each page in the list.<br/>when no desription exists for the page, children shortcode takes the first 70 words of your content. [read more info about summaries on gohugo.io](https://gohugo.io/content/summaries/)  |
| depth | 1 | Enter a number to specify the depth of descendants to display. For example, if the value is 2, the shortcode will display 2 levels of child pages. {{%alert success%}}**Tips:** set 999 to get all descendants{{%/alert%}}|
| sort | none | Sort Children By<br><li><strong>Weight</strong> - to sort on menu order</li><li><strong>Name</strong> - to sort alphabetically on menu label</li><li><strong>Identifier</strong> - to sort alphabetically on identifier set in frontmatter</li><li><strong>URL</strong> - URL</li> |



## Demo

	{{%/* children  */%}}

{{%children %}}

	{{%/* children description="true"   */%}}

{{%children description="true"   %}}

	{{%/* children nohidden="true" */%}}

{{% children nohidden="true" %}}

	{{%/* children style="h3" depth="3" description="true" */%}}

{{% children style="h3" depth="3" description="true" %}}

	{{%/* children style="div" depth="999" */%}}

{{% children style="div" depth="999" %}}






