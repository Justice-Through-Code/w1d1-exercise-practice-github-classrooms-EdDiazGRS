# Hello, World

## W1D1 - Exercise - Practice Github Classrooms

Welcome to Tech Pathways at Justice Through Code! W1D1 - Exercise - Practice Github Classrooms is meant to familiarize you with how to use these GitHub repos to turn in your coding challenges.

---

### Estimated Time to Complete

10 minutes

---

### Learning Objectives
Understand how to complete and turn in JTC coding challenges

---


### Assignment Overview

Clone this repo to your computer, then follow the steps as out-lined in the pre-lesson video series for today's Technical Curriculum Overview Pre-Lesson to complete and turn in the assignment.

---


### How to use Challenge Repos

Let's walk through to use this type of repository?

- You will download it onto your computer. The process is the same as cloning any repo (re-watch to pre-lesson video on how to do so, or google it if you aren't sure!). 
- Once you have successfully cloned the repo onto your computer, make sure to `cd` into the cloned folder in your Command Line so you have immediate access to all the files.

- There are multiple files inside the cloned folder, but you'll only be working with one.
- Read the instructions inside of `hello.py`
- Let's briefly take a look at what the function of the other files are.

---

<img width="152" alt="gitignore" src="https://user-images.githubusercontent.com/7146649/187483324-ea53270c-be38-4306-9161-8595d6e9c436.png">

Most GitHub repos will (and should) have a `.gitignore` file. This tells your local computer what files to _ignore_ when tracking files in `git`. For instance, Mac computers create a hidden `.DS_Store` file in every folder on your computer. We can use the `.gitignore` file to make sure that those files don't end up in the GitHub repo.

_(EXTRAS: Notice how both `.gitignore` and `.DS_Store` start with a `.`? The dot tells us that these are 'hidden files', files that most users will want to ignore, so the computer hides it from us. Google how to reveal hidden files on your computer and take a look!)_

---

<img width="158" alt="README.md" src="https://user-images.githubusercontent.com/7146649/187484169-b84be13d-ac4f-4851-b7f0-e494a6b9173f.png">

Good GitHub repos will also have a `README.md` file, to describe what's inside the repo. You're reading this repo's `README.md` file right now! The `.md` file extension tells us that README files are written in a language called `markdown`. Take a look at the file to see the underlying characters that the browser turns into HTML when dispalying it. 

---

<img width="143" alt="hello_test.py" src="https://user-images.githubusercontent.com/7146649/187484683-1c63c05c-bf15-4686-b54d-4b4d196a7dca.png">

Good code has tests! `hello_test.py` enables you to test your code to see if it's working properly. This file will also run automatically when you turn in your homework. This means you'll be able to see how you did and make changes without waiting for us to grade it by hand. Python comes with a built in way to write tests called [unittest](https://docs.python.org/3/library/unittest.html). 

**DO NOT EDIT THIS FILE**. 

To run the tests (after you've completed the assignment):

1. Go into your **terminal**
2. Make sure you are `cd`'d into your challenge folder (you can also run the command `ls`-- if you see your `hello_test.py` file, you're in the right place)
3. Run the command `python3 -m unittest hello_test` <-- NOTE: `python3` may not be the right command on your computer. Whatever command runs Python 3 for you (`python3`, `py`, `python`), use that one
and check it out! The tests will either pass (OK) or fail, in which case you should see an error that will help explain what went wrong. 

---

Finally:

<img width="122" alt="hello.py" src="https://user-images.githubusercontent.com/7146649/187496842-63c99047-00ad-4335-837e-4b1e2c8ee16e.png">

This is where _your_ code goes. Just like elsewhere, there are elements here that we won't go into _yet_, but you don't need to understand them to do the challenge. The provided code looks like this:

```python3
def hello_world():
    # print out the string 'Hello World!'
    
```

All of the code you write should be _indented_ into the `hello_world` function. What that means is that all of your code should start at the same indentation level as the comments above:

```python3
def hello_world():
    print('Hello World!')
    
```

Try it out and see if you can get the tests to pass, then push your changes and you're all set!

---

## Summary

0. Accept the challenge via the GitHub Classroom link (if you're already here, you've done this part!)
1. Clone the repo to your computer
2. Follow the instructions in `hello.py` (the only `.py` file that is not a `_test.py` file) so that it prints out `'Hello World!'`.
  - Make sure to run your code often as you write it to see what changes you're making
  - 'Run' your code by typing your computer's version of `python3 hello.py` into your terminal and hitting enter
3. Run your computer's version of `python3 -m unittest hello_test` to see if your code works as expected
4. `git add`, `git commit`, `git push` your code, and look for the little green check mark on your repo that tells you your tests passed

And you're good to go!

