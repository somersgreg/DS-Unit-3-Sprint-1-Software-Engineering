

## Module 4 Project - Software Testing, Documentation, and Licensing

For code to stand the test of time, it is not enough to be well-written - it must be tested and documented. It is also important to understand the basics of software licensing, both in the code you depend on and create.


## Learning Objectives



* Understand approaches toward and the purpose of software testing, and be able to write basic unit tests
* Read and write quality comments, Pydoc, and READMEs
* Recognize major open-source licenses and their significance for personal and professional use

## Before Lecture


Read the official documentation for [pytest](https://docs.pytest.org/en/stable/), a Python package for writing unit tests.

Read the [pandas README.md](https://github.com/pandas-dev/pandas/blob/master/README.md) - it strikes a good balance between ease of skimming for immediate usefulness and reference links for more details.

Check out the [Open Source Initiative](https://opensource.org/licenses), the group that formally approves licenses as being "open source." You'll see some familiar and less-familiar license names, as well as a [useful FAQ](https://opensource.org/faq).


## Live Lecture Task

First we'll write some basic unit tests to demonstrate their functionality. We'll apply these concepts to `lambdata`, but will also discuss them more generally. Come to class with questions and be prepared to discuss documentation and licensing as well!

## Assignment

Spruce up `lambdata`!

- Add at least one basic `pytest` to `lambdata`
- Make sure there are docstrings wherever PEP 8 demands
- Write a high-quality `README.md` that is both skimmable and has appropriate
  examples/details/links for someone who wants to understand your code
- Pick a license for your package, and add it in a `LICENSE` file.

Please submit your `pytest` file (the one with the test) and your `README.md` to Canvas.


## Resources and Stretch Goals

#### Resources:
Add a `ROADMAP.md` file to your repo, with an outline of where you'd like to take your `lambdata` project. It can also include guidelines for what sort of contributions you'd like to have and how somebody can go about getting started building and developing on your code.

Run [pydoc](https://docs.python.org/3.7/library/pydoc.html) on your `lambdata` package to generate documentation based on your docstring comments. Try browsing it locally, and for an extra stretch goal - put it in a `/docs` directory in your repo and enable GitHub Pages to serve it on the web!

Try [unittest](https://docs.python.org/3/library/unittest.html), a Python testing framework included in the standard library. This is a bit less powerful than `pytest`.

Read [the MIT License, Line by Line](https://writing.kemitchell.com/2016/09/21/MIT-License-Line-by-Line.html), and write your own summary of it with a target audience of another person who writes code.

