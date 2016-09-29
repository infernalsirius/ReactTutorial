# *FIRST STEPS WITH REACT*

**Tutorial**: *https://tylermcginnis.com/react-js-tutorial-pt-1-a-comprehensive-guide-to-building-apps-with-react-js-8ce321b125ba#.sbj8vlobn*

### Tools used in this tutorial

* **Gulp** to build to Javascript
* **Browserify** to tie component together
* **Flux** to structure the application efficiently
* **Firebase** for data persistance
* **React router** for routing



### React concept used in this tutorial
* Props
* State
* JSX

### Tutorial part
**Pt I**: A Comprehensive Guide to Building Apps with React.js.

**Pt II**: Building React.js Apps with Gulp, and Browserify.

**Pt III**: Architecting React.js Apps with Flux.

**Pt IV**: Add Routing to your React App with React Router. (Coming Soon)
**Pt V**: Add Data Persistence to your React App with Firebase. (Coming Soon)
**Pt VI**: Combining React.js, Flux, React Router, Firebase, Gulp, and Browserify. (Coming Soon)


### Concepts

##### **Component:**
* Collection of HTML, CSS and JS files + data properties
* A component can be define in pure Javascript or using JSX
* Data can be received from parent component or can be contained in the component itself

#### Fundamental aspects
* JSX — Allows us to write HTML like syntax which gets transformed to lightweight JavaScript objects.
* Virtual DOM — A JavaScript representation of the actual DOM.
* React.createClass — The way in which you create a new component.
* render (method) — What we would like our HTML Template to look like.
* ReactDOM.render — Renders a React component to a DOM node.
* state — The internal data store (object) of a component.
* getInitialState — The way in which you set the initial state of a component.
* setState — A helper method for altering the state of a component.
* props — The data which is passed to the child component from the parent component.
* propTypes — Allows you to control the presence, or types of certain props passed to the child component.
* getDefaultProps — Allows you to set default props for your component.
* Component LifeCycle
* componentWillMount — Fired before the component will mount
* componentDidMount — Fired after the component mounted
* componentWillReceiveProps — Fired whenever there is a change to props
* componentWillUnmount — Fired before the component will unmount
* Events
* onClick
* onSubmit
* onChange

#### Making a component
* Render method is required.


#### React.DOM.render
* Usually used only once in the application