# Code Citation Tips #

When writing code, you want to use similar citation ideas as in academic writing instances. Whether you are copying or adapting code from a small snippet or using an entire module or function, you must cite your source.

Your citation should include:

* URL of your source
* Publisher information (if known)                                                   
* Date you retrieved your source
* Title of the program or application you are using     
* Type (e.g., source code, application, full program)
* Author name(s) if available
* Code version if available
* License (if the code you copied has a "copyleft" license)
  * A <ins>copyleft license</ins> lets you use and change code freely, but if you share your version, you must keep it open so others can use and change it too
 
## Instructions

Here are two methods for citing code from a snippet used from <b>http://www.oregonstate.edu/mysource</b> retrieved on September 4, 2024:

1. You can cite your code in your written report or your `README.md` file. Here is an example on how to cite code in a written document:
    
    <b>Sample format:</b>
    <br><Author name(s)> (&lt;Date retrieved&gt;). <i>Title of application/source code/program</i> (&lt;Version of code&gt;) [&lt;Type of      code&gt;]. <i>Source publisher information</i>, <b>Source web address</b>. Licensed under &lt;license name&gt; (if known/applicable).</br>
    
    <b>Example:</b>
    <br>Safonte, Darreon (September 4, 2024). <i>Citing Source Code</i> (Version 2.1) [Source Code]. <i>Oregon State University – School of Electrical Engineering and Computer Science</i>, <b>http://www.oregonstate.edu/mysource</b>. Licensed under MIT.</br>

2. The second method cite your source right within your code using comments.

    <b>Example:</b> a good citation can be observed on lines 1-11 below:
    
```
1       # Citation for the following function:
2		# Author: Darreon Safonte
3		# Title: Citing Source Code
4		# Version: 2.1
5		# Type: Source Code
6		# License: MIT
7       # Date retrieved: September 4, 2024
8       # Copied from /OR/ Adapted from /OR/ Based on:
9       # Source URL: http://www.oregonstate.edu/mysource
10      # Publisher: Oregon State University – School of Electrical Engineering and Computer Science
11		# Note: Adapted from original to fit our use case (e.g., added error handling)
12
```
