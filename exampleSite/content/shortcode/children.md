+++
draft = false
title = "children"
description = ""

[menu.main]
parent = "shortcodes"
identifier = "children"
+++

This shortcode will list the child pages of a page.

## Usage

| Parameter | Default | Description |
|:--|:--|:--|
| style | "li" | Choose the style used to display descendants. It could be any HTML tag name |
| nohidden | "false" | When true, child pages hidden from the menu will not display |
| depth | 1 | Enter a number to specify the depth of descendants to display. For example, if the value is 2, the shortcode will display 2 levels of child pages. {{%alert success%}}**Tips:** set 999 to get all descendants{{%/alert%}}|


## Demo

	{{%/* children */%}}

{{%children%}}

	{{%/* children nohidden="true" */%}}

{{% children nohidden="true" %}}

	{{%/* children style="div" depth="3" */%}}

{{% children style="div" depth="3" %}}

	{{%/* children style="div" depth="999" */%}}

{{% children style="div" depth="999" %}}






