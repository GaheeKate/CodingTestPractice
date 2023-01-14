
### MySQL
#### 1757. Recyclable and Low Fat Products</br>

##### Thoughts
- my first leet


```
select product_id from Products
where low_fats = 'Y'
and recyclable = 'Y'
```


### JS
#### 1920. Build Array from Permutation

##### Thoughts
- How much time do I have for one question? 
- How other ppl did: use 'map', or 'forEach'
 ```
 var buildArray = function(nums) {
    return nums.map(a=>nums[a]);
};
```

- How I did
```
var buildArray = function(nums) {
    var ans=[]
    for(i=0; i<=(nums.length-1); i++){
    ans.push(nums[nums[i]])
 }
  return ans; 
};


```
