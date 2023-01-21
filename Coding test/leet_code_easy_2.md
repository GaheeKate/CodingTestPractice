# Coding test 
 
Today I practiced coding test 

- think of time complexity. one for loop O(n)
nested for loops O(n2). It is okay to use if it does not violate the restrictions


### MySQL
#### 1757. Recyclable and Low Fat Products</br>

- How I did
```
select event_day as day, emp_id, sum(out_time-in_time) as total_time 
from Employees
group by event_day,emp_id
```
### JS
#### 2469. Convert the Temperature

##### Thoughts
- Don't use .push too often
- write on return

- How I did

```
var convertTemperature = function(celsius) {
    var Kelvin = celsius + 273.15
    var Fahrenheit = celsius * 1.80 + 32.00
    var r =[]
    r.push(Kelvin,Fahrenheit) 
         return r;
};
```
- How Other did
```
var convertTemperature = function(celsius) {
    return [(celsius + 273.15),(celsius * 1.80 + 32.00)]
};
```

### JS
#### 1108. Defanging an IP Address

- How Other did

```
var defangIPaddr = function(address) {
    return (address.replaceAll(".","[.]"))
};
```
