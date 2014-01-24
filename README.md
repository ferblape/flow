Flow
=====

Time management under your terms.

Why Flow
--------

I found that the [Pomodoro technique](http://en.wikipedia.org/wiki/Pomodoro_Technique) breaks my flow when I'm successfully immerse in a certain task.

[Some people suggest](http://productivity.stackexchange.com/a/813) changing the amount of intervals and try out things like 35/5, 50/10 or 45/10, But this hasn't proven to be effective for me either.

What is Flow, then?
-------------------

Flow is a minimalistic time-management tool that helps you maintaining a good balance among activity and rest. While you are working, you are earning time to rest later. If you start feeling tired, you can take a break and the time counts down. Flow gives you feedback on whether you are working too much, or resting more than enough.

What are the trade-offs
-----------------------

Flow is excellent if you want to be highly productive and in a flow state, while keep a good balance between activity and rest. However, this same flexibility makes Flow not so good as a planning technique, something Pomodoro is good at.

If you are a programmer or a designer, and like me, you perform better when deeply immerse in what you are doing, then Flow is for you!

Flow in action
--------------

Here you are:

http://flownow.herokuapp.com/

You can customize the duration of the work phase and the rest factor. The following sets a flow instance with a limit of 2 minutes working and a rest factor of 50%, which means that you will earn 30 seconds each minute to rest:

http://flownow.herokuapp.com/?limit=120&factor=0.5

The default one is thought for cycles up to one hour of work and a rest factor of 30%, which is the same as if we customized flow this way:

http://flownow.herokuapp.com/?limit=3600&factor=0.3



Want to contribute?
-------------------

Any idea or feedback to make Flow better is very welcome.

If you want to play around and customize it, fork this:

    $ git clone git://github.com/miguelff/flow.git

Make your changes, and if you are proud of them, open a pull-request.

Credits
-------

Copyright (c) 2014 Miguel Fernández and Marcelino Llano and Buti Romero. Released under the MIT license.
