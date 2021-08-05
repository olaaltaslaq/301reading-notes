# Component Based Architecture

![cba](https://marvel-b1-cdn.bc0a.com/f00000000075552/www.perforce.com/sites/default/files/image/2019-11/image-vcs-blog-monolith-vs-microservices-vs-component-based-development.png) 

## What is a component?

*Components are the building blocks of any React app, a component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities.*

![cba](https://www.techdiagonal.com/wp-content/uploads/2019/08/React-components-blog-image.jpg) 

## What are the charactistics of a component?

- Reusability
- Replaceable
- Not context specific
- Extensible
- Encapsulated
- Independent

## What are the advantages of using component based architecture?

- Ease of deployment
- Modification of technical complexity
- Reliability

# What is “Props” and how to use it in React?

![cba](https://miro.medium.com/max/1400/1*27LtOtFyJe7MguQkNcZQjQ.png) 

## What is props short for?

*It stands for properties, it is a special keyword in React used for passing data from one component to another.*


## How are props used in React?

- Defining attribute and data, with interpolation {}.

```HTML
<ChildComponent text= { “Im the 1st child” } />
```

- Passing data using Props, like we pass 
arguments to a function.

```JS
const ChildComponent = (props) => {  
  return <p>I'm the 1st child!</p>; 
};
```

- Rendering Props data.

```JS
const ChildComponent = (props) => {  
  return <p>{props.text}</p>; 
};
```

## What is the flow of props?

> uni-directional flow, one way from parent to child.

## Things I want to know more about

- I want to use React and know more and more about it.

**HI ... my name is Ola 23 years old i'm a Nutritionist and my computer operating system version number is windows 10 and i'm so excited for this course because i want to learn something very important to me**

*click on the [link](https://github.com/olaaltaslaq) to find my GitHub*



