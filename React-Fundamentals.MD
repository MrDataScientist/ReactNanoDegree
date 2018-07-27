
## React NanoDegree program : Starting 17 July 2018.

### 1) What is a component? How do components relate to props?

- A component is a reactJS object that knows how to render itself and  combines a bunch of small elements together with the goal of grouping and encapsulating functionality.

- Props are one of the ways to pass data to a component. More in detail, props are the properties available to use for the component.

### 2) How do we know whether something should be a component in React?

- We should use the same intuition as when designing classes in OOP languages: a component should represent an isolated idea/object in our App that groups together all the functionality required to meets the goal of the component.

- As a general rule: we create components to represent ideas in of the business logic of the app and we achieve it’s goal by combining smaller elements through composition.

## Lecture 3 : functional components
### QUESTION 1 OF 2
When is it appropriate to use a Stateless Functional Component? Check all that apply.
- when all the components needs a render() method
- If a component is only using a render method to display content, then it can be converted into a Stateless Functional Component.
