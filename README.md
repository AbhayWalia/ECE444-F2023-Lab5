# ECE444-F2023-Lab5

### This repo was created with the help of: https://github.com/mjhea0/flaskr-tdd#first-test


## Unit tests for group project:

### https://github.com/ECE444-2023Fall/project-1-web-application-design-novatech/blob/5f6005e6001c22f6e514221d859ef10bbb5db964/Tests/app_tests.py#L153C1-L173C26
### Tests written: test_check_rsvp_limit() and test_delete_all_events()

## What are the pros and cons of TDD?

## Pros:

Some pros with TDD are since we are essentially writing the test cases before actually developing a new feature, we already know exactly what functionality we need to have and what the expected output should be.
This makes it very easy to identify issues with your code since you already know based on the test that has been written what output you should receive. 
This also allows us faster debugging since, if you are developing to pass test cases you are essentially developing smaller chunks of a program each time and testing them, which would allow you to pinpoint an error easily
if it comes up.
Also, for developing in a team setting, each team member will also know what functionality other people's code will have before it's even implemented, by simply looking at the test cases. this is especially helpful if you
are developing a function that requires output from someone elses function, knowing exactly what they will output will be beneficial. 

## Cons:

Based on what I have observed I can say some cons with TDD are that it's time-consuming, and can't always be trusted.
Firstly, even though this was the first time I used TDD, I can already see how time-consuming it is. Before you even start coding you have to think about exactly what your code should be returning and exactly how to test that.
So you have to sit down and plan test cases accordingly rather than just jumping into development right away. This can be very time-consuming especially if you have deadlines that are approaching.
Next, we can't always rely on the test cases we build as indications of whether the correct functionality is present or not. This is because if we are making test cases, we generally already have an idea of what we will do to pass
them. And even if we are passing these cases, there could be a bunch of edge cases that weren't thought of while designing the test cases which could be completely overlooked since you would think the code is functioning as attended   by seeing your own test cases passing.
