## Hello!

- This is a solution for a challenge on [devChallenges](https://devchallenges.io)

### Links
- See live site:[Here](https://ozlemxates.github.io/Recipe-Page-Master-devchallenges/)

### Built With
- Semantic HTML5 markup
- CSS Flex
- Figma

### What I learned and did

While doing this challange I tried to practice using the ::before pseudo-element. I used the element to create a logo-like dots group and a counter. I now understand how it works better🫡

```html
<h1>Here is the little dots and counter</h1>
```
```css
header p:before {
    content: "• • •\A • • •";
    font-size: 12px;
    line-height: 0.5;
    color: #C4C4C4;
    position: absolute;
    display: inline-block;
    white-space: pre-wrap;
    top: 0;
    left: 0;
}

.instructions p::before {
    content:counter(counter); 
    counter-increment: counter;
    position: absolute;
    left: -47px;
    background-color: #F2994A;
    width: 36px;
    height: 36px;
    color: #FFFFFF;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 6px;
}
```

### Continued development

I tried to make the design as close as possible to given figma design. Yet I could not figure out how to solve some problems. I want to solve them soon!

### Author
-Thats me!
-[My GitHub](https://github.com/ozlemxates)

### Thanks! 🚀