## Github'da 1 commit geri gitmek için:

- Eğer son 2 commit'i silmek istersek ~'dan sonra 2 yazabiliriz.

> **git reset --hard HEAD~1**

- Bu kod ile local'de yaptığımız değişikliği aynı zamanda github repomuza force ederek güncelliyoruz.

> **git push origin +master**

____

## Çalışma Metodu

so a learning technique that ı like to share with people is as you're  going through a course, instead of taking notes,  write a study guide for yourself, so that you can quiz yourself later. <br>
And so this is an example of that, this recap, so some things is like,  
- what is an object, right?
- What is the difference between dot and bracket notation?
I'm not gonna go over them cuz we've been going through them.

And then you can find patterns in what is working for you, what teaching styles work for you.
What frequency or repetiton do you need to learn something new?

I would just look for flash card apps if you wanna invest in  the technological piece, but usually I'm kind of a pen and paper person.

____

## JavaScript

- Primitive values get pass by value. 
- While non-primitive values get pass by reference.

So when you are store a non-primitive value somewhere or you pass it to a function, for example, It's  passed by reference. Which means  that you're passing like a pointer to it. So you see how this arrow is pointing to this value? You're kind of passing the pointer around to it. And so, if you have multiple things pointing, it's not making a copy. So if you're sharing one instance of the object and so if you update that object,  and you're pointing the same object over here, that will also be updating. And so that can affect your code in unusual ways.

But if you're passing around primitive values,  you don't have to worry about that. It makes a copy every time. And we're all happy.

> So an array is a special kind of object.  And they have really  the most special thing about an array is the .length property,  which a property that is computed as you add numerical indices,  and numerical indices are different than properties on an array.  Because an array captures that and will increment the length. <br>
So the cool thing about having numerical indices is that they're ordered. And when things are ordered you can reverse them. With an object we don't really have any such order. So for things like sorting and the order and what else? 

- So we can't push things to an object. | "push()" methods. 
-  We can only push things to an array. 

_____