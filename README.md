# rn-starter
React project  
  

# Steps to get into this project
- Download the zip project and extract all into a folder (be sure you know where is saved because we are going to come back).
- Open you folder and the project with your code editor.
- Open your terminal and in the projects directory run `npm install`, this will install all dependencies needed.
- Then you can run `npm start` to open expo and look every screen, or you can run an emulator
- That's it! :)

# Screens:
Btw, you may wanna check what this screen does and how they work... here below are some of them in case you want to take a look:  
[Home](https://github.com/gabyross/rn-starter/blob/main/README.md#home-screen)
[Component](https://github.com/gabyross/rn-starter/blob/main/README.md#component-screen)
[List](https://github.com/gabyross/rn-starter/blob/main/README.md#list-screen)
[Counter](https://github.com/gabyross/rn-starter/blob/main/README.md#counter-screen)
[Image](https://github.com/gabyross/rn-starter/blob/main/README.md#image-screen)
[Color](https://github.com/gabyross/rn-starter/blob/main/README.md#color-screen)
[Square](https://github.com/gabyross/rn-starter/blob/main/README.md#square-screen)
[Box](https://github.com/gabyross/rn-starter/blob/main/README.md#box-screen)
[Text](https://github.com/gabyross/rn-starter/blob/main/README.md#text-screen)  

# Home Screen:

## Info about what contains this screen (Buttons):

### Button:
- Very simple component for showing a button and detecting a press.

It is a primitive element. A primitive element is something that we import from the React Native Library, and in this case it's called button.

### Touchable Opacity.
- Highly customizable component that can detect a press on just about any kind of element.

This is a very customizable, primitive component and allows us to essentially tag detect a press event or like a user tapping on something and on just about any kind of element inside of application.

So it could be like a piece of text or an image or just about 
anything else.

## Code: 
Lets a user to navigate between all these different screens.


# Component Screen:
## Code :
It shows how to apply some simple styling and variables use.


# List Screen:

## Info about flat list:
Its a primitive element to take an array of records and turn it into some list to display on the screen of our device.

When we make use of the flat list element, we are always going to pass in two different props (props are configuration options).

- The first required prop is called data, so we have to pass in an array of records, and we want to turn into a collection of react elements to show on the screen.

- Now, Fleshless doesn't technically just figure out for us how to display each of these different elements, instead it's up to you and me to provide a function called the *render item* prop that's going to be called with every individual element out of that array. And it's going to be up to you and me to return from that function the second required prop.

## Code:
This its basically an array of objects where each object has maybe a name property.

In here, every object inside of here represents a friend.

We could also have an array of numbers or array of strings or an array of absolutely anything.

But in general, when we are building out a list with React Native, our starting point is an array.

Note: The primitive element we use in this scree is called the flat list.


# Counter Screen:

## What is a state:
It is a mutable data store of components, i.e., the values of the states can change.

## Code:
How to increment or decrement a number by using state.


# Image Screen:

## Code:
Here we have three group of element, repeated three times.
We could repeat the same JSX three times over, or we could create a separate component and then show that component three times on the single screen (exactly what we are doing).

Each time we show that component, we pass in some configuration options or props to customize how that component gets displayed.

So in other words, we  create one new component called image screen, and then separately we create a new component called image detail.

This image detail thing is responsible for showing one of these individual cards that has a image and some text next to it.

Now, each of these image detail components shows a different image in some different piece of text, so we customize how these different components are displayed by passing them some props from the image screen down to the image detail.


# Color Screen:

## Some information you may wanna look again:

### State: 
The state system is all about tracking a piece of data that's going to change over time inside of our application.
And any time that piece of data changes, we might want to somehow update the content on the screen of our device.

### Props:
The prop system is all about communicating data from a parent to a child.

All right, I think we can now take a look to what our code does.

## Code:
At the very top, we're going to show a simple button that says add color.

Whenever a user taps on this, we're then going to generate a random color and show it in a very little box underneath that button.

So maybe the first color we generate randomly would be pink and we could show that right underneath.

Then if a user taps on that button again, I want to generate a new color at random.

Maybe the next one is like yellow or red, maybe it is purple.

And then every time the user taps on that button, we're going to show another randomly colored box like so.


# Square Screen:

## Code:
- Its basically hot to increment or decrement RGB values, so like this we can change the square's color.


# Box Screen

## How do we style a native app and make it look really nice?

Well, first off, I want you to understand that there are three different systems or properties that we're going to use to control how elements are displayed in react.

### Native application.

These three systems are the *object model, the flexible system and a single property called position* with a box object model.

You might be familiar with this from the world of Web development.

We're talking about properties like margin, border and padding and also the intrinsic height and width of some element.

### Box Object Model:
We are going to use it any time that we're trying to position a single element by itself.
- The height/width of an element + the space around it.
- Use this to affect the positioning of a single element.

### Flex Box:
This  system is concerned with how we lay out some number of child elements that are all inside of one common parent.
We're going to use this flexible system each time that we're trying to position multiple elements within one common parent element.
- How some number of sibling elements get laid out inside a parent.
- Use this to position multiple elements with a common parent

### Position:
We're going to use this property any time we want to override the box object model or the flex box systems.
- How a single element gets laid out inside of a parent


Now, in order to understand these three different systems, you really have to look at some different examples.

So let's flip back over to our code.

### Code
Use this screen to take a look at this box object model system
Here we go through flex and then position.


# Text Screen:

## Code:
We're going to show a enter name, little label right there underneath that will show a text input.

We want a user to enter some text into that input.

And as they do, we're going to print out whatever the user types character by character as the user types it.
