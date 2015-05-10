# babel-sublime-snippets

Sublime snippets for [ES6+ JavaScript](http://kangax.github.io/compat-table/es6/) and [React](http://facebook.github.io/react/docs/component-specs.html).

## Installation

Find it as [**Babel Snippets**](https://packagecontrol.io/packages/Babel Snippets) through [Package Control](https://packagecontrol.io/).

## Using the "React: wrap in a component" snippet

First, select a block of JSX. Then, from the Command Palette select "React: wrap in a component". Or, you can set up a key binding.

To set a key binding, go to "Preferences: Key Bindings - User" from the Command Palette and add an entry like this:

```json
{
  "keys": ["ctrl+shift+,"],
  "command": "insert_snippet",
  "args": {
    "name": "Packages/Babel Snippets/react_wrap.sublime-snippet"
  }
}
```

## Available snippets

### ES6

### React

| Trigger  | Content |
| -------: | ------- |
| `rcc→`   | class component skeleton |
| `rcc→`   | legacy component skeleton |
| `cdm→`   | `componentDidMount() {…}` |
| `cdup→`  | `componentDidUpdate(prevProps, prevState) {…}` |
| `cwm→`   | `componentWillMount() {…}` |
| `cwr→`   | `componentWillReceiveProps(nextProps) {…}` |
| `cwun→`  | `componentWillUnmount() {…}` |
| `cwup→`  | `componentWillUpdate(nextProps, nextState) {…}` |
| `fdn→`   | `React.findDOMNode(…)` |
| `gdp→`   | `getDefaultProps() {…}` |
| `gis→`   | `getInitialState() {…}` |
| `ren→`   | `render() {…}` |
| `sst→`   | `this.setState(…)` |
| `scu→`   | `shouldComponentUpdate(nextProps, nextState) {…}` |
| `props→` | `this.props` |
| `state→` | `this.state` |

## Notes

  * Unsupported React API snippets: `displayName`, `forceUpdate`, `getDOMNode` (use `React.findDOMNode`), `ismounted`, `mixins`, `propTypes`, `replaceProps`, `replaceState`, `setProps`, `statics`.

## Snippet(ing)

Read [Extending Sublime Text » Snippets](http://sublime-text-unofficial-documentation.readthedocs.org/en/latest/extensibility/snippets.html).
