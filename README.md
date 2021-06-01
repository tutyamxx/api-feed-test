# API Feed Test
Test for backend developer candidates. When you start the test, create a branch off of master that you will name after you and when you are done create a pull reqeust. Good luck!

# The test
Using the Punk API, create a program that generates a list of beers, grouped by their yeast.
This program should be able to recieve two inputs via the command line, a min and max ABV. 
The program should use these values to return only the beers with a ABV greater than the min amount but less than max amount. 

Each beer in the feed should include:
- name
- image url
- description
- tagline
- a single, comma seperated string of the names of it's hops
- a single, comma seperated string of the names of it's malts

This output of the program should be printed to the terminal.

# The tools
You must use the Punk API (https://punkapi.com/documentation/v2) to get the data. The API has a request limit of 3600 per hour, so you may want to save the json response to work with during the test.


# What we are looking for
We're looking to see how you approach a problem more than anything.

You are welcome to add any documentation or tests to your code that you like.

We look forward to seeing your solution. 
