# Let's talk about JavaScript
JavaScript was never meant to be this behomoth of a language that we now have. he plan was simple
Sun Microsystems wanted a simple scripting language that could compliment their more robust language Java. 
In weird way, the fact that JavaScript was merely meant to be a side kick to Java, has in its own twisted way led to the massive development of the language.
What was meant to be a simple scripting language, is now a programming language that goes toe to toe with the language it was supposed to compliment, Java. JavaScript was meant to only run on the browser but nowadays, JavaScript runs on both the Web and servers as well as mobile application and IOT devices.

-Apache Cordova
- Embedded Systems (Espruino and Tessel)

A few key things to differentiate.
- JavaScript is not the Browser.
- JavaScript comes bundled with your browser
- Browser have JavaScript engines that consume your JavaScript code.
  
This unique ability tha JavaScript has, the flixibilty that is sometimes so frowned upon has allowed tht language to become one of the most versitile languages around
Key Differences that JavaScript has compared to other programming languages.
- Functions are first-class objects
- Function Closure 
- Scope
- Prototype-based object orientation

Is it JavaScript or is it ECMAScript?

Talking about Transpilers (Transformation + Compiling):
This allows us to use cutting edge JavaScript code that's not currenly supported then transpile into a version that most browsers support. 



## The Browser Infrastructure
The browser infrastructure is made up of:
- HTML
- CSS
- JavaScript
- Browser APIs
   - The DOM
   - Events
   - Timers
  
  ## Best Practices
  - Debugging Skills
  - Testing
  - Performance Analysis


### Debugging
- Chrome DevTools
- FireBug
- FireFox Dev Tools
- WebKit
  
### Testing
Anatomy of a testing suite
assert(condition,message)
The first parameter is the condition that needs to be met,the second is message that will be output if it fails

```js
 assert(a=== 1, "Disaster! a is not 1!")
```


### Performance Analysis
```js
console.time("My Operation")
for(let i = 0; i < 100000;i++){
  
}
console.timeEnd("My Operation")
```
## Lifecycle Overview
The lifecycl consists of two stages:
- Page Building
- Event Handling
  
  