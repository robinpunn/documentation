## Quick Start

#### Creating and Nesting Components

- React apps are made out of components. 
    - A component is a piece of the UI (user interface) that has its own logic and appearance. 
    - A component can be as small as a button, or as large as an entire page.

- React components are JavaScript functions that return markup:
    ```js
    function MyButton() {
        return (
            <button>I'm a button</button>
        );
    }
    ```

- Now that you’ve declared ``MyButton``, you can nest it into another component:
    ```js
    export default function MyApp() {
        return (
            <div>
                <h1>Welcome to my app</h1>
                <MyButton />
            </div>
        );
    }
    ```

- Notice that <MyButton /> starts with a capital letter. 
    - That’s how you know it’s a React component. 
    - React component names must always start with a capital letter, while HTML tags must be lowercase.
