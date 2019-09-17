- [ ] Why would you use class component over function components (removing hooks from the question)?
If you need access to the lifecycle hook then you would need class components as functional components don't have it
- [ ] Name three lifecycle methods and their purposes.
componentDidMount- can fetch data, use then statements, replaces axios 
componentDidUpdate - can receive props, setState, force update, utilize render
componentWillUnmount- completes the component, end of lifecycle

- [ ] What is the purpose of a custom hook?
lets you use state and features without writing a class

- [ ] Why is it important to test our apps?
allows to you target and specify any issues down to the component
isolates the errors
