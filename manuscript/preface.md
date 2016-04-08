A year back one of my NGO friends wrote to me asking for recommendation for developing a website. A summary of our email exchange was as follows.

Dear Vijay,
 
http://<NGO URL> needs to build a good portal. To use various data analytics, I prefer Python (Django) rather than popular php at server side.
Drupal and Joomla both use PHP, which is more cumbersome though very popular. I have used Joomla, not Drupal. People at the NGO would be happy even with a simple static website, but will later realise its impotency. Changes later would be messy.
 
Can you suggest some company who would develop this? NGO may bear the cost.
 
Regards,
PG

At that time I was the web admin for two websites which I had built from scratch using Drupal and another two websites which were built in an ancient era using CGI.pm A few months later as I started migrating one of my ancient sites I was faced with the same problem, I wanted to use the website as a frontend for a few webapps that I am developing, but I also want to have the features provided by a normal CMS like authentication, roles, blogging, static pages, forms and so on. So what do I do, do  I build my app as a  plugin for drupal or do I bolt on the CMS features to my app?

This book is a record of my attempt to build a website using the second strategy where my app is the center of the website and the other features are bolted on to it.
