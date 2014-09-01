---
layout: post
title:  "Welcome Back"
date:   2014-09-01
categories: article
---

Hello all!

Following the first week of classes, this is proving to be a very exciting semester full of projects and hackathons. Coming up in a few weeks is [Big Red Hacks][big red] in Cornell, where I'll hopefully be able to make my very first app in Swift.

Being a self-proclaimed iOS programmer, jumping into [Swift][swift] is proving to be a very cool experience. It was long overdue for Apple to have a new programming language, and Swift is really showing some neat new features. One of my personal favorites is the ease of string concatentation. In my experience with iOS, you needed to call a message on the string you would want to concatenate with the string you want to add as a parameter. It was a very long and unncessary process. 

Now, in Swift, they have impleneted a very cool feature such as:

var string1 = "world"
var string2 = "Hello, \(string1)!"

which will actually print "Hello, world!"

Another very interesting addition is making the language more losely typed, such as a language like JavaScript. It still utilizes classes, structs, and enums, but for variables the compiler can actually infer that string1 would be a string. It can do the same thing with Ints, Doubles, etc., as long as you give it a literal when you first create a variable. They've also removed the necessity of semi-colons, which is useful, I suppose. It saves time having to write and check semi-colons all the time at least.

An addition that I personally find a bit confusing is the way a variable is declared. Take for example:

var number: Int

Instead of the classic "int number;", it is now a little more involved. It makes sense, considering the attempt to be more loosely typed, but I guarantee that I'll probably forget to do declare a variable at some point.

By far, the coolest addition to the new language is the introduction of Xcode Playground. Essentially, it shows you the output of what you've made as you type it. I think it's a really cool feature, because you don't have to spend half an hour writing code, which ends up breaking when you run it. You can see the functionality of the methods and statements as you write it, and if something unexpected happens, you can fix it on the fly.

But that's enough of Swift from me today. Hopefully, I'll have a really cool Swift app to show at the end of the semester. Stay tuned, because I'll be going over the cool stuff happening at [Circular Studios][circle] and the [Dash Engine][dash] next week.

Carl, out

[big red]: http://www.bigredhacks.com/
[swift]: https://developer.apple.com/swift/
[circle]: http://circularstudios.com/
[dash]: http://circularstudios.com/dash/