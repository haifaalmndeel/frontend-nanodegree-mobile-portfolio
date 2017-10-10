
## Website Performance Optimization portfolio project

#####  __First__ thing to do is that I have to make the score above `90` 
1. download all the __image__ to have it locally .
2. Compress all the images.
2. make all scrept tag __async__ and move it to end of the bage .
3. copy and delete `print.css` file and paste it in `style.css` to make it one file.
4. make `style.css` _media=all_ to unblock it .

##### __scond__ 
*  fix main.js to make  frame-rate at `60fps` when scrolling
* fix the time to resize pizzas is less than `5ms`

 1. delet `determineDx()` and change `sizeSwitcher()` to make one function  `changePizzaSizes()` .
 2. in `changePizzaSizes()` Changes the slider value to a percent width .
 3. any __variable__ defined inside loops that can be define outside I define it outside.
 4. change all __querySelector__ in `loops` to __getElementsByName__.
 the loop at the end that display the pizzas, the loop doesnt have to loop 200 times and have all these pizzas,I optimize it so it display   pizzas enough only for the screen resolution so I change the loop to `64` .
