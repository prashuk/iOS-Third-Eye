# Third Eye

An iOS app for empowering visually impaired to help finding their belongings and overcome day-to-day struggles through Mobile camera as "Third Eye" using Object Detection Algorithm and speech recognition.

![Screen Shot 2019-10-19 at 11 24 03 PM](https://user-images.githubusercontent.com/17843556/67154305-f7201780-f2c7-11e9-9833-0eb273222a0a.png)
 
# Introduction
Our project takes input from User to find a specific item using speech-to-text and detects the requested object in the room in "REAL-TIME" and using beep sensing and vibration in the mobile phone it will guide the user to the item. <br/>
@authors: <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<i>Prashuk Ajmera<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Hitesh Verma<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Parag Bhingarkar<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Genglin Liu<br/></i>
         
# Challenges
- Detecting Object in "real-time"
- In order to decrease the latency of response from the deep learning model, we had to integrate the neural network with the iOS platform and deploy the model on the mobile phone itself, instead of relying on a cloud service and getting detection results from the cloud.
- choosing the most-fit Object Detection Algorithm
- integrating the neural network on an iOS platform instead of on a cloud service

# Technologies Used
- Swift
- Python
- AI/Machine Learning
- iOS Frameworks (AVKit, Speech, CoreML)

### Platform requirements
The program was developed on XCODE 11.2 with Swift 5.1 programming language and it is available for iOS 11.0 and above.
The following frameworks are used to build the application

# Demo Links
- [Youtube link](https://youtu.be/b543EcMP2SA)
- [Project Source](https://dashboard.hackumass.com/projects/54)

## Next Step
Extending our app using Drone which can help to find items without any human support and can freely rotate in 360 angles. It would be interesting to use a combination of MobileNet and SSD to detect an object in real-time video streaming.
