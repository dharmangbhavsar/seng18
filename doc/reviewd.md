[home](http://tiny.cc/seng18) |
[copyright](https://github.com/txt/seng18/blob/master/LICENSE.md) &copy;2018, tim&commat;menzies.us
<br>
[<img width=900 src="https://raw.githubusercontent.com/txt/seng18/master/img/banner.png">](http://tiny.cc/seng18)<br>
[syllabus](https://github.com/txt/seng18/blob/master/doc/syllabus.md) |
[src](https://github.com/txt/seng18/tree/master/src) |
[submit](http://tiny.cc/seng18give) |
[chat](https://seng18.slack.com/)


______



# Review Ques 4

1. What one thing we should be expect in:
  - a poorly architectured system?
  - a well architectured  system?
2. Package switching network (PSN):
  - Define the components of a PSN
  - What other architecture was package switching designed to replace?
  - Why was an advantage of that other architecture?
  - What feature of PSN make it attractive as an alternate architeture?
3. Blackboard architecutures:
   - Define the components of a blackboard architecture;
   - For which projects are  blackboard architectures are ideal?  
4. Pipe and Fiter:
   - Describe the components of a pipe and filter architecture.
   -  Give an example of a commonly used system that makes extensive use
         of pipe and filter
   - Explain one advantage of pipe and filter
   - Explain one dsadvantage of pipe and filter
5. CRUD:
    - What is the CRUD pattern?
    - Give two example where CRUD pattern is used.  
6. In Windows
    machine if you open one folder in two different views, rename folder in
    one view automatically renames the other.
    - What type of architecture is this?  
    - Describe different components of this architecture with respect to the above example.
7. Layered architectures:
    - What is "LAMP" and why is it an example of a layered architecture>
    - Explain one advantage of a layered architecture.
    - Explain one dsadvantage of pipe and filter
    - What is "MEAN" and why is it sometimes called a "leaky layered" architecture?
    - Why is MEAN replacing LAMP in certain fast-paced organizations?
8. Architectures and Programming
       
       
Consider the following functionality in Javascript, which gets the mouse cursor position upon the cursor move:



```    
       $(document).bind('mousemove', function(event) {
       position = {'x' : event.pageX, 'y': event.pageY};
       });
```

Now, here is the similar functionality in ELM:

```
       import Mouse
       main = lift asText Mouse.position
```

-  How are the different functions retrieving the mouse positions?
-  What architecture the lift construct in the ELM program is utilizing for this functionality? Explain.
