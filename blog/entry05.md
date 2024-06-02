# Entry 5
##### 5/1/24

### Context
In APCSA we are doing a year long project where we get to create anything I want. For my project I decided to make an alarm that will only stop until you solve a math problem. For this I used Swift to code the project. I have finished my MVP (Minimal Viable Product) which is that I created a functioning alarm that will alert the user for what time they want to be alerted. I am now trying to make a pop up math problem where the **user's inputs** answer and if it is correct the alert will stop. This is **challenging** because I will have to do a lot of research and learn; however I **do have my MVP**.

### Content
I wanted to get the users input when the alarm rings so I began to research how to get the user's input in general and I saw this [Swift Documentation link](https://developer.apple.com/documentation/usernotifications/untextinputnotificationresponse) but I had to figure out how to code it. I figured out that I had to put it into a class in order for it to work. 
```swift 
class UNTextInputNotificationResponse
```
I began research on how to use this code so I went to [slackoverflow](https://stackoverflow.com/questions/51386248/swift-get-content-from-untextinputnotificationaction-in-appdelegate) to see an example of it
```
if let textResponse = response as? UNTextInputNotificationResponse {
                let userAnswer = textResponse.userText
                print("User's answer: \(userAnswer)")

} 
```

In this code I was able to get the input from the alert I had to do [research](https://mahigarg.github.io/blogs/as-operator-in-swift/) on the `as` componment since there were alot of kinds. 

<img width="230" alt="Screenshot 2024-05-30 at 9 36 31 PM" src="https://github.com/wilsonh4522/apcsa-freedom-project/assets/91762146/e811a992-a63a-416a-81f8-1be81c3c4434">

### EDP
In the Engineering Design Process, I am creating the **prototype of my feature** which is to to get the input from the user. My next steps would be testing it and fixing any bugs.

### Skills Learned 
One skill I learned is **how to google** because I had to research on how to get the user's input from the alert. Before doing research I wasn't really sure if I could even get the user's input from the alert. After discovering this I had to google how it used and how to code it. Another skill I learned is **embracing failure** since I had a lot of errors when making this code even though it was a small block of code. 

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
