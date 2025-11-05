# Code Citation Tips #

When writing code, you want to use similar citation ideas as in academic writing instances. Whether you are copying or adapting code from a small snippet or using an entire module or function, you must cite your source.

Your citation should include:

* URL of your source                                                      
* Date you retrieved your source
* Title of the program or application you are using     
* Type (e.g., source code, application, full program)
* Author name(s) if available
* Code version if available
* License (if the code you copied has a "copyleft" license)

Here are two methods for citing code from a snippet used from <b>http://www.oregonstate.edu/mysource</b> retrieved on December 2, 2020:

1. You can cite your code in your written report or your `README.md` file. Here is an example on how to cite code in a written document:
    
    <b>Sample Format:</b> <author name(s)> (&lt;date retrieved&gt;) <title of application/source code/program> (&lt;Version of code&gt;) [&lt;type of      code&gt;]. Source Web address or publisher information.<br>
    
    <b>Example:</b> Safonte, D. (December 2, 2020) Citing Source Code (Version 1.0) [Source Code]. <b>http://www.oregonstate.edu/mysource</b></br>

2. The second method cite your source right within your code using comments.

    <b>Example:</b> a good citation can be observed on lines 1-9 below:
    
```
1       # Citation for the following function:
2		# Author: D. Safonte
3		# Title: Citing Source Code
4		# Version: 1.0
5		# Type: Source Code
6       # Date retrieved: December 2, 2020
7       # Copied from /OR/ Adapted from /OR/ Based on:
8       # Source URL: http://www.oregonstate.edu/mysource
9		# Note: Adapted from original to fit our use case (e.g., added error handling)
10
```
