# Jquery Persian Event Calendar
This is a persian (jalali) event calendar based on jquery
![screen shot of persian calendar](https://github.com/mojtaba-asadollahzade/jquery-persian-event-calendar/blob/master/assets/images/screen_shot.png)

### Installing

Include the **persian-event-calendar.js** and **persian-event-calendar.css** files into your 
page.

After that place below code in your project :

```html
<div class="calendar hidden-print">
          <header>
            <h2 class="month"></h2>
            <a class="btn-prev"><</a>
            <a class="btn-next">></a>
          </header>
          <table class="calendar-table">
            <thead class="event-days">
              <tr>
                  <tr>
                    <td>شنبه</td>
                    <td>یکشنبه</td>
                    <td>دوشنبه</td>
                    <td>سه شنیه</td>
                    <td>چهتر شنبه</td>
                    <td>پنجشنبه</td>
                    <td>جمعه</td>
                </tr>
              </tr>
            </thead>
            <tbody class="event-calendar">
              <tr class="1"></tr>
              <tr class="2"></tr>
              <tr class="3"></tr>
              <tr class="4"></tr>
              <tr class="5"></tr>
              <tr class="6"></tr>
            </tbody>
          </table>
</div>
```

This only helps you to get the calendar itself.
To get the events you have yo first put 

```html
<div class="list"></div>
```
inside the **div.calendar** and after that within it to make events you can put your events like below :
```html
<div class="day-event" date-day="[day]" date-month="[month]" date-year="[year]">
</div>
```
where you replace the [day],[month] and [year] with your desired values.

At the end I've to thank :
* **[Reza Babakhani](https://github.com/babakhani)** - *for Persian Date*.
* **[Ardani Rohman](https://github.com/ardani)** - *for Simple Jquery Calendar*.
