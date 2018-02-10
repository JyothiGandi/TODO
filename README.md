# TODO
My checklist 🙂

1) Promises/Async&Await/Fetch - do some sample examples for better understanding
    https://classroom.udacity.com/courses/ud898
    https://jakearchibald.com/2017/async-iterators-and-generators/
    https://davidwalsh.name/fetch
2) Start doing a REACT application
    use ES6
    https://frontendchecklist.io/#section-javascript
3) Go through webpacks    
3) kotlin vs go
4) Joy building Architecture 
5) Get really good understanding of sessions and tokens

# Feb 10 2018 

Learnt lessons after making my first React application 💖

- design the components before starting the APP
- careful with the usage of "state" object elements and keep a proper track of the state elements of a component
- use React-bootstrap instead of bootstrap
- App used to crash (UI used to go to white screen) when there is any javascript error. Found that by using "componentDidCatch()" method we can prevent app from crashing. As this method catches every javascript error, we can also log the error to an error reporting service.
- An update to a mounted component can be caused by any change to props or state. So if you want the change to be reflected based on a particular prop change, then use "componentWillReceiveProps(nextProps)" method. This method is called everytime when there is a change in the props/state. Handle the update by comparing this.props and nextProp inside the method.
- Got an issue i.e. Failed to execute 'removeChild' on 'Node': The node to be removed is not a child of this node (I used bootstrap alert and on click of the close button, the alert got successfully closed. But later started showing this error in the console)
