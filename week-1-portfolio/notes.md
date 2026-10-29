# Reading Note: Week 1

Article: [MDN: The box model](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Box_model)

- Every element is a box made of content, padding, border and margin, from the inside out.
- Padding is space inside the border; margin is space outside it, between elements.
- By default, width only sets the content box, so padding and border make the element bigger than expected.
- Setting `box-sizing: border-box` makes width include padding and border, which makes layouts easier to predict.
