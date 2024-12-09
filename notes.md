# Conquering Responsive Design

## Day 1

By default the width of a block element id 100% of its parent.

Percentage widths on child elements is based on their parent's width

Setting fixed widths can cause overflow issues on the x and y axis

## Day 2

The size of an em unit is determined by its parent. For example, if the root elements size was set to 10px, 2em would be 20px. Em units can compound from one level to the next which can cause unintended consequences.

Rem units are relative to the root element (html or :root) and do not compound.It is best to use rem for font sizing.

If using an em for anything other than font sizing i.e. margin, padding etc., it's behaviour differs. Instead of using the font size of the root element, it uses the font size of the element in which it is declared.
