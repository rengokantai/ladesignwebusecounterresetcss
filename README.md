### ladesignwebusecounterresetcss

####
#####Counting headings with CSS
```
h3{
  counter-increment:ke;    //default start from 1. 
  // counter-increment:ke 2;  (start from 2,interval is 2(same as))
}
h3::befoew{
  content:counter(ke) '. '; //or content: 'Number ' counter(ke) ;
}
```
this will render 1. 2. ...

#####Positioning the heading numbers
[before and after](http://www.bennadel.com/blog/2445-using-css-pseudo-elements-before-and-after.htm)
#####
```
counter-reset: childcounter  //use in parent level element
```
