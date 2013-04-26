jQuery Countdown
=====

##Usage
1. Create an element

```html
<span>example element</span>
```
Easy enough.
2. Add the Countdown class, **jq-countdown**

```html
<span class="jq-countdown">example element</span>
```
3. Add the attributes for the countdown date

```html
<span class="jq-countdown" 
data-date-year="1993" data-date-month="12"  data-date-day="01" 
data-date-hour="10" data-date-minute="0" data-date-second="0">
example element
</span>
```
A list of available countdown date attributes:
  - ```data-date-year``` : any year
  - ```data-date-month```  : any month in numerical form, 1=January, 12=December
  - ```data-date-day``` : any day applicable in the given month 
  - ```data-date-hour``` : any hour in 24-hour format (from 0 to 24 which is 12:00 midnight to 12:00 noon respectively)
  - ```data-date-minute``` : any minute from 0 to 60
  - ```data-date-second``` : any second in a minute from 0 to 60


**Done!**
