# SENG-LIVE-013023 Phase 2 - React

## Phase Level Objectives

- Design a React component hierarchy based on a wireframe
- Use React to create components that interact with an API
- Incorporate client-side routing into a single-page application in React


| Lecture | Notes | Videos | Starter | Solution |
| ------- | :---: | ------ | ------- | -------- |
| 1. (02/21/23) Components & Props     |  [Slides](https://raw.githack.com/learn-co-curriculum/SENG-LIVE-013023-Phase-2-React/main/01_components_and_props/assets/export/index.html), [Notes](https://docs.google.com/document/d/1PaEUsoVruIU3pSUOz9jlsfVhxrwB1N7XPYbmak03wKg/edit?usp=sharing)     |  [Video](#)      |    [Starter](https://github.com/learn-co-curriculum/SENG-LIVE-013023-Phase-2-React/tree/main/01_components_and_props)     |   [Solution](#)       |
| 2. (02/22/23) State & Events     |  [Notes](https://docs.google.com/document/d/1PaEUsoVruIU3pSUOz9jlsfVhxrwB1N7XPYbmak03wKg/edit?usp=sharing)     |   [Video](#)     |    [Starter](#)     |    [Solution](#), [Local variables vs state variables](https://codesandbox.io/s/counter-state-example-0r8stb?file=/src/App.js), [SmartHome app - Passing State as Props](https://codesandbox.io/s/vigilant-minsky-iiykrb)      |
| 3. (02/23/23) Information Flow     |  [Notes](https://docs.google.com/document/d/1PaEUsoVruIU3pSUOz9jlsfVhxrwB1N7XPYbmak03wKg/edit?usp=sharing)     |  [Video](#)      |   [Starter](#)      |    [Solution](#), [SmartHome app with clickable bulbs](https://codesandbox.io/s/smarthome-with-clickable-bulbs-woyctp), [SmartHome app with individually clickable bulbs](https://codesandbox.io/s/smarthome-with-individually-switchable-bulbs-du3hot)      |
| 4. (02/24/23) Forms     |   [Notes](https://docs.google.com/document/d/1PaEUsoVruIU3pSUOz9jlsfVhxrwB1N7XPYbmak03wKg/edit?usp=sharing)    |   [Video](#)     |   [Starter](#)      |  [Solution](#), [controlled form with single state object](https://codesandbox.io/s/refactoring-a-controlled-form-with-individual-pieces-of-state-juv663?file=/src/App.js), [controlled form with individual pieces of state](https://codesandbox.io/s/controlled-form-with-individual-pieces-of-state-pbjpe4?from-embed)        |
| 5. (02/27/23) Side Effects & Data Fetching     |  [Notes](https://docs.google.com/document/d/1PaEUsoVruIU3pSUOz9jlsfVhxrwB1N7XPYbmak03wKg/edit?usp=sharing)     |   [Video](#)     |   [Starter](#)      |   [Solution](#), [useEffect cleanup demo](https://codesandbox.io/s/useeffect-cleanup-ig17kd?file=/src/Timer.js)       |
| 6. (02/28/23) PATCH & DELETE     |   [Notes](https://docs.google.com/document/d/1PaEUsoVruIU3pSUOz9jlsfVhxrwB1N7XPYbmak03wKg/edit?usp=sharing)    |   [Video](#)     |    [Starter](#)     |   [Solution](#)       |
| 7. (03/03/23) Client-Side Routing     |   [Notes](https://docs.google.com/document/d/1PaEUsoVruIU3pSUOz9jlsfVhxrwB1N7XPYbmak03wKg/edit?usp=sharing)    |    [Video](#)    |   [Starter](#)      |    [Solution](#)      |

## 1: Components and Props
### SWBATs:
- Review the benefits of React over Vanilla JS 
- Review the difference between HTML and JSX
- Review the importance of Components
- Review how a component is written
- Explain what props are and how to create them
- Recognize best practices when writing components and props
- Observe how to render multiple components from a list
### Lecture Topics:
- JSX
- Components
- Props
- Destructuring


## 2: State & Events

### SWBATs:
- Explain the importance of state
- Explain the difference between state and props
- Observe how to use the useState hook
- Observe how to use DOM events in React
### Lecture Topics:
- Creating & Updating State
- Events
- Callbacks
- useState


## 3: Information Flow
### SWBATs:
- Define the term “lifting state”
- Recognize the pattern for changing state in a parent component from a child component
- Explain the role that callback functions play in changing parent state
- Observe how we can render reusable components that invoke different callback functions after an event
- Recognize destructured props and how to work with them
### Lecture Topics:
- Callback functions as props
- Changing parent state
- Reusing components w/ different behaviors

## 4: Forms
### SWBATs:
- Explain the difference between a controlled and uncontrolled input
- Explain why controlled inputs are preferred by the React community
- Review how to use callback functions with events in React
- Review how to change parent state from a child component
### Lecture Topics:
- Controlled vs uncontrolled inputs
- Forms

## 5: Side Effects & Data Fetching

### SWBATs:
- Explain what a side effect is
- Observe how React manages side effects with the useEffect hook
- Observe how to use the useEffect hook to fetch data on page load
- Observe how to send a POST request via form
- Review changing parent state
### Lecture Topics:
- useEffect
- Dependency array
- fetch => GET & POST

## 6: PATCH & DELETE
### SWBATs:
- Observe how to send a PATCH & DELETE request
- Review changing parent state
### Lecture Topics:
- fetch => PATCH & DELETE

## 7: Client Side Routing

### SWBATs:
- Review the difference between server-side and client-side routing
- Observe a refactor to include client-side routing using React Router V5
- Explain what a nested route is
- Observe how to handle nested client-side routes 
### Lecture Topics:
- React Router
