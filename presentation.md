# INTRODUCTION TO NODE.JS
### Twitter: @steph_happens

---

### Why was the Javascript developer sad?

---

### Because they didn't Node how to Express themselves!
___

![](http://i0.kym-cdn.com/entries/icons/original/000/014/959/Screenshot_116.png)

___

## What is Node.js

---

## According to NodeJs.org

---

#### Node.js® is a **JavaScript runtime** built on **Chrome's V8 JavaScript engine**. Node.js uses an **event-driven, non-blocking I/O model** that makes it lightweight and efficient. Node.js' **package ecosystem, npm**, is the largest ecosystem of open source libraries in the world.

---

## Javascript runtime

---

## V8 Javascript Engine

___

## Event-driven, non-blocking I/O model

---

## npm ecosystem

---

## Computers??

---

![](https://media.giphy.com/media/Ysce790SgjJK0/giphy.gif)

---

## so yeah…

---

## Confused

---

## Me too.

---

## Javascript Runtime
## V8 Javascript engine

---

## event-driven, non-blocking I/O model

---

### Objective: Print file contents

___

## Blocking

###  // Read file from Filesystem, set equal to “contents” //
### // Print contents //
### // Do something else //

___

# VERSUS
___

## Non-blocking

### // Read file from Filesystem, set equal to “contents” //
### // Print contents //
### // Do something else //

___

## Node Code

___

## Blocking

``` javascript
const contents = fs.readFileSync('/etc/hosts');
console.log(contents);
console.log('Doing something else');
```

___

## Non-blocking

``` javascript
fs.readFile(‘index.html’, function(err, contents) {
console.log(contents);
});
console.log(‘Doing something else rn’);
```

___

![](http://media1.giphy.com/media/8mjyUVMiNmOLS/giphy.gif)

___

## Event driven
### AKA the node event loop

___

## npm, is the largest ecosystem of open source libraries in the world

---

#### Node.js® is a **JavaScript runtime** built on **Chrome's V8 JavaScript engine**. Node.js uses an **event-driven, non-blocking I/O model** that makes it lightweight and efficient. Node.js' **package ecosystem, npm**, is the largest ecosystem of open source libraries in the world.

---

## What is Node Not

---

## HTTP Server

---

## A language

---

## A toy

---

## Why node

---

## Node was created to be better than ruby

---

## Jk

___

# :smiling_imp:

---

## 2009


---

![](https://media.giphy.com/media/l3q2uTMBcedNfsNxe/giphy.gif)

---

## 2017

---

# what is it good for?


---

# well a lot actually

---

# NASA

---

![](http://cdn.collider.com/wp-content/uploads/interstellar-matthew-mcconaughey-anne-hathaway.jpg)

---

# But Really

---

![](http://www.esa.int/var/esa/storage/images/esa_multimedia/images/2009/11/luca_parmitano/9844876-3-eng-GB/Luca_Parmitano.jpg)

___

# Better Developers??
# Yass!

---

# 75%

---

# 63%

---

![](https://i.imgur.com/knj0Uy6.jpg)

---

# Yeah, but what now?
- [Introduction to Node.js](https://blog.hellotangible.com/an-absolute-beginners-guide-to-node-js-c27e6d108b5c)
- [Everything you need to know about the Node.js event loop](https://www.youtube.com/watch?v=PNa9OMajw9w)
- [Why the hell would you use Node.Js](https://medium.com/the-node-js-collection/why-the-hell-would-you-use-node-js-4b053b94ab8e)
- [Wes Bos Node.js Course](https://learnnode.com/)

- Extra Credit- [Scott Hanselman](https://www.youtube.com/watch?v=IWPgUn8tL8s)

---

# Thanks!!
#### stephanie@lewiscommuncations.com
#### twitter: @steph__happens
#### thehealthydev.com
