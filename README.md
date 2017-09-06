# \<dropdown-input\>

Dropdown menu with input above for FORM or IRON-FORM

## Install 


```
$ bower i rokity/dropdown-input --save
```
## Api

1. selected : set selected paper-item

2. named : name of the parameter to pass via FORM or IRON-FORM

3. param : name of the propreties to copy on input value (id,value,innerHTML or html, custom properties)

4. label : the label of paper-dropdown-menu

5. value : default value for input text to pass via Form or Iron-Form

## Event

1. change : when user select an item on dropdown
    ```javascript
        document.querySelector('dropdown-input').addEventListener('change', function (e) {
      console.log(e.detail.item); // return item DOM 
  })
    ```


