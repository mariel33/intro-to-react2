React official documentation interesting finds:
- Can develop new features in React without rewriting existing code
- Components can maintain internal state data, and when the data changes the rendered markup will be updated by reinvoking `render()`
- React provides hooks that allow you to interface with other libraries and frameworks
- JSX is similar to a template language but comes with the full power of JavaScript
- You can embed any JS expression in JSX by wrapping it in curly braces
- JSX expressions become regular JS function calls
- React elements are immutable and once you create one you can't change its children or attributes
- You should always start component names with a capital letter (React treats lowercase components as DOM tags)
- All React components must act like pure functions with respect to their props

```
