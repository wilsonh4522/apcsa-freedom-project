# Entry 3
##### 01/08/24

### Content
In APCSA (AP Computer Science A) we are doing a **year long freedom project** where we make any project we want and work on it for the entire schop; year. In this blog I will take you through my progress and plans. For my project I will be **creating an alarm that will only stop when a person solves a simple math problem** so that they can feel more awake. This is a problem that I struggle with and would like to solve. For this project I need to make my **MVP** (minimal viable product) so that I have at least something that works. I think making a alarm will be hard so I might consider to make some kind of code that will count to a certain number in which the user wants to wake up, like a timer. Throughout the month I have **working on my project little by little**. I have done I have so far made what the app **would look like but the app does not funciton yet**. I did this buy looking at [this](https://developer.apple.com/documentation/swiftui/datepicker) specific Swift documentation and I did some research on how to do [wheel date picker style](https://developer.apple.com/documentation/swiftui/datepickerstyle) for the looks. 
#### Code for the looks
```java
var body: some View {
        VStack {
            Text("When do you want to wakeup?")
                .font(.title)
            
            DatePicker("", selection: $alarmTime, displayedComponents: .hourAndMinute)
                .datePickerStyle(WheelDatePickerStyle())
//                .labelsHidden()
            
            Button(action: {
                
            }) {
                Text("Set")
                    .font(.headline)
                    .foregroundColor(.white)
                    .background(Color.blue)
            }
        }
    }
```
#### What it looks like
<img width="377" alt="Screenshot 2024-02-18 at 9 20 24 PM" src="https://github.com/wilsonh4522/apcsa-freedom-project/assets/91762146/e3c2dac5-29ac-4c81-a529-da1d40f95351">

It looks like the timer from iphone. For the next month or so I wil try to make a function that will take the user's input and make a sound to wake them up in the time they want to wake up. 

### EDP    
In the **Engineering Design Process**, I am planning the most promising and minimal solution. I am doing this by figuring out a way to make a counter that will count to a certain number and wake up the user. I also **need to figure out how to make sounds when the alarm rings and make a pop up of a math problem**. I can use this [component](https://developer.apple.com/documentation/foundation/timer) in swift but I will need to figure out how to use it. 

### Skils learned 
The two skills I learned during the past month is **how to learn and read**. When creating the design I had to **learn how to write in swift** this was challenging because it was my first time doing it. I made many mistakes but I learned from it. I learned the skill of "how to read" because I had to **look through some swift documentation to further understand the code**. 

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
