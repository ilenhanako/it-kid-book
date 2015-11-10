# Potato Chip Factory

Do you like potato chip?
_Yes_

Potato chip are made in factory.
In this potato chip factory, there are list of tasks to do

1. clean potato
2. chop potato
3. fry potato
4. package potato

Similar to a potato factory, an application (call it a __program___) are sequence of tasks.
So if you want to make an application for potato chip factory, here is how it might look like

~~~
product = potato.clean;
product = product.chop;
product = product.fry;
product = product.package;
~~~

In Ruby, we often simplify the above program as 1 line only

~~~
product = potato.clean.chop.fry.package;
~~~