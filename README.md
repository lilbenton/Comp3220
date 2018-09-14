 # Ruby Project  
This is Ruby Project 1
* PART 1: Short Questions
* PART 2: Coding Problem
* PART 3: Documentation
* PART 4: Thinking Assignment 
### Quick start
**Make sure you have an appropriate IDE that implements Ruby. For example, Ubuntu OS version 18.04
 > Clone/Download the solution then run `main_foo.rb`
 ```bash
 # Download all files from canvas
 # For Mac OSX
 $ ruby main.rb
 ```
# Table of Contents

* [Short Question](#short-answer)
* [Coding Problem](#coding-problem)
* [Documentation](#documentation)
* [Thinking Assignment](#thinking-assignment)
* [License](#license)
* [Author](#author)

 #### Short Question
 
 A series of 8 qeustions involving code and definitions.
 ___
 
 #### Coding Problem
 Solve a coding problem involving a list of movies looked-up by a user. 
 ___
 
 #### Documentation
 Create a "README.md" similar to that of "SAMPLE_README.md."
 ___
 
 #### Thinking Assignment
 Create a solution to finding the fluctuation point in an array that holds millions of entries. 
 ___
 
 ### API

 The showList() method shows the movies within the array. 
 ```
 def showList()
  @searchSuggestionList
 end
 ```
 The updateList() method puts a new movie, entered by the user, at the top of the list. 
 ```
 def updateList(movie_name)	
 searchSuggestionList.unshift(movie_name)
 end
 ```
 The saveListToFile() method saves the updated suggestion list to "data.txt".
 ```
 def saveListToFile()
  File.write("data.txt", searchSuggestionList)
  return 
 end
 ```
 ___
 #### Program Time Complexity

 The program runs with O(N^2) time complexity.
 ___

 #### License
   [Auburn University](/LICENSE)

 ___

 ## Author
   [Amy Benton](/LICENSE)
  


  

