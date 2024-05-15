Code Complete
=============

Official summary:
- Design for minimum complexity and maximum creativity
- Reap the benefits of collaborative development
- Apply defensive programming techniques to reduce and flush out errors
- Exploit opportunities to refactor--or evolve--code, and do it safely
- Use construction practices that are right-weight for your project
- Debug problems quickly and effectively
- Resolve critical construction issues early and correctly
- Build quality into the beginning, middle, and end of your project



https://softwareengineering.stackexchange.com/questions/2777/what-are-the-key-points-of-code-complete
--> nice summary there!


# Coding Style

Be Consistent.

- Follow the project's existing coding standard.
- If there is no coding standard and you are editing an existing code-base owned by someone else - be consistent with the style of the existing code, no matter how much you like / dislike it.
- If you are working on a green-field project - discuss with other team members, and come to a consensus on a formal or informal coding standard.
- If you are working on a green-field project as the sole developer - make up your own mind, and then be ruthlessly consistent.

Being consistent could include using different styles in different scenarios.


## Curly Braces

For a long time I argued that they were of equal worth, or so very close to equal that the
possible gain by making the right choice was far, far, below the cost of arguing about it.


https://softwareengineering.stackexchange.com/questions/2715/should-curly-braces-appear-on-their-own-line

Readability

```c
void MyFunction(
    int parameterOne,
    int parameterTwo) {
    int localOne,
    int localTwo
}
```


Maintainability
There are BAD styles

```c
void MyFunction(int parameterOne,
                int parameterTwo) {
    int localOne,
    int localTwo
}
```

But mainly CONSISTENCY.
