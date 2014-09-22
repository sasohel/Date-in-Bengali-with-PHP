Date-in-Bengali-with-PHP
========================

To translate date in Bengali language

Example 1

$my_date1 = new Date_in_bengali('12/16/1971');
echo $my_date1->translated_date;

The above example will output:
১২/১৬/১৯৭১

Example 2

$my_date2 = new Date_in_bengali('16/12/1971');
echo $my_date2->translated_date;

The above example will output:
The date format is invalid. Use like this 12/16/1971
