### React core concepts

- Class vs functional components;
- Handling exceptions;
- Interaction with REST API concepts and the best way to handle with HTTP Requests Management;
- Advantages of React
- Props vs States
- Viertual dom vs Real Dom

#### Class vs functional components

> What is a component ?

Imagine your whole application as a Lego Build. It have a lot of pieces that together make you build on. <br/>
Whit React is the same, each piece we call `<Component />`. And a component normally it's build to can be used in every place that we need it.

So imagine you have a button on your application and need to use the same button multiple times. You don't need to build one new button everytime you need to use it.<br/>
You just need to componentize this `<Button />` and use it whenever you want. Making this you avoid some over-coding, make your code more organized and avoid new errors.

> Ok, now we can learn the difference between class vs functional

- Basically the differences are Syntax, State and Lifecycle, Code Length and Readability and Performance.

> Class Components

- Class components are defined using ES6 class syntax and must include a `render` method that retun a JSX;
- Also, in the syntax to handle with states you need to use `this.state` and to uptade the state value you use `this.setState`;
- Class components can use lifecycles methods like `componentDidMount` , `componentWillUnmount` and `componentDidUpdate`, to handle with side effects at differents stages of our application lifecycle;
- So, to understand better witch one, we can make a comparison with a `kid playing with a toy` context.

`componentDidMount`: "The toy is ready to play with!" – Happens after the toy is fully built.
`componentDidUpdate`: "I just changed something on my toy!" – Happens after you make changes to the toy.
`componentWillUnmount`: "I'm putting my toy back in the box!" – Happens right before you put the toy away.


> Now, let's go for the acctual version of React and the way that we uses it on a uptaded application.
> Functional Components

- Are defined as a Javascript functions;
- They return JSX directly from the function body ( no needs render );
- And after version 16 of React, we have now the Hooks. And we use Hooks in every contexts on our application.
- Hook is a function. A special function. We can create our own Hooks to handle with intern logics that repeats at the app and we commonly use the default Hooks created by React. They are `useState`, `useEffect`, `useMemo`, `useRef`, `useReducer`



