# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
While completieng this assignment, I got more comfortable working with tuples and lists in python. I got better at problem solving and creating a simple match function that took a users input and got an answer out of it.


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
First the user types in a query. Then the match function tries to find a pattern from a predefined source list. if a match is found, it takes the words that are found in it. When a match is found, it returns the words that go with what the user put into the query, if matches is not None, then it calls the corresponding action function that is found is pa_list. When the action function gets called, it returns the values to the user.


3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?
Some real-world applications where this pattern-matching chatbot system is found is in companies chat boxs. Before reaching a representative, companies make users go through a chatbox to see if they can get an answer. This is pretty effective because usually people ask pretty general questions. Ways of improving this is finding a way to satisfy the user with the answer. Sometimes users are unhappy because the answer they recieve is too broad and doesn't solve their issue.