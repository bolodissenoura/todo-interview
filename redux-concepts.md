### Redux concepts
[x] - Toolkit
[x] - Store
[x] - Reducer
[x] - useSelector
[] - dispatch
[] - Provider
[] - Common
[] - actions
[] - Slices
[] - saga
[] - Thunk ( Middewares )


> When use Redux?
- When we are losting ourselves into the code and lost informattion about differents contexts;
- When you need to store something and group this logic in one unique place;

> What is Redux?
- The common way to describe redux is "A global state manager", an this is right. But it's also much more;
- Redux can be a way to STORE all the logic of a single context in one unique place;
- Redux can handle with Prop Drilling;
- Redux is used when we need to handle with informations of our application, an a information can be much more than a single data object. It can be a interactions of our user, can be breadcrumbs that the user leave on our application, can be handle with HTTP requests, dispatch errors and much more;

#### Toolkit ( RTK )
- I already had to install, step-by-step the Redux in a real application, and I know how much verbose and hard can be to do that;
- Also, without toolkit you package.json looks like a really big text, and that not cool to manage and handle with as a developer;
- Redux Toolkit is there for this reason. A toolbox that you can open and use, without hard presets, just plug and play;

#### Store
- As the name explains, the Store is to ... STORE things ( wow );
- Is a common place for all our application's state;

#### Reducer
- The Reducers are functions that take the `state` and `action` as arguments and determinate how the `state` of an context should change whenever a `action` is called;
- And retrun a new `state` result;
- The Reducers are responsible for manipulating the `state` directly;

#### useSelector
- useSelector ( as the `use` mention ) is a hook, that redux provide us, to access the state and read the data of an state;

