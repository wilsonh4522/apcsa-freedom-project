# Entry 5
##### 5/1/24

### Context
In APCSA we are doing a year long project where we get to create anything I want. For my project I decided to make an alarm that will only stop until you solve a math problem. For this I used Swift to code the project. I have finished my MVP (Minimal Viable Product) which is that I created a functioning alarm but the feature that I wants isnt there. I am now trying to make a pop up math problem where the users inputs answer and if it is correct the alert will stop. This is challenging to do but I have my MVP.

### Content
I wanted to get the users input when the alarm rings so I began to research how to get the user's input in general and I saw this [Swift Documentation link](https://developer.apple.com/documentation/uikit/uilexiconentry/1614132-userinput) but I had to figure out how to make the user input in the alert. I found this 
```
.alert("Enter your name", isPresented: $showingAlert) {
            TextField("Enter your name", text: $name)
            Button("OK", action: submit)
```
I could possibly use this for my code and see if it works. 
### EDP


[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
