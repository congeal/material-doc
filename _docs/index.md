---
layout: doc
title: Welcome
permalink: /docs/home/
redirect_from: /docs/index.html

---

This site aims to be a guide to Material Doc.

Material Doc is a Material Designed Jekyll template for documentation site. Using structure from [Jekyll Documentation][jekyll-doc], and style from [Materialize][materizlize].

Use this template, you can easy create a Material Design style documentation site.

Key features of this template:

1. Material Design style with mobile friendly responsive layout.
2. Compatible with [GitHub Pages][github-pages]. No other hosting service needed.
3. Fully support Markdown files, to make it easy to write new docs & pages.
4. Cool technologies like SASS, Markdown, icon font, etc, to make the site work in future.

For how to use this template, read next doc. <i class="mdi mdi-github"></i>

Unordered list
* First
    * Nested 1
* Second
* Third

Ordered list
1. First
    1. Nested 1
        1. Nested 1
        1. Nested 1
    1. Nested 2
        * Unordered
1. Second
    * Unordered
1. Third

### Code highlight
```verilog
module assign_test #(
    parameter W_DATA = 4
)
(   input clk, resetn,
    input [W_DATA-1:0] i_data,
    output reg [W_DATA-1:0] o_data
);
    // comment
    always_ff @(posedge clk or negedge resetn)
        if(!resetn)
            o_data <= '0;
        else
            o_data <= i_data;
endmodule
```

[jekyll-doc]: http://jekyllrb.com/docs/home/
[materizlize]: http://materializecss.com/
[github-pages]: https://pages.github.com/
