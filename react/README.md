# React Interview Questions

1.What is React?

React is a javascript library for rendering user interfaces(UI). UI is built from small units like buttons, text, and images. React lets you combine them into reusable components. From websites to phone apps, everything on the screen can be broken down into components.

2.What is the React component?

Component is a basic Building Block of our React Application. React applications are built from isolated pieces of UI called components. A React component is a normal JavaScript function that returns JSX. Components can be as small as a button, or as large as an entire page. React lets you combine your markup, CSS, and JavaScript into custom `components`, reusable UI elements for your app.

##### Steps To Create a React Component :

1.  Export the component ⇒ The export default prefix is a standard JavaScript syntax (not specific to React). It lets you mark the main function in a file so that you can later import it from other files. 2. Define the function ⇒ function Profile() { } you define a JavaScript function with the name Profile.

`Note : React components are regular JavaScript functions, but their names must start with a capital letter or they won’t work!`

3. Add markup ⇒
   The component returns an <img /> tag with src and alt attributes. <img /> is written like HTML, but it is actually JavaScript under the hood! This syntax is called JSX, and it lets you embed markup inside JavaScript.
   Return statements can be written all on one line, as in this component:

##### Example

```javascript
return <img src='https://i.imgur.com/MK3eW3As.jpg' alt='Katherine Johnson' />;
```

But if your markup isn’t all on the same line as the return keyword, you must wrap it in a pair of parentheses:

##### Example

```javascript
return (
    <div>
        <img src='https://i.imgur.com/MK3eW3As.jpg' alt='Katherine Johnson' />
    </div>
);
```
