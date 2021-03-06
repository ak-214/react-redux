# react-redux
This is the basic tutorial of react-redux. :dart: 
---

## about redux
* State Management library
* Makes creating complex application easier

## redux cycle
> Action Creator --> Action --> Dispatch --> Reducer --> State
 
**Action** are payloads of information that send data from your application to your store. They are the only source of information for the store. You send them to the store using ``store.dispatch().``

**Reducers** specify how the application's state changes in response to actions sent to the store. Remember that actions only describe what happened, but don't describe how the application's state changes.

The **Store** is the object that brings them together. The store has the following responsibilities:
 * Holds application state;
 * Allows access to state via getState();
 * Allows state to be updated via dispatch(action);
 * Registers listeners via subscribe(listener);
 * Handles unregistering of listeners via the function returned by subscribe(listener).

# Implementation
 ## 1. songs/
 This is an demonstration app. Shows list of songs and it's details
 
 ### Installation
* Create react-app : songs
> `` create-react-app songs ``
* Install redux library
> `` npm install --save redux``
* Install react-redux libary
> `` npm install --save react-redux `` <br />
> **react-redux** library used to talk with redux.
 
### File Structure
> ``/action`` contains files related to action creators <br />
> ``/components`` contains files related to components <br />
> ``/reducers`` contains files related to reducers <br />
> ``index.js`` set up both the react and redux sides of the app <br />`


## 2. blog/
 List of blog post, posted by user.

 ## Installation
 * Create react-app : blog
 > ``create-react-app blog``
 * Install redux library
 > `` npm install --save redux``
 * Install react-redux libary
 > `` npm install --save react-redux `
 * Install axios library
 > ``npm install --save axios`` <br />
 > **axios** Helps us to make network requests
 * Install redux-thunk library
 > ``npm install --save redux-thunk`` <br />
 > **redux-thunk** middleware to help us make request in redux applicaton. 
  
