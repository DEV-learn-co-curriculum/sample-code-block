## Happy Test

```ruby
def greeting
	puts "Hi, Ruby programmer!"
end
```

```bash
// ♥ irb
2.2.1 :001 > def greeting
2.2.1 :002?>   puts "Hi, Ruby programmer!"
2.2.1 :003?>   end
 => :greeting 
```

You've now defined the method. Notice that it did not execute. Type the following into IRB to execute your method: `greeting`.

```bash
2.2.1 :004 > greeting
```

You should see:

```bash
Hi, Ruby programmer!
 => nil 
```

As amazing as this method is, it's still pretty literal. It hard-codes, or directly specifies, name of the person we are greeting as `"Ruby programmer"`. If we wanted to build a method that can greet *anyone*, even Python programmers, we'd have to re-implement the majority of the original logic from `greeting`:

```ruby
def greeting_python
  puts "Hello, Python programmer!"
end
```
<a href='https://learn.co/lessons/sample-code-block' data-visibility='hidden'>View this lesson on Learn.co</a>
