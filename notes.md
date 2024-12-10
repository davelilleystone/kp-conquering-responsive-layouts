# Conquering Responsive Design

## Day 1

By default the width of a block element id 100% of its parent.

Percentage widths on child elements is based on their parent's width

Setting fixed widths can cause overflow issues on the x and y axis

## Day 2

The size of an em unit is determined by its parent. For example, if the root elements size was set to 10px, 2em would be 20px. Em units can compound from one level to the next which can cause unintended consequences.

Rem units are relative to the root element (html or :root) and do not compound.It is best to use rem for font sizing.

If using an em for anything other than font sizing i.e. margin, padding etc., it's behaviour differs. Instead of using the font size of the root element, it uses the font size of the element in which it is declared.

## Day 3

The `max-width` property avoids the issue where content spreads too far horizontally. You combine a `width` setting with `max-width`. As an example, setting {`width: 80%, max-width: 750px`} will mean the element will have 80% width until it hits 700px wide where it will then stop widening

There is a `min-width` property that does the opposite of `max-width`. This can be used to stop an element shrinking beyond a certain size.

## Day 4

vw and vh are units of measurement based on the viewport width and height. Widths and heights are based on the width / length of the viewport and parent width is not taken into consideration like setting a width / height using a percentage.

vmin and vmax are also based on the above. They depend on what is the largest or smallest dimension in the viewport. As an example, 10vmin will be 10% of the height or width, depending on what is the smallest. vmax works in a similar way but relates to the largest dimension.
