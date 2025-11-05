# Code Citation Tips

When writing code, you want to use similar citation ideas as in academic writing instances. Whether you are copying or adapting code from a small snippet or using an entire module or function, you must cite your source.

Your citation should include:

* URL of your source
* Publisher information (if available)                                  
* Date you retrieved your source
* Title of the program or application you are using     
* Type (e.g., source code, application, full program)
* Author name(s) if available
* Code version if available
* License (if the code you copied has a "copyleft" license)
  * A <ins>copyleft license</ins> lets you use and change code freely, but if you share your version, you must keep it open so others can use and change it too
 
## Instructions

Here are two methods for citing code from a snippet used from <b>https://www.oregonstate.edu/mysource</b> retrieved on September 4, 2024:

1. You can cite your code in your written report or your `README.md` file. Here is an example on how to cite code in a written document:
    
    <b>Sample Format:</b>
    <br>`<Author(s)>` `(<Date retrieved>).` `"<Title of application/source code/program>"` (Version `<X.X>`), <ins>[`Type of code`]</ins>.</br>
    `'<Publisher>'`, **`<Source URL>`**. Licensed under `<License name>` (if known).</br>
    
    <b>Example:</b>
    <br>`Safonte, Darreon` `(September 4, 2024)`. `"Citing Source Code"` (Version `2.1`), <ins>[`Source code`]</ins>.</br>
    <i>`Oregon State University – School of Computer Science`</i>, <b>`https://www.oregonstate.edu/mysource`</b>. Licensed under `MIT`.</br>

2. The second method cite your source right within your code using comments.

    <b>Example:</b> a good citation can be observed on lines 1-11 below:
    
```
1       # Citation for the following function:
2		# Author: Darreon Safonte
3       # Date retrieved: September 4, 2024
4		# Title: Citing Source Code
5		# Version: 2.1
6		# Type: Source code
7       # Copied from /OR/ Adapted from /OR/ Based on:
8       # Publisher: Oregon State University – School of Computer Science
9       # Source URL: https://www.oregonstate.edu/mysource
10      # License: MIT
11		# Note: Adapted from original to fit our use case (e.g., added error handling)
12
```
