


For better or worse, I’ve been using MATLAB for quite a long time. Most of the codes and libraries in my research area are published in MATLAB, and naturally so are mine. Lately, I’ve started using python much more frequently, and I was pleasantly surprised by many features that I truly miss in MATLAB. I am not an expert in either programming language, so this is just my personal opinion, you can let me know what you think in the comments below.

### Syntax:
One of the first things I liked about  MATLAB was that it was a high-level programming language with a syntax that was really easy to learn. Yes, it had its quirks (e.g. using parentheses for both function calls and accessing matrix values), but these quirks aside, it's syntax was really straight forward. 

```matlab
x = foo(i); % is this a function or a matrix?
```

As it turns out, python is even easier. Python's syntax forces you to write code that is easily readable and maintainable and also helps you adopt better programming practices. There are many examples of this, but I'll just mention a few: 

 >  Python's syntax forces you to write code that is easily readable and maintainable. 

1. Scopes [is this the correct word?]: Instead of using semi-colons like MATLAB, Python uses indentation to mark [...]. I really love this because it forces you to write clean readable code. Not only does indentation helps make your code easier to read, it also forces you to use shorter lines, and spread out operations into multiple lines. Thus breaking down your long complex lines of code into shorter easily-digestable chunks. 

2. namespaces: 
In MATLAB, every function you write or download is defined in the global namespace. This caused me many unneccesary headaches. If you have a large MATLAB directory, it's very likely that some of the functions you download (or even write, if you're not careful) will have the same name of another function in your directory. When you call that function, you don't know exactly which function is being called. You can imagine how this can cause a lot of problems. With python however, this problem is non-existant. I absolutely love how python uses namespaces. You only load whatever python libraries you need (e.g. `import skimage as sk`) or even just the specific module you want (e.g. `from skimage import filters`). This is also one of the ways Python forces you write readbale code. A quick glance at the first few lines of any Python code will let you know which Python libraries are being used, and if you have to install them before running the code. With MATLAB, unless the code documentation specifies which libraries you need to run the code, you will have to find out yourself. 

3. docstrings:



4. List Comprehensions:
This is one of my favourites. I


5. Function inputs and default function parameters: (find a better example)
If you had a MATLAB function `sendEmail(to, subject, body)`, you will have to call that function with the inputs `to`,`subject`, and `body` exactly in the order they are defined in the funciton definition. With Python, you can do that of course, or you can use any arbitrary order as long as you specify the input variable. In Python it would work like this: 
``` python
sendEmail(body = 'python is awesome.', subject = 'What i think of python', to = )
``` 
Also, you can easily define the default value for any input this way: 
``` python 
def fun(a, b = 2.0, c = 1.0):
	print 'a**b / c'
``` 


x. Coding Style: 

PEP8 vs. what for matlab? 


### Object orientation: 
(while I don't use it often, ...)



### Package management 
pip and conda vs.  ?



### General vs. Customized programming language:
While MATLAB was , Python is a general programming langauge from the get go. You can use Python to build websites(Django link), solve complex scientific problems (scipy), analyse data (pandas), other examples .. . While Python code might not execute as fast as other programming languages such as C/C++ or Julia (link), it is still widely used and increasingly adopted in many scientific communities. 


### Open source libraries and strong community:

Obviously MATLAB is a commercial software. A single MATLAB license costs about: $  xxxxx. Python does everything MATLAB does and more. 

> A single MATLAB license costs about $ ...... 

- you can download and use python with all it power for free. 
- you can read all the built in functions
- you have a lot of flexibility with what you want to do with the language.. 
- many great open source projects, and thousands of people 
- the python standard library is huge. From encrypting data to ..., you name it. (see dash documentation.. lots of great libraries) 

> Python's standard library is huge.


### Finally.. 

After all the points I've mentioned above, it's no wonder why I would prefer Python over MATLAB. I'm leaving out a lot, but I just wanted to make a point. 
