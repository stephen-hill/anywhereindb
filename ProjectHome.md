# Needle in a Haystack #

**Comprehensive Search on MYSQL Database**.

> ## ` select * from anywhereindb where anyfield like %search_text%  ` ##

Sometime we need to find out a small piece of string in big Database. Like where is the configuration is saved, or where is Jon's Date of birth is saved. This code is search all the tables and all the rows and columns in a MYSQL Database. The code is written in PHP. For faster result, we are only searching in the varchar field.
_(if anyone needs to search in other field, he can just comment the varchar selecting part.)_

This code is written to help out the web developers as tool.


### How To ###
**_Install_**
  1. Download the anywhereindb.php
  1. Drop it in your _htdocs_ or _www_ folder, and run it in your browser
  1. Give your Database connection information
  1. It's ready for work, search any string

**_Working_**

  * _Collapse All Result_
> > This will hide all the search result, and show how many results are there in each table
  * _Expand All Result_
> > This will show all the search result.
  * _SQL_
> > This is will show/hide SQL query for the particular tables result.
  * _Result_
> > This is will show/hide the particular tables result.


### Helpful for whom ###
  * searching a data in the database
  * understanding a new system
  * quickly find out a setting string in the database


### History ###
In my office Blueliner Bangladesh, Aktar vai always needed a code to find out a string from any where from his database. in other words, search all the tables and all the rows of DB for that search string. So, Mahbub Vai asked me to write a code to the job.

The code was done long time ago. but i did not shared it with anyone.
Today, I have published the code in google code. It needs a good documentation.

Russel vai, gave the text based UI a nice look.(i asked him not to use any image and stuff)
Initial project was Aktar vai's idea and without help of Mahbub vai, Miraz vai it might not be done.

Thanks goes all of my co-worker in Blueliner Bangladesh for this project.




Enjoy the code. please report bugs.
## Download count of older version was 1883 Download ! ##

---

Thank You.
[Nafis Ahmad](http://www.google.com/profiles/happy56)
&lt;wiki:gadget url="http://anywhereindb.nafisahmad.com/donate.xml" height="200" border="0" /&gt;