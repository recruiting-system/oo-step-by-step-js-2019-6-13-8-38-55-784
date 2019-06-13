Create class Person with fields name, age and a method named introduce.
Method introduce should return string like this:

>My name is Tom. I am 21 years old.

Then create class Student to inherit class Person. There are fields name, age, klass and a method named introduce in class Student. Method introduce should return string like this:

>My name is Tom. I am 21 years old. I am a Student. I am at Class 2.

Then create class Teacher to inherit class Person. There are fields name, age, klass and a method named introduce in class Teacher. Method introduce should return string like this:

>My name is Tom. I am 21 years old. I am a Teacher. I teach Class 2.

If klass is null, then it will like this:

>My name is Tom. I am 21 years old. I am a Teacher. I teach No Class.

This text from all subclasses of class Person

>My name is Tom. I am 21 years old.

should be returned by calling method introduce from class Person.
