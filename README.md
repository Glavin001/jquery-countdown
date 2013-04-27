jQuery Countdown
=====

##Usage
1. Create an element

```html
<span>example countdown element</span>
```

2. Add the required countdown class, **jq-countdown**

```html
<span class="jq-countdown">example countdown element</span>
```
3. Add the applicable attributes for the countdown's end date

```html
<span class="jq-countdown" data-countdown-alt="Now finished this example Countdown"
data-countdown-year="1993" data-countdown-month="12"  data-countdown-day="01" 
data-countdown-hour="10" data-countdown-minute="0" data-countdown-second="0"
data-countdown-callback="console.log('Countdown complete!');">
example countdown element
</span>
```
A list of available countdown date attributes:
  - ```data-countdown-year``` : any year
  - ```data-countdown-month```  : any month in numerical form, 1=January, 12=December
  - ```data-countdown-day``` : any day applicable in the given month 
  - ```data-countdown-hour``` : any hour in 24-hour format (from 0 to 24 which is 12:00 midnight to 12:00 noon respectively)
  - ```data-countdown-minute``` : any minute from 0 to 60
  - ```data-countdown-second``` : any second in a minute from 0 to 60
  - ```data-countdown-alt``` : Alternative text to be displayed; default & after countdown has finished
  - ```data-countdown-callback``` : JavaScript callback function that will be triggered when the countdown hits 0!


**Done!**
