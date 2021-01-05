2.7.2 :001 > docking_station = DockingStation
Traceback (most recent call last):
4: from /Users/katy/.rvm/rubies/ruby-2.7.0/bin/irb:23:in `<main>' 3: from /Users/katy/.rvm/rubies/ruby-2.7.0/bin/irb:23:in `load'
2: from /Users/katy/.rvm/rubies/ruby-2.7.0/lib/ruby/gems/2.7.0/gems/irb-1.2.1/exe/irb:11:in `<top (required)>'
1: from (irb):1
NameError (uninitialized constant DockingStation)

Type of error: uninitilized constant
FIle path: /Users/katy/.rvm/rubies/ruby-2.7.0/bin/irb:23:in `<main>'
Line number: 23

What the error means: using capital letters in Ruby makes it a constant, which cannot be changed (and not used on the right side of a Ruby equation).

Can be fixed by assigning a value to docking_station, such as an integer or an array or a string, but it has to be a defined method.
