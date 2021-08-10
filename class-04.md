# React and Forms

![Forms](https://res.cloudinary.com/practicaldev/image/fetch/s--KpQnReJ9--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://i1.wp.com/blogreact.com/wp-content/uploads/2020/03/forms.jpg%3Ffit%3D750%252C393%26ssl%3D1)

- ## React Docs - Forms

***What is a ‘Controlled Component’?***

It is the component that takes its current value through props and notifies changes through callbacks like onChange .

***Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.***

We should update the state with their responses as soon as they enter them, because that input will be a cntrolled component by react and also controls what happens in that form on subsequent user input.

***How do we target what the user is entering if we have an event handler on an input field?***

By creating a function contains the passed in event parameter to get the target input element; from the target get the value and name of the input element.


- ## The Conditional (Ternary) Operator Explained

***1. Why would we use a ternary operator?***

Using a conditional, like an if statement, allows us to specify that a certain block of code should be executed if a certain condition is met.

***2. Rewrite the following statement using a ternary statement:***

```JS
  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
```

***_Selution:_***

```JS
x===y ? console.log(true) : console.log(false)
```

**HI ... my name is Ola 23 years old i'm a Nutritionist and my computer operating system version number is windows 10 and i'm so excited for this course because i want to learn something very important to me**

*click on the [link](https://github.com/olaaltaslaq) to find my GitHub*

