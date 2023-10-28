---
title: "Know and Hold your useState Hook"
seoTitle: "what is Usestate Hook React"
datePublished: Sun Jul 02 2023 17:48:05 GMT+0000 (Coordinated Universal Time)
cuid: cljlq6rmo000e09jt3nbsgowo
slug: know-and-hold-your-usestate-hook
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1688158906969/9f3d5702-9cf5-411d-a4fa-fe588116e7aa.png
tags: web-development, react-native, reactjs, meta, metaverse

---

### **What is Hook?:**

The hook is a very good tool in React. It was added to React in Version 16.8. Hooks allow functional components to have access to state and other React features. This makes class components not to be needed. Since the introduction of Hooks, class components has being replaced with functional components.

The useState is a react Hook that enables a developer in adding state variables to functional components.

<mark>const [state, setState] = useState(initialState);</mark>

The useState returns two arrays, the current state and the function to update. An initial state is passed to the Hook <mark>useState(initialState)</mark> and returns an updated state value whenever the setter function is called.

The useState is called at the top level of our component

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1688160746143/7cefbd93-cc14-4d1e-8cb7-cc99031809f2.png align="center")

Stages in implementing useState.

*Stage1*: import the useState Hook at the top of Your component

<mark>import {useState} from ‘react’;</mark>

***Stage2***: we initialize useState  <mark>useState(initialState)</mark> by calling useState in our function component.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1688161323531/54a6c27d-f769-48d8-bd9d-2eeeb252422d.png align="center")

Here the argument passed inside the useState() is the initialState <mark>20</mark>, <mark>omeke</mark>, <mark>University of Port Harcourt Nigeria</mark>. respectively

The idea here is to make state variables like \[something setSomething\].

*Let’s analyze the parameters deployed for useState.*

From this; <mark>[state, setState] = useState(initialState);</mark>

<mark>useState</mark>: the useState returns an array with two values;

i.The current state <mark>(initialState)</mark>

ii. The set function (setState). This state enables us to update the state to a different value and this trigger a re-render

Note that the useState can only be called at the top level of your component, it can not be called inside of loops, conditionals, and nested functions.

The set function lets **u**s update the state to a different value like setSomething(nextState)

***Stage 3***\*:\* we update what’s on the screen by calling the next state.

`function onClick() {`

`setSomething(‘new value’);`

`}`

the set function does not change the current state of the already executing code it only affects what useState will return starting from the next render.

*Stage4:* We pass our return value

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1688207116601/e0f40151-99d8-498d-af05-7b7ae65c5482.jpeg align="left")

### Basic Application of useState Hook

Below is an example of a Hook state that uses a functional component. Here the `count` state variable holds a number. Clicking the button increments the number of times ikechukwu touches me.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1688204036537/2a9c4420-27c4-4c6b-877e-de18d6931cb3.png align="center")

We declare a new state variable by calling the useState Hook. which Returns a value pair, countValue, with the number of clicks and setCount, which updates the count value.

Initialize countValue to zero by passing zero as the useState argument.

When the user clicks on setCount with a new value, react will re-render the component and pass in the new value of the countValue.

<mark>Conclusion</mark>

The useState Hook is very important for every Frontend Engineer to be familiar with, it helps us create and track the state changes.