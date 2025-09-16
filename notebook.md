# My coding notebook

## Table of Contents
- [Flutter Notes](#Flutter-notes)
  - [what is flutter?](#what-is-flutter)
  - [Key Terms and Definitions](#Key-Terms-and-Definitions)
  - [Layout and Design Widgets](Layout-and-Design-Widgets)
-[Code Definitions](Code-Defenitions)
- [Notebook Style Guide](#markdwon-style-guide-for-coding-notebooks)

## Flutter Notes 

### What is Flutter?
- Definition:
- Why is it useful?

---

### Key Terms and Definitions

| Term             | Definition                                      | Example / Notes                          |
|------------------|--------------------------------------------------|-------------------------------------------|
| Widget           | Basic building block of a Flutter app. Everything is a widget.          |            Text, Image, Container, Colum               |
| MaterialApp      |  The root of the app. Sets up routes and themes.                                               | Found in main. dart                                           |
| Scaffold         |  Provides basic visual layout-like a header,body, floating button     |                         Each screen uses it                     |                                           |
| StatelessWidget  |  A widget that doesn't change                                               |  Most of the screen files                                         |
| StatefulWidget   |  A widget that can change over time                                               | Used in MyHomePage()                                          |
| Navigator        |  Manages screen transitions                                               |Navigator.pushNamed(context, '/page2');                                           |
| AppBar           |  Top navigation bar                                               | Title of each page appears here                                          |
| Column           |  vertical layout                                 |                                          |
| Row              | horizontal layout                                |                                           |
| Container        |  wraps content with padding, margin, or color    |                                           |
| Text             |  displays text                                   |                                           |
| Image.network    |  displays images from a URL                      |                                           |
|  Padding         |  adds space around a widget                      |                                           |
|  Center          |   centers its child                              |                                           |














## Flutter Definitions

|Term             | Definition                                      | Example / Notes                          |
|------------------|--------------------------------------------------|-------------------------------------------|
| Widget           | Basic building block of a Flutter app. Everything is a widget.          |            Text, Image, Container, Colum               |
| MaterialApp      |  The root of the app. Sets up routes and themes.                                               | Found in main. dart                                           |
| Scaffold         |  Provides basic visual layout-like a header,body, floating button     |                         Each screen uses it                     |                                           |
| StatelessWidget  |  A widget that doesn't change                                               |  Most of the screen files                                         |
| StatefulWidget   |  A widget that can change over time                                               | Used in MyHomePage()                                          |
| Navigator        |  Manages screen transitions                                               |Navigator.pushNamed(context, '/page2');                                           |
| AppBar           |  Top navigation bar                                               | Title of each page appears here                                          |
| Column           |  vertical layout                                 |                                          |
| Row              | horizontal layout                                |                                           |
| Container        |  wraps content with padding, margin, or color    |                                           |
| Text             |  displays text                                   |                                           |
| Image.network    |  displays images from a URL                      |                                           |
|  Padding         |  adds space around a widget                      |                                           |
|  Center          |   centers its child                              |                                           |






































##Coding defenitions

Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|------|------------|--------------------------|-------------------|------------|
| variable     | A named container used to store a value that may change. | `var x = 5;` |Weight is 125  | app example later |
| constant     | A fixed value that cannot change once set. | `const PI = 3.14;` |The 7 days in a week never changes.  |  |
| Data Type     | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` | Age vs Words in a sentence. |  |
| String     | A sequence of characters used to represent words or text. | `"Hello World"` |A title  |  |
| Integer    | Whole number values. | `int age = 16;` |Seeing your health score number from 100 - 0  |  |
| Double     | Number values with decimals. | `double age = 16.2;` |Calculations  |  |
|Boolean      | A value that can be true or false. | `bool isLoggedIn = false;` |If I practice that day, will my streak go up?  |  |
|List      | A collection of values in a specific order. | `List<String> names = [];` |Newest to oldest release  |  |
|Null     | A special value that means “nothing.” | `String? name = null;` |Unloaded level  |  |
|Function      | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |Repeating the level again on a game.  |  |
| Parameter     | The information passed into a function to change how it works. | `greet(String name)` |Choosing your video game character color or style.   |  |
| Return     | The result a function gives back. | `return total;` |Are you part of the militray? If yes, the result will be entering in the militray. If no, the result will be leaving the area.  |  |
| Scope     | Where a variable or function can be used. | (No set syntax — concept-based) |Gift cards for specific places.  |  |
| Class     | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` |Creating a waterbottle with a defined structure.  |  |
| Object     | A specific version of a class. | `Dog myDog = Dog();` |my lil jit weighths 170  |  |
|property      | A variable that belongs to a class/object. | `String name;` ||  |
|method      | A function that belongs to a class. | `void bark() {}` |  |  |
|
 A special function used to set up a class when it’s created. | `Dog(this.name);` |  |  |
|      | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |  |  |
|      | Changing how a built-in or inherited function behaves. | `@override` |  |  |
|      | A function that does not return a value. | `void printMessage() {}` |  |  |
