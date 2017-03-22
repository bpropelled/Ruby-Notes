# Ruby-Notes

## Just a way to keep track of some notes and snippets

### One liner code to open and write to a file
```ruby
File.open('test.txt', 'w') {|f| f.write(doc) }
puts "yeah, it is done"

```

## Assert Definition
assert will terminate the program (usually with a message quoting the assert statement) if its argument turns out to be false. it's commonly used during debugging to make the program fail more obviously if an unexpected condition occurs.

for example:

```ruby
assert(length >= 0);  // die if length is negative.
```

## Objects
Get the mothods of any object by using ".methods"

```ruby 
self.methods

#or

x = []

x.methods
```