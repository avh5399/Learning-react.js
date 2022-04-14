# Learning React.js 
  
### Why React? 

#### What is React?
- JavaScript library for building user interfaces 
- Declarative for dynamic data
- Component based 
- A "language" to model the state of UIs, not the transactions of them

#### Disadvantages of Frameworks 
- Limited flexibility 
  - Do things a certain way 
  - Hard to deviate
- Large and full of features 
  - Hard to customize 
  - Use the whole thing

#### Why is React Popular?
- Allows you to work with "virtual" browser (vs. DOM API)
- Similar to Javascript, small learning curve to learn React API
- Can use React skills to pick up React Native to build iOS and Android apps 
- Thorough testing by Facebook team and releases rarely have bugs
- Declaratively describe stateful user interfaces (model UI and state)


### React's Basic Concepts

#### Fundamental Concepts
- Components 
  - Like functions 
  - Input: props, state | Output: UI
  - Reusable and composable
  - Can use it as if it is a regualr HTML element `<Component />`
  - Can manage a private state to hold any data that may change over the lifecycle of the component.
- Reactive Updates 
  - React will automatically update the parts of the DOM that need to be updated 
  - Take updates to the browser 
- Virtual views in memory 
  - Generate HTML using JS
  - No HTML template Language 
  - Allows react to keep and use a virtual representation of HTML views in memory - Virtual DOM or Tree reconciliation algorithm

#### React Components
- React app is a set of reusable components
  - They take input and they output a description of a user interface in the for m a react element 
  - React DOM library enables us to render the react elements in a browser and rerender them automatically when their in meory state changes
- Types of Components
  - Function Component 
  - Class Component 

#### JSX
- JSX is a syntax enxtension to JS 
- Can use it with React to describe what the UI should look like 
- rendering logic is inherently coupled with other UI logic
  
#### Props and State 
- Input for a component is a set of properties you can access inside the component with its first argument object
- `(props) => {}`
- `[val, setVal] = useState(initialVal)`
- Immutable props. Mutuable state 

#### ReactDOM.render
- syntax to mount a React component in the browser is `ReactDOM.render`
  - `<Component />`
  - DOM node - HTML element to hold the React-rendered markup

#### React events 
- normalized events that work across all browsers that work in a standard way