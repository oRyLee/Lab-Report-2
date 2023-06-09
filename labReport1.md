LAB REPORT 2!

Part 1:

Firstly I began with the code for needed for successfully creating the servers.

This is the code for string server! : 

![Image 5-10-23 at 9 24 PM](https://github.com/oRyLee/Lab-Report-2/assets/130015533/6e4a01de-cef8-4528-bd89-b423a87608ae)

<img width="843" alt="Screenshot 2023-04-24 at 11 32 39 PM" src="https://user-images.githubusercontent.com/130015533/234193467-fdd68803-be4c-4fb4-a8d6-d9a0f1357317.png">

After running the code in my terminal to create a server I created one of my own, and this is what it looks like below  once I added a string to it by using the format ```/add-message?s=<string>``` and typing that into the search bar:
  
![Image 5-10-23 at 9 14 PM](https://github.com/oRyLee/Lab-Report-2/assets/130015533/1c1e3048-50d1-4c47-90c2-aa88d21c85be)

Q & A:
Which methods in your code are called?
- the handleRequest method is called, the handle method from the class of ServerHTTPHandler, as well as the main method within the StringServer class

What are the relevant arguments to those methods, and the values of any relevant fields of the class?
- the relevant arguments within creating a server is the first argument put into the command line which is the 4 digit number which serves as the port number

How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why.
-The port number value is subject to change when being input to the command line
  
  
  
I did the same process to add another line of text in the search bar with the format ```/add-message?s=<string>```, I then did this process twice with the strings "Hello" and "How are you" and saved them: 
  
 After saving them I was met with this screen: 
 ![Image 5-10-23 at 9 49 PM](https://github.com/oRyLee/Lab-Report-2/assets/130015533/a6b60e49-ab12-43a5-a6a0-a32316688e88)

  
  
 Once reloading the server in the browser the text I added successfully saved and this was the final screen:
![Image 5-10-23 at 9 16 PM](https://github.com/oRyLee/Lab-Report-2/assets/130015533/1755e5e9-651f-444a-993b-c8fd0804e911)

Q & A:
Which methods in your code are called?
- the handleRequest method is called, the handle method from the class of ServerHTTPHandler, as well as the main method within the StringServer class

What are the relevant arguments to those methods, and the values of any relevant fields of the class?
- the relevant arguments within creating a server is the first argument put into the command line which is the 4 digit number which serves as the port number as well as the portion of the path that had "/add-message"

How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why.
-The port number value is subject to change when being input to the command line as well as the string added in the search bar after "/add-message?s="
 
 
Part 2:

A bug I saw in the lab was in the ArrayExamples class where the implementation of reversing the last element of the array did not work successfully:
![Image 5-10-23 at 10 33 PM](https://github.com/oRyLee/Lab-Report-2/assets/130015533/d2ea484a-43b9-440d-bd3a-985fd690c29e)

A test that is non-failure inducing and one that is failure inducing is shown below:
![Image 5-10-23 at 11 04 PM](https://github.com/oRyLee/Lab-Report-2/assets/130015533/4b4e90a7-a2c2-4904-99fd-e1cccc55d495)

the failure inducing input brought on this error because the expected and actual were not the same:
![Image 5-10-23 at 11 14 PM](https://github.com/oRyLee/Lab-Report-2/assets/130015533/289407ac-c0fe-4ca4-89bd-4b8de97f766d)



After evaluating the code this is the correctly implemented code I came up with:
![Image 5-10-23 at 11 17 PM](https://github.com/oRyLee/Lab-Report-2/assets/130015533/0c696370-df70-40fa-aaa9-b6db1d75c4e7)



After making new tests for the new code (which are shown below) I ran the tests and they worked successfully!
![Image 5-10-23 at 11 19 PM](https://github.com/oRyLee/Lab-Report-2/assets/130015533/21692a43-8866-47ac-9fb6-066e53b48fcc)

Part 3:
Something I've learned from the lab was how to use JUnit to run tests which became easier because I had trouble with it before. I also learned how to create a server and the code that is written to create one, which was interesting. I also learned more about common errors in code implementations from all of the bugs we observed. Overall the labs were helpful and opened my eyes to new code.





  

  
 




