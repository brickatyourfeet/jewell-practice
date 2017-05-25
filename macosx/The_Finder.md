### !challenge

* type: short-answer
* id: angular-curriculum-bind-forms-02
* title: Object Shape #2

##### !question
What `ng-model` code would you write in order to create an object of this shape?

```js
{
  person: {
    address: {
      state: {
        name: ""
      }
    }
  }
}
```
##### !end-question


##### !placeholder
ng-model="$ctrl.??"
##### !end-placeholder

##### !answer
/ng-model\s*=\s*(\"|\')\$ctrl\.person\.address\.state\.name(\"|\')/
##### !end-answer

##### !explanation
When Angular sees multiple chained properties, it constructs the appropriate object.
##### !end-explanation
### !end-challenge
