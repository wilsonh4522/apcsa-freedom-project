# Entry 4
##### 3/11/24

## Context
In APCSA (AP Computer Science A) we are doing a year long freedom project where we make any project we want and work on it for the entire schop; year. In this blog I will take you through my progress and plans. For my project I will be creating an alarm that will only stop when a person solves a simple math problem so that they can feel more awake. This is a problem that I struggle with and would like to solve. For this project I need to make my MVP (minimal viable product) so that I have at least something that works. I have so far created the format of my project on how it will look like. I now need to do the backend of the project where I make things work. Throughout the weeks I have tried to create a functioning alarm that can work.
```java
 func scheduleNotification() {
        let center = UNUserNotificationCenter.current()
        
        center.requestAuthorization(options: [.alert]) { granted, error in
            if granted {
                let content = UNMutableNotificationContent()
                content.title = "WAKE UP!!!"
                
                let trigger = UNTimeIntervalNotificationTrigger(timeInterval: 5, repeats: false)
                
                let request = UNNotificationRequest(identifier: "alarmNotification", content: content, trigger: trigger)
                
                center.add(request) { error in
                    if let error = error {
                        print("Error scheduling notification: \(error.localizedDescription)")
                    } else {
                        print("Ok")
                    }
                }
            }
        }
    }

```
## This pops up
<img width="143" alt="Screenshot 2024-03-22 at 10 56 22 PM" src="https://github.com/wilsonh4522/apcsa-freedom-project/assets/91762146/f6fbf178-a724-4295-8b91-32f2805e3aee">

## EDP
In the engineering design process, I am creating a prototype. Like I said, I have so far created the front end of my project and I am now doing the backend so that it is able to work. During the past month I have been working to create a functioning alarm that will alert you and I so far have completed this. My next step is to make a pop up math problem when the alarm rings. 

## Skills learned
During the past month, I have learned how to debug and embracing failure. Writing this code was really hard amd it took me weeks to figure it out. I made a lot of mistakes in my code and it took a lot of time to figure out my mistakes and doing these mistakes I learned how to embrace failure. I would feel frustrated and unmotivated when ever I made a mistake but I got used to it a pushed throught it. I also had to search a lot of things online because I was using new to swift. 


[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
