### CSS 

## Transitions
CSS transitions provide a way to control **animation speed** when changing **css properties**. \
For example, if you want to change the color of an element from white to black, usually the change is instantaneous.\
With CSS transitions enabled, changes occur at time interval that follow an acceleration curve, all of which can be customized.

### Defining transitions
- transition-property: Specifies the name or names of the CSS properties to which transitions should be applied.
- transition-duration: Specifies the duration over which transitions should occur.
- transition-timing-function: Specifies how the animation will be executed over the time
  - ease
  - linear : Always the same speed
  - step-end
- transition-delay: Define how long to **wait** between the time a property is changed and the transition actually begins.

#### Shorthand
```css
div {
    transition: <property> <duration> <timing-function> <delay>;
}
```


- [List of css properties that allows add transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animated_properties)


#### Links

- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions

