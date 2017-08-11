Rightpoint response
===================

## What was the problem?
 Write a program in your language of choice that prints the numbers from 1 to 100. But for multiples of three print “right” instead of the number and for the multiples of five print “point”. For numbers which are multiples of both three and five print “rightpoint”.

## What are the user stories?
* As a technical recruiter, I want to see if the applicant submitted a reply to the coding question, so that I can determine if the applicant can program.

# What is this most similar to?
* This is the [fizzbuzz](https://en.wikipedia.org/wiki/Fizz_buzz) problem.

## What was my response?
```js
(function printNumRightPoint(num) {
  num = parseInt(num);
  for (var i = 1; i <= num; i++) {
    var by3 = i % 3 === 0;
    var by5 = i % 5 === 0;
    console.log(by3? by5? "rightpoint" : "right" : by5 ? "point" : i);
  }
})(100);

```


## Who is Lino?
Hi, I'm [Lino](https://www.linkedin.com/in/lino-jimenez-jr-4989b23/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3Ba%2BKxwkThQXW3AlolYFIXhw%3D%3D&licu=urn%3Ali%3Acontrol%3Ad_flagship3_feed-nav.settings_view_profile). I worked in project management, software product management, and am looking to work as a front end developer. I've worked with internal and external clients to bring to life software people love. I'm a life long learner.

How can I help?

August 11, 2017
