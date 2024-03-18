# Tool Learning Log

Tool: **Swift**

Project: **An alram that won't stop ringing until you do a task**

---

10/28/23:
* Today I downloaded [Swift Playground](https://apps.apple.com/us/app/swift-playgrounds/id908519492) in the App Store. It gave me an intorduction and tutorials on how to use Swift. It introduced me componets like functions. I also looked at the [documentation](https://www.swift.org/documentation/) on components and [videos](https://www.youtube.com/watch?v=q3KRE-MyCO8&t=498s) of people making apps using Swift to better familiarize myself with the langaage. Some challenges I had was navigated through the app. One question I have is if Swift Playground the same as when you downlaod swift.

11/13/23:
* Today I tried using swift in replit. It was confusing to use but I read some documentation about swift in replit. 

11/26/23:
* Today I will try coding swift with replit and trying some components from the swift documentation. I tried coding time by looking at this swift [component](https://developer.apple.com/documentation/foundation/dates_and_times) since I will be needing to use time for my alarm. I am still deciding if I want to do a [timer](https://developer.apple.com/documentation/foundation/timer) or a fixed time. I am figuring out which is easier for my MVP (Minimal Viable Product). Since I am making an alarm so I need sound so I looked at this [documentation](https://developer.apple.com/documentation/soundanalysis/) about sound and began tinkering about it. Using replit is a bit confusing to use so I will go home and use Swift Playground. One challenge I face is that there are a lot of components of each timer and sound so I don't know which one to use.

12/4/23:
* Today I wanted to find out if I needed to download x code if I wanted to create my project. I also began looking more at what compnents I will use when making the project.

12/18/23
* Today in class I began looking at projects made from Swift. I also looked at some of the code it uses so I can better familiarize myself with it.

1/8/24
* Today in class I began to familiarize myself more with Swift. I looked more at documentation, videos, and other projects.

1/22/24
* Today in class I began looking at some of the componets I will use in my project. For example I have to get the user's input for the time they want to wake up. I also am looking at sound so the user can wake up.

2/26/24
* Today in class I began looking at the to-do list for my freedom project and I need to figure out how to make a functioning alarm for my MVP. I am figruing this out by looking a components in Swfit and reasearching people doing it. I found this [component](https://developer.apple.com/documentation/eventkit/ekcalendaritem/1507397-addalarm) that I may be able to use to make a functioning alarm and [this](https://developer.apple.com/documentation/eventkit/ekalarm/1507227-soundname) can be the the sound of the alarm. I could use [this](https://www.youtube.com/watch?v=pnM_3zcDbjk) and [this](https://www.youtube.com/watch?v=SUA2wzjpYjo) to make sound in my alarm.

3/4/24
* Now that I have researched ways to make sound I need to make a popup math problem. After reasearch a couple of ways I found [this](https://medium.com/@fdika24/creating-modal-popup-in-swift-d34642054fab) tutorial that can help me create a popup math question when the alarm rings. 

3/11/14
* In class today I couldn't do much but research because I couldn't code with swift in the computers. So I began doing research more about each of the parts and tried some of it at home. I did some research to see if I can code my whole Freedom Project on Swift Playgroud because I wasn't sure if I could do that and if I had to install x code.
```swift
var soundName: String? { get set }
```
I am trying to figure out how I could make this work by looking at other projects that use this code.
<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
3/18
Today in class I will figure out how to make a pop up math question and user input to stop the alarm. To start this off I began to research ways to do this on the internet and on youtube I found out that I had to use the `readLine()` component to get the user input. I learned this from this [swift documentation](https://developer.apple.com/documentation/swift/readline(strippingnewline:)). I next need to find out to make a pop up in swift. I figured out how to may an [alert](https://developer.apple.com/documentation/uikit/uialertcontroller) like in Javascript  but I am figuring out how to get the user's input from the alert or if that is even possible. Next I will figure how see if the input is correct so that the alarm can stop and also need to figure out how to stop the alarm. 
```swift
if let inputData = readLine() {
   print("Subject is \(inputData)!")
}
```
I could possibly use this code to compare the user input. 
```swift
import Foundation
import Glibc

print("Please enter number 1")
var num1 = Int(readLine()!)!
print("Please enter number 2")
var num2 = Int(readLine()!)!

var sum = num1 + num2
print("The sum of \(num1) and \(num2) is \(sum)")
```
I could also use this to get the user's input. I got this code from [this website](https://www.tutorialspoint.com/swift-program-to-get-input-from-the-user)
If making an alarm sound will be hard I will use the alert component.

