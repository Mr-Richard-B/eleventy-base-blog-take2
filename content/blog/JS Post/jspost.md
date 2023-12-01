---
title: Introduction to Javascript.
description: Some of the first javascript programs I have written.
date: 2023-12-01
tags: second tag
---
<p>This week I have been learning how to buid javascript programs. The session was built around 3 tasks:</p>
<ol>
<li>A percentage calculator</li>
<li>A function that produces a drinks order based on a switch statement</li>
<li>A calculator that utilises a switch function to change between messages based on the opertor used</li>
</ol>

<p>See my code below!</p>
<h3>Task 1 - Percentage Calculator</h3>
<pre>
<code>
"function percentageCalculator(num, percentage){
            return (num * percentage) / 100;
     }
    console.log("The answer is", percentageCalculator(200, 35), "%");"
</code>
</pre>
<br>
<h3>Task 2 - Drinks Order</h3>
<pre>
<code>
function drinkOrder(size, drink) {
           switch (drink) {
              case "cola":
<                   console.log(`You have ordered a ${size} cola.`);
                    break
                case "lemon":
                    console.log(`You have ordered a ${size} lemon.`);
                    break
                case "orange":
                    console.log(`You have ordered a ${size} orange.`);
                    break
                default:
                    console.log(`Sorry, we dont have any ${drink}.`);
            }
        }

        drinkOrder("small", "lemon");
</code>
</pre>

<h3>Task 3 - Calculator</h3>
<pre>
<code>
function calculator(number1, number2, operator) {
        switch (operator) {
            case '+':
                console.log(`${number1} + ${number2} = ${number1 + number2}`);
                break
            case '-':
                console.log(`${number1} - ${number2} = ${number1 - number2}`);
                break
            case '*':
                console.log(`${number1} * ${number2} = ${number1 * number2}`);
                break
            case '/':
                console.log(`${number1} / ${number2} = ${number1 / number2}`);
                break
            default:
                console.log(number1 + number2);
        }
    }
    
    calculator(2, 3,'+')
</pre>
</code>

<p>Thanks for taking a look at my blog!</p>
