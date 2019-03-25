## Self-Study/Essay Questions

- [ ] What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

PropTypes are a quality assurance step to ensure correct data types are passed to components in a React application. A component depends on the proper handling of data in React. If incorrect data types are passed then the application can basically break. It's important to make it easy to know when incorrect data is passed, and tell the user how to fix this error.

- [ ] Describe a life-cycle event in React?

- - A life-cycle event is an event that triggers a function (lifecycle method). Each life-cycle event is part of the entire Lifecycle: componentDidUpdate(Birth), componentDidUpdate(Life), and componentWillUnmount(Death). 

- [ ] Explain the details of a Higher Order Component?

- - Higher Order Component (aka HOC) is a  React component that pulls a component as an argument and returns a component. Typically it's some variation of the original component with added functionality.

- [ ] What are three different ways to style components in React? Explain some of the benefits of each.

- - 1) CSS. This has the benefit of open-ended design control - you can design anything. It's also readable to an average developer and easy to implement.

- - 2) Inline styling from JSX. It's nice as it's in the same file as the individual component - although it can cause issues with specificity.

- - 3) Third party module styled-components, like bootstrap or reactstrap. Its nice as it uses both inline and CSS styling: The inline styling is restricted to individual components and props can be used to pass, and it's ulimately transpiled to a CSS stylesheet.