
# My name

Evkurov Anzor

***

Frontend developer

***

## Contact

* email: anzor-_-06@mail.ru
* telegram: @anzor-evk
* phone: 8920-888-88-88 

***

## About myself

I would really like to study programming next year.

I do not want to live in need of everyday things. I would like to help my parents, brothers and sisters.

Strengths I would call craving for knowledge. I can no longer just sit and laze around like I used to. I want to learn and develop.

***

## Skills

* HTML5
* CSS3  
* JavaScript(basic)
* Scss, Sass, Less 
* Gulp
* Git, GitHub
* VS Code
* Figma, Scketch, Avocode, Adobe Photoshop, Adobe XD

***

## Code example:

Calculator

```
var buttonPlus = document.getElementById('plus');
var buttonMinus = document.getElementById('minus');
var buttonMultiplication = document.getElementById('multiplication');
var buttonDivision = document.getElementById('division');

var operationButtons = document.getElementsByClassName('operation-button');

var operationButtons = [buttonPlus, buttonMinus, buttonMultiplication, buttonDivision];

var input1 = document.getElementById('number1');
var input2 = document.getElementById('number2');


function makeOperation(OperationCode) {
    var number1 = Number(input1.value);
    var number2 = Number(input2.value);

    if (OperationCode === '+') {
        var result = number1 + number2;
    } else if (OperationCode === '-') {
        var result = number1 - number2;
    } else if (OperationCode === '*') {
        var result = number1 * number2;
    } else if (OperationCode === '/') {
        var result = number1 / number2;
    } else {
        alert("Операция не выполнена.");
    }
    alert(result);
}

function onOperationCodeButtonClick(eventObject) {

    var clickedElement = eventObject.currentTarget;
    var operation = clickedElement.innerHTML;
    makeOperation(operation);
}

for (var i = 0; i < operationButtons.length; i++) {
    var button = operationButtons[i];
    button.addEventListener('click', onOperationCodeButtonClick);
}
```
***

## Courses: 

no completed courses

## Languages:

* Russian
* English- A1