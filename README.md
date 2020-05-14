## __Code Snippets__
This VS Code Extension provides snippets to make it easy to code.
<br/><br/><br/>


# References

## React JS
### `react.class`
React Component is named based on its filename
```js
// MyComponent.js

import React, { Component } from "react";

class MyComponent extends Component {

  render() {
    return (
      <div className="MyComponent">

      </div>
    );
  }

}

export default MyComponent;
```



### `react.constructor`
Creates the __Constructor__ for a Class component
```js
  constructor(props) {
    super(props);
    this.state = {

    };
  }
```



### `react.mount`
Creates the __componentDidMount__ method for a Class component
```js
  componentDidMount() {
    
  }
```



### `react.unmount`
Creates the __componentWillUnmount__ method for a Class component
```js
  componentWillUnmount() {
    
  }
```



### `react.catch`
Creates the __componentDidCatch__ method for a Class component
```js
  componentDidCatch(error, info) {
    
  }
```



### `react.props-state`
Creates the __getDerivedStateFromProps__ method for a Class component
```js
  static getDerivedStateFromProps(props, state) {
    return null;
  }
```



### `react.error-state`
Creates the __getDerivedStateFromError__ method for a Class component
```js
  static getDerivedStateFromError(error) {
    
  }
```



### `react.render`
Creates the __render__ method for a Class component\
_ClassName_ is derived from its filename
```js
    render() {
      return (
        <div className="MyComponent">

        </div>
      );
    }
```



### `react.export`
Creates export statement for React component.
```js
export default MyComponent;
```



### `react.export-redux`
Creates export statement for React component with Redux.
```js
export default connect(mapStateToProps, mapDispatchToProps)(MyComponent);
```



---


## React-Redux
### `react.connect-redux`
Create everything needed to export the component with redux.
```js
const mapStateToProps = state => {
  return {

  };
};

const mapDispatchToProps = {
  
};

export default connect(mapStateToProps, mapDispatchToProps)(MyComponent);
```



### `redux.mapStateToProps`
Creates __mapStateToProps__ function.
```js
const mapStateToProps = state => {
  return {

  };
};
```



### `redux.mapDispatchToProps`
Creates __mapDispatchToProps__ object.
```js
const mapDispatchToProps = {

};
```



---


## Redux
### `redux.reducer`
Creates the starter code for Redux Reducer
```js
const initialState = {
  
};

export default function(state = initialState, action) {
  switch(action.type) {



    default:
      return state;
  }
};
```



### `redux.action.const`
Creates the Redux action constant
```js
export const CONSTANT_NAME = "CONSTANT_NAME";
```



### `redux.action.function`
Creates the Redux action function
```js
export const functionName = () => {
  return {
    type: CONSTANT_NAME,
    payload: {
      
    },
  };
};
```



### `redux.action.function.dispatch`
Creates the Redux action function using dispatch
```js
export const functionName = () => {
  return dispatch => {
    
  };
};
```