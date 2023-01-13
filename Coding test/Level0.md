# Coding test 
 
Today I practiced coding test 

- please complete the solution function that returns the year of birth based on 2022.
  - memorize the function 'Date().getFullYear()'
```js
How I did:
function solution(age) {
    var answer = 2022-age+1;
    return answer;
}

How other did;
function solution(age) {
    return new Date().getFullYear() - age + 1;
}
```


- Iced Americano is $5.5 per cup. Complete the solution function to return an array containing the maximum number of cups of Americano he can drink and the remaining money in order when money is given as a parameter.
  - Just return array. 
  - Use '%'    

```js
How I did:
function solution(money) {
    var answer = [];
    var cups = Math.floor(money / 5.5)
    var change = money - (5.5 * cups)
    answer.push(cups, change)
    return answer;
}


How other did;
function solution(money) {
    return [Math.floor(money / 5.5), money % 5.5];
}
```

- You want to write each letter in a width of 2cm, and when you write a letter only horizontally, complete the solution function to return the minimum horizontal length of letterhead needed to write a message.
  - why used spread syntax?
  - shorten the code
```js
How I did:
function solution(message) {
    var answer = 0;
    var msg = message.length
    answer = msg *2
    return answer;
}


How other did;
function solution(message) {
    var answer = [...message].length * 2;
    return answer;
}
```