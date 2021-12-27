# Andrej Nagibauer

### Contact information:

* Location: Omsk, Russia
* Phone: +7-983-563-07-51
* Email: nagandrej@gmail.com
* GitHub: [nagibauer](https://github.com/nagibauer)
* Telegram: nag_an
* Discord-Server RS_School: Andrej_(@nagibauer)

### About me:

I'm 40 years old. I worked as a teacher of Philosophy, Theology and Logic for 8 years. But now I really want to change profession and learn programming to become IT-specialist.

### Skills:

* HTML
* CSS
* Git (basics)
* VS Code (basics)
* Ruby (just started to learn)

### Code example:

```
Ruby:

x = rand(0..100)
puts "\nЯ загадал число от 1 до 100. Угадай, какое?"
puts "У тебя есть 10 попыток"

times = 10

1.upto(times) do |pp|

	print "\nПопытка #{pp}: "
	answ = gets.strip.to_i

	if answ < x
		puts "Нет, больше!\n"
	elsif answ > x
		puts "Нет, меньше!\n"
	elsif answ == x 
		puts "Браво!"
		exit
	end
	if pp == times && answ != x
		puts "Так и не угадал"
		puts "Правильный ответ: #{x}"
	end

	print "Осталось попыток #{times - pp}\n"
end
```

### Courses:

* [HTML](https://ru.code-basics.com/languages/html)
* [Жизнь программиста](https://ru.hexlet.io/courses/prog-life)

### Languages:

* English - Intermediate / Upper-intermediate
* German - B1
