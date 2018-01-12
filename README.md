# wheres-my-change

You've always wanted to practice your change making skills! Now's your chance!

![Final Product Example](https://github.com/junior-devleague/wheres-my-change/blob/master/assets/example.png)

## Objective

Use **JavaScript Functions**, **Objects**, **Math Methods**, and **Arrays** to simulate the customer-cashier interaction. Think about returning different values from functions.

## Prerequisites

To complete this project, students should have the following:
* Basic understanding of HTML structures and attributes.
* Basic understanding of Flexbox.
* Strong grasp of JavaScript and DOM (Functions, Objects, Methods)

## Concepts

JS | Description
-- | -----------
IIFE | Stands for Immediately-Invoked Function Expressions. Function executes right after being defined!
return | The return statement stops the execution of a function and returns a value from that function.

## Your Challenge

### Part I

To complete Part I, fulfill the following requirements:
1. Set up your project file structure through the command line.
2. Create the following:
* HTML file
* CSS file
* JS file
* Assets folder (from repo)
3. Link all of your files correctly.

---

### Part II HTML

To complete Part II, fulfill the following requirements:

1. Create the following elements nested in the order of their parent-child relationships.
* ```div``` with an ```id``` of "container".
  * ```audio``` with ```id``` of "money-sound" and ```src``` of the "flip.wav" file.
  * ```audio``` with ```id``` of "chaching-sound" and ```src``` of the "chaching.wav" file.

    ---

  * ```div``` with an ```id``` of "counter".
    * ```div``` with an ```id``` of "customer".
      * ```img``` with ```src``` of the "happy.png" file.
    * Empty ```div``` with an ```id``` of "table".
    * ```div``` with an ```id``` of "change".
      * ```h3``` with an ```id``` of "change-text" and text "Change: ".
      * ```button``` with an ```id``` of "restart" and text "Restart".
      * ```button``` with an ```id``` of "give" and text "Give Change".

    ---

  * ```div``` with an ```id``` of "cashbox".
    * ```div``` with an ```id``` of "bill-20" and ```class``` of "bill money" (spacing between the "bill" and "money" indicates that it has two classes: bill and money).
      * ```h2``` with ```class``` of "money-text" and text of "$ 20". (Include the space between the $ and 20).
    * ```div``` with an ```id``` of "bill-10" and ```class``` of "bill money".
      * ```h2``` with a ```class``` of "money-text" and text of "$ 10".
    * ```div``` with an ```id``` of "bill-5" and ```class``` of "bill money".
      * ```h2``` with a ```class``` of "money-text" and text of "$ 5".
    * ```div``` with an ```id``` of "bill-1" and ```class``` of "bill money".
      * ```h2``` with a ```class``` of "money-text" and text of "$ 1".
    * ```div``` with an ```id``` of "cent-25" and ```class``` of "coin money".
      * ```h2``` with a ```class``` of "money-text" and text of "25 c".
    * ```div``` with an ```id``` of "cent-10" and ```class``` of "coin money".
      * ```h2``` with a ```class``` of "money-text" and text of "10 c".
    * ```div``` with an ```id``` of "cent-5" and ```class``` of "coin money".
      * ```h2``` with a ```class``` of "money text" and text of "5 c".
    * ```div``` with an ```id``` of "cent-1" and ```class``` of "coin money".
      * ```h2``` with a ```class``` of "money text" and text of "1 c".

    ---

  * ```div``` with an ```id``` of "computer-speech" and ```class``` of "dialogue".
    * ```h3``` with ```class``` of "title" and text "Computer says: ".
    * ```h1``` with ```id``` of "comp-text" and text "Welcome to the web store!".

    ---

  * ```div``` with an ```id``` of "customer-speech" and ```class``` of "dialogue".
    * ```h3``` with ```class``` of "title" and text "Customer says: ".
    * ```h1``` with ```id``` of "cust-text" and text "Hi!".
---

### Part III CSS

To complete Part III, fulfill the following requirements:

#### Take out the little white spaces in the margins of the body.
1. Target the ```body``` element.
* Set the margin to 0px.

#### Modify the default sizes and styles of the h1, h2, and h3.
2. Target the ```h1``` element.
* Set the font-size to 18px.

3. Target the ```h2``` element. We're going to style this to look like a coin and the inner part of the dollar bills!
* Set the width to 60px.
* Set the height to 60px.
* Set the background-color to rgb(230,230,230).
* Set the font-size to 17px.
* Turn it into a circle! *Hint: Use the border-radius property!*
* Activate flexbox!
* Center the elements horizontally using flexbox.
* Center the elements vertically using flexbox.
* Set the border to 3px solid rgb(180,180,180).

4. Target the ```h3``` element.
* Set the font-size to 16px.

#### Center the elements and specify size and color of our biggest container.
5. Target the ```id``` of "container".
* Set the width to the full view width.
* Set the height to the full view height.
* Set the background-color to rgb(240,240,240).
* Activate flexbox!
* Arrange the elements in a COLUMN using flexbox.
* Center the items horizontally using flexbox.
* Center the items vertically using flexbox.

#### Style the "counter" area where our customer will reside.
6. Target the ```id``` of "counter".
* Activate flexbox!
* Arrange the elements in a COLUMN using flexbox.
* Center the items horizontally using flexbox.
* Center the items vertically using flexbox.

7. Target the customer's image element.
* Turn it into a circle!

8. Target the ```id``` of table.
* Set the width to 300px.
* Set the height to 2px.
* Set the background-color to rgb(120,120,120).
* Curve the edges just a little. *Hint: Use the border-radius property!*

9. Target the ```id``` of change. This is where we will display the change we've made.
* Set the width to 100%. This is 100% of the width of its parent container.
* Set the height to 100%. This is 100% of the height of its parent container.
* Set the top margin to 10px.
* Activate flexbox!
* Arrange the elements in a COLUMN using flexbox.
* Center the items horizontally using flexbox.
* Center the items vertically using flexbox.

#### Style the cashbox where we will store our cash and coins.

10. Target the ```id``` of "cashbox".
* Set the width to 750px.
* Set the height to 180px.
* Set the background-color to rgb(50,50,50).
* Activate flexbox!
* Arrange the elements in a ROW using flexbox.
* Place horizontal SPACE AROUND the elements using flexbox.
* Center the items vertically using flexbox.
* Set the position to absolute. We can now control how many pixels this element will be away from the sides of the page.
* Set the bottom to 0px. This will make it stick to the bottom of the page.
* Curve the edges of the box a little! *Hint: Use the border-radius property!*
* Set the border to 10px solid rgb(20,20,20).

11. Target the ```class``` of "money".
* Activate flexbox!
* Center the items horizontally using flexbox!
* Center the items vertically using flexbox!

12. Create a **:hover** pseudoclass on the ```class``` of "money".
* Set the border to 10px solid rgb(154,205,50).

13. Target the ```class``` of "bill".
* Set the width to 80px.
* Set the height to 130px.
* Set the background-color to rgb(119,187,101).
* Set the border to 10px solid rgb(20,180,91).
* Curve the edges a little bit.

14. Target the ```class``` of "coin".
* Set the width to 70px.
* Set the height to 70px.
* Turn it into a circle! *Hint: Use the border-radius property.*

#### Style the dialogue for our computer and customer!

15. Target the ```class``` of "dialogue".
* Set the width to 400px.
* Set the min-height to 100px. This will ensure that our boxes are at least 100px but will expand if the text doesn't fit.
* Set the background-color to white.
* Activate flexbox!
* Arrange the elements in a COLUMN using flexbox.
* Center the items horizontally using flexbox.
* Center the items vertically using flexbox.
* Enable flex-wrapping to occur if needed.
* Curve the edges a little!
* Set the position to absolute.
* Set the top to 0px. This will make our dialogue boxes stick to the top.

16. Target the ```id``` of "computer-speech".
* Set the left property to 250px. This will arrange the dialogue box 250 pixels away from the left edge of the window.

17. Target the ```id``` of "customer-speech".
* Set the right property to 250px. This will arrange the dialogue box 250 pixels away from the right edge of the window.

Woohoo!! That was quite a lot of HTML and CSS. Onto JavaScript!

---

### Part IV JS

To complete Part IV, fulfill the following requirements:

1. Create a window.onload function as follows:

``` javascript
window.onload = function() {
  //code goes in here
}

```
#### Store your money in a variable.

2. Create a ```variable``` "money" that will store all the elements of the **class** "money-text".

#### Store the audio files in variables.

3. Create a ```variable``` called "moneySound" that will store the money-sound audio.

4. Create a ```variable``` called "chachingSound" that will store the chaching-sound audio.

#### Store the buttons in variables.

5. Create a ```variable``` called "restart" that will store the restart button.

6. Create a ```variable``` called "give" that will store the give button.

#### Store the divs where we will change the text in variables.

7. Create a ```variable``` called "custText" that will store the element with ```id``` "cust-text".

8. Create a ```variable``` called "compText" that will store the element with ```id``` of "comp-text".

9. Create a ```variable``` called "change-text" that will store the element with ```id``` of "change-text".

10. Create a variable called changeMaker and set that equal to 0.

#### Create objects to store the items that your customer can buy.

11. Create a ```variable``` called "apple" that will store an ```object```. This ```object``` will contain properties "name" and "price" as follows.

```JavaScript
var apple = {
  name: "apple",
  price: 3.23
}
```
You can make up your own prices!

**Create variables called "grape", "banana", "coconut", and "lemon", or other grocery items of your choice.**

13. Create a ```variable``` called "items" that will hold an ```array```. Store your grocery item variables into this array like so.

```JavaScript
var items = [apple, grape, banana ...etc.];
```

#### Add event listeners to your cash and coins that will increment the changeMaker to the appropriate amount.

14. Add event listeners to all of your bills and coins. Every time they are clicked, do the following:
* Play the ```moneySound```.
* Update the ```changeMaker``` variable to the correct sum of choices that the user pressed. If they pressed the $20, add 20 to ```changeMaker```. If they pressed the .25 cents, add .25 to ```changeMaker```, so on and so forth.
* Change the ```innerHTML``` of ```changeText``` to display the current value of ```changeMaker```.

#### Create functions to update our computer and customer dialogue boxes.

15. Create a ```function``` named compSpeech that will take in a parameter "speech".
* In this function, change the innerHTML of compText to equal the parameter speech.

16. Create a ```function``` named custSpeech that will take in a parameter "speech".
* In this function, change the innerHTML of custText to equal the parameter speech.

#### Create a function to generate the necessary items to start a new scene! e.g. Generate number of items purchased and random items, respective dialogue for that purchase...etc.

17. Create a ```function``` named startScene that will take in no parameters. In this function, do the following:
* Create a ```variable``` called "randNum" that will store a random **Integer** from 0 to the number of items in the items array.
* Create a ```variable``` called "item" that will store a random item from the items array. **Hint: Use the randNum variable you just created to help you access a random item from the items array.**
* Create a ```variable``` called "num" that will store a random **Integer** from 1 to 100.
* Create a ```variable``` called "total" that will multiply the values stored in ```num``` by the price of the random item.
* Create a ```variable``` called "randPayout" that will store a random number that is GREATER THAN the total. This is how much the customer will pay.
* Create a ```variable``` called "change" that will calculate how much the correct change is.

---
* Now, paste the following code into the startScene function.

**DISCLAIMER: This code example is not exemplar for efficiency or clarity. It is just to observe how we can return different types of values (objects, functions) in ways that we haven't been familiar with yet!**

```JavaScript
var script = (function() {

  var custDialogue = (function() {
    // Item to buy
    var speech1 = (function(){
      var dialogue;
      if (num != 1) {
        dialogue = "Hi! I want to buy " + num + " " + item.name + "s.";
      } else {
        dialogue = "Hi! I want to buy " + num + " " + item.name + ".";
      }
      return dialogue;
    })();

    // Money paid.
    var speech2 = "Here is $" + randPayout.toFixed(2) + "!";

    var dialogue = {
      dialogue1 : speech1,
      dialogue2 : speech2
    }

    return dialogue;
  })();

  var compDialogue = (function() {
    // Cost
    var speech1 = "That will be $" + total.toFixed(2) + ".";
    // Change
    var speech2 = "Your change will be $" + change.toFixed(2) + ".";

    var dialogue = {
      giveTotal : speech1,
      giveChange : speech2
    }

    return dialogue;
  })();

  var talkingSet = {
    cust: custDialogue,
    comp: compDialogue
  }

  return talkingSet;
})();
```
This code looks different! What is it doing?

Test out and console.log different parts to answer the following. Write or type them out somewhere and discuss the answers with your instructor afterwards:
1. What is the value of our variable script?
2. What will script.cust return?
3. What will script.cust.dialogue1 return?
4. How do we access the string where the computer says what our change will be?

---

* Add an Event Listener to the ```restart``` button that listens for a click. When a click is detected, do the following:
* Set ```changeMaker``` equal to 0.
* Set the innerHTML of ```changeText``` to show the value of ```changeMaker```.

---

* Add an Event Listener to the ```give``` button that listens for a click. When a click is detected do the following:
* Create an ```if statement``` that will check if the change the user generated is equal to the correct change value. If so:
  * Play the ```chachingSound```.
  * Make the computer dialogue box show how much change we are giving the customer. Use the ```compSpeech``` function and give it the correct string as the parameter by accessing it from the ```script``` variable.
  * Make the customer dialogue box display "Thanks!".
* ELSE
  * console.log the value of changeMaker and the correct change to see how much you were off by.

---

* Create a ```setTimeout``` using the reference to custSpeech and compSpeech functions. Access the speech needed from the script variable. We want the dialogue to happen in this order:
1. Customer tells us what they want to buy 2000 ms after the window loads.

2. 2000 ms afterwards, the computer dialogue box displays how much that will cost.

3. 2000 ms afterwards, the customer tells us how much they will pay.

An example for the first setTimeout is as follows:
```JavaScript
setTimeout(custSpeech.bind(null, script.cust.dialogue1), 2000);
// Use .bind to give the custSpeech function reference the parameter of what they want to buy (accessed using script.cust.dialogue1). .bind is a more complex topic that we will discuss later. However, feel free to do research on what this is!

```

Woohoo! That was a lot! Nesting functions and returning objects and functions is another way to limit who has access to your variables. Not just anyone should be able to manipulate important variables!

## Stretch Goals

1. Over time, change the source of the customer image to display the smiley, sad, then angry face while the change is being calculated by the user. Customers don't like waiting! 
