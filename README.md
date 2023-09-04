# DigitalWatch

it is an a Digital Watch .
Functinality use in this :-

 We get all the hr ,min , sec and am tags in the js.

 *After that making a continus call function with setting time out of 1000 ms it will call continously.
  *Then we assign a Date funtion call to get and hour min and sec.
  *assign it to varible;
  * To get is the time is am or pn we make condition that if hour is greeter than
    12 ait means am = to pm
  * Then we try to concate the zero for by using ternary operator .
  * That if hour is less than 10 concate 0 to hour else direct get hour.
  * rest same for all min and sec also.
  * Then we take that all elemnt to the inner text of a specifed divs;
  * And lastly make a set timer for update clock  each and every 1000ms.
  * Lastly we call the update clock;
