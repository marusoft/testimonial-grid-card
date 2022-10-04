- [ ] Create five divs with different classes
- [ ] Add p tag with content in each of the five divs
- [ ] Give each divs their respective background color
- [ ] Wrapper all the five divs with a container in order to give them some padding
- [ ] Give them some space around and some space within
- [ ] Divide the testimonial card into two section: left(first four divs) and right section(last div)
- [ ] Divide the left section into sub-section top(first and scend div) and bottom(third and fourth div).
- [ ] Separate the fifth div from the first four by doing display: flex on the

```
@media (min-width: 576px) {
   .testimonial-grid-container{
      display: flex
    }
}
```
- [ ] Add flex-basis: 25px to the fifth div in order to look like the design
- [ ] Then df to top and bottom section in order to placed side by side
- [ ] Add flex-basis to each of the first four divs in order to achieve the desire design
- [ ] Add max-width to the entire .testimonial-grid-container in order to reduce the width of all the cards and put them at the center with 
`margin: 0 auto`
- [ ] Distribute the space in column direction for both the top and bottom section by adding flex-basis: 50%
- [ ] FIRST OPTION Take 2% from 70% so it become 68% of the flex-basis of .left-section in order for justify-content:space-between to work in .testimonial-grid-container
- [ ] SECOUND OPTION, To make it simple and pretty-straightforward, we can undo all the flex-basis subtraction, remove the justify-content:space-between from the
.testimonial-grid-container, top-section and bottom-section. Then target the .left-section and each .grid-item and apply margin-right to it
- [ ] Then Clean up css file by grouping selectors with similar styling/ruleset