# Intro to Web Dev

* HTML - Hypertext Markup Language
* CSS - Makes style sheets, selecting similar objects
* JS - JavaScript, default logic programming language

These allow you to create better:
1. Responsiveness
2. Accessibility
3. SEO

## Minor heading

[Here's a link to the Markdown lookup!](https://markdownlivepreview.com/)

```
module Dlatch(input d, clk, output Q, Qn);
  nand(w1, d, clk);
  nand(w2, ~d, clk);
  nand(Q, Qn, w1);
  nand(Qn, Q, w2);
endmodule
module Dflip(input d, clk, output Q, Qn);
  Dlatch latch1(d, ~clk, Qplanned, x);
  Dlatch latch2(Qplanned, clk, Q, Qn);
endmodule
```
