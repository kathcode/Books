<span style="color:red; font-size:1.5em;">
  1. React vs Angular (Difference) - Difference in processing the DOM
</span>

### **Definition:**
- Angular JS is a Javascript **framework** written in TypeScript. Developed by Google.

- React is a Javascript **library** developed by Facebook.

 ### **Architecture of React vs. Angular (Framework vs. Library)**
**Angular** as a framework tell you how your application should be be structured. React is more has a kind more flexibility because is a library and because allow you to decide what to use in your application.

**React** just provide you the _View_, and you need to do the _Model_ and the _Control_.

**React** use **Virtual DOM** it means that the virtual DOM just look at the changes in the document and update just the part of the document that has a change.

**Angular** use a regular DOM, so if it need to update something then it will update the entire tree of document.

[Reference...](https://programmingwithmosh.com/javascript/stateful-stateless-components-react/)

<span style="color:red; font-size:1.5em;">
  2. Stateless vs stateful components
</span>

The difference between stateless and the stateful, is that the stateless doesn't have state and the stateful has a state.

```javascript

// STATEFULL COMPONENT

class Main extends Component {
 constructor() {
   super()
   this.state = {
     books: []
   }
 }
 render() {
   <BooksList books={this.state.books} />
 }
}
```

```javascript

// STATELESS

const BooksList = ({books}) => {
 return (
   <ul>
     {books.map(book => {
       return <li>book</li>
     })}
   </ul>
 )
}
```

<span style="color:red; font-size:1.5em;">
  3. What is JSX
</span>
