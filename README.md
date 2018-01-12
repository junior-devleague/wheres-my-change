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
