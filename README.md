# DOM
* text node represents white space
* Window object is the parent object of the browser
( )

* `document.getElementsByClassName('slds-file-selector__button slds-button slds-button_neutral')`


* Generally, user `querySelector` and `querySelectorAll` 

* Looping through list items:
```javascript
const items = document.querySelectorAll('.items');

items.forEach((item) => console.log(item));
```

```javascript
const ul = document.querySelector('.items');

ul.remove();
```

* [firselementchild](https://developer.mozilla.org/en-US/docs/Web/API/ParentNode/firstElementChild)

* <b>Use This for changing color or background related to events</b>:
```javascript
const s = document.querySelector('.slds-file-selector__body');
s.style.background = 'red';

s.addEventListener('event', (e) => {
    
    e.preventDefault();
    console.log('click');
})
```

^^ the first is the event the second is the function 

* https://www.freecodecamp.org/forum/t/push-a-new-local-branch-to-a-remote-git-repository-and-track-it-too/13222

https://developer.mozilla.org/en-US/docs/Web/API/Event

https://www.w3.org/TR/CSS2/cascade.html

https://codepen.io/bradtraversy/pen/Bwapow

https://www.youtube.com/watch?v=l1-F5_w4l-0

https://developer.mozilla.org/en-US/docs/Web/API/Node/appendChild

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Methods_Index

https://developer.mozilla.org/en-US/docs/Web/API/ParentNode/firstElementChild

https://developer.mozilla.org/en-US/docs/Web/Events

https://developer.mozilla.org/en-US/docs/Web/API/Event

https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference_force_auth.htm#cli_reference_web_login

