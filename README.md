# React-To-Do

A simple React JS ToDo application 

What I have learned:
- useState() hook
- useRef() hook
- useEffect() hook
- use of LocalStorage in React apps
- ReactDom render

We use the useEffect() hook to use React functionality like writing a state or other features without writing a class. It is more efficient in some cases because we do not have to repeat the same code. In useEffect() hook React will remember the effect it needs to perform after render. The effects (operations) can be performed inside a function. 

useState() hook allows to add state functionality to function components. Argument passed into the state hook is the initial state and it does not have the be an object like in classes. It is faster to update the state using this hook as we only need to pass the set variables. 

useRef() hook holds current value set from the corresponding DOM node. It creates a plain js object which will stay the same on each render. 

To create a random UUID...

1. Install

npm install uuid

2. Create a UUID (ES6 module syntax)

import { v4 as uuidv4 } from 'uuid';
uuidv4(); // ⇨ '9b1deb4d-3b7d-4bad-9bdd-2b0d7b3dcb6d' 

