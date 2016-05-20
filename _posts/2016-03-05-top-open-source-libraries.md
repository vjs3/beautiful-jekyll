---
layout: post
title: Top 5 open source android libraries
tags: [android, blog, opensource]
---

Finally I am writing this article after getting some time after finishing my university exams.
This will be a small article to describe about some of the open source android libraries which I found most useful to me specifically during contributing to open source projects.

Here I only cover what are they and quick tips on when to use them.Following is the list of top 5 must know open source android
libraries in my opinion:

- **[Retrofit](http://square.github.io/retrofit/)** - It is developed by square.It is used to retrieve and upload JSON or any other strucured data to any REST based webservice. Retrofit uses the OkHttp library for HTTP requests.

- **[GSON](https://github.com/google/gson)** - It is a very popular networking library developed by Google only. GSON is used to convert Java objects to JSON objects. It can also be used to convert a JSON string to an equivalent Java object.
Gson provides several built in serializers and deserializers. A serializer allows to convert a Json string to corresponding Java type and a deserializers allows to convert from Java to a JSON representation. 

- **[Butter Knife](http://jakewharton.github.io/butterknife/)** - This library is again developed by android chief of square Jake Wharton (I am a big fan of his work ;)).This is useful for every large android projects involving large number of views in it.
This library reduces boilerplate code to calls views again and again and increase code readability as well.

- **[Picasso](http://square.github.io/picasso/)** - This is very popular image caching library in android developed by square only. It simplifies the process of displaying images from external locations with few lines of codes.

- **[Sugar ORM](http://satyan.github.io/sugar/)** - This is one of the most useful library when it comes to work with SQLite database in android.
This is Object Relational Mapping library helps  to avoid writing long queries in your java code instead it created database automatically out of the objects which we have created for application.
So try using it whenever you are going to to develop your application with usage of SQLite say saving data in offline mode itself.

I hope you enjoyed this article, will try to write another article on other important android libraries/concepts.
