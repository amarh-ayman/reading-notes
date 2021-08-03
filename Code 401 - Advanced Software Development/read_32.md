# React

# JSX
 
> *It separates concerns with loosely coupled units called “components” that contain both.*

##  Embedding Expressions in JSX

> *In the example below, we declare a variable called name and then use it inside JSX by wrapping it in curly braces:*


```
const name = 'Josh Perez';
const element = <h1>Hello, {name}</h1>;

ReactDOM.render(
  element,
  document.getElementById('root')
);

```

**You can put any valid JavaScript expression inside the curly braces in JSX.**


## JSX is an Expression Too

> *After compilation, JSX expressions become regular JavaScript function calls and evaluate to JavaScript objects.*


## Specifying Attributes with JSX

> *You may use quotes to specify string literals as attributes:*

```
const element = <div tabIndex="0"></div>;
```

## State and Lifecycle 

> *Components let you split the UI into independent, reusable pieces, and think about each piece in isolation.*


## Function and Class Components
> *The simplest way to define a component is to write a JavaScript function:*


```

function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}

```

## Composing Components


> *Components can refer to other components in their output. This lets us use the same component abstraction for any level of detail. A button, a form, a dialog, a screen: in React apps, all those are commonly expressed as components.*


```
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}

function App() {
  return (
    <div>
      <Welcome name="Sara" />
      <Welcome name="Cahal" />
      <Welcome name="Edite" />
    </div>
  );
}

ReactDOM.render(
  <App />,
  document.getElementById('root')
);
```

> *It accepts author (an `object`), text (a `string`), and date (a `date`) as props, and describes a comment on a social media website.*