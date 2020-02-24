# iOS/Swift Expert Challenge
## Requirements 
This is iOS App Developing challenge.
You have to make this project with Swift 5.
In this project, we will focus on the flexible of the x-axis value according to the Pinch-to-Zoom, and method to make "Bouncing".
Any of 3rd-party libraries are not allowed, and just full-customize iOS default UI components (i.e. UIView, UIScrollView and CALayer)

iOS dark mode support: would be a bonus, but not essential.

Explain more in the detail section.
## What we expect from your code
* Clean code
* Readability
* Extensibility
* Maintainability
* Documentation & Comment
## Technical Description
### Details
* Make this project with **swift 5**
* **Bouncing** on Both Temp & Brix Y-axises, but can not disappear even it content offset goes minus.
* Both Y-axises can not disappear while **Pinch-to-Zoom** and **Scroll**
* The number of X-axis labels and horizontal lines is flexible according to **Scale**, you can specify Max/Min/Default scale factor in mind.
* When sample data of **Brix-axis** is under Zero, Don't **fill in DOT**
* Connect points with **Line**, but connect with **Dash line**, if no sample value on that day.
* You can get more information via [Video](https://github.com/WilliamEven/iOS_Swift_Challenge/blob/master/CZEY7758.MP4)
### Data Structure
* Please try to use Swift-specified modern techniques such as Closure, Enum, Collection Operator(map, filter, reduce), nested function, defer, guard and etc.
* Model
```
struct Sample {
	var temp: Double
	var brix: Double
	var date: Date
}
```
* Input
```
	var samples: [Sample]
```
* Assumption

`date` in samples is not in an ordered sequence. You may need to sort it before drawing.
## Example Picture
Please check these screenshots. 
![Challenge_Img_01](https://github.com/WilliamEven/iOS_Swift_Challenge/blob/master/IMG_1636.PNG)
![Challenge_Img_02](https://github.com/WilliamEven/iOS_Swift_Challenge/blob/master/IMG_1637.PNG)
![Challenge_Img_03](https://github.com/WilliamEven/iOS_Swift_Challenge/blob/master/IMG_1638.PNG)

## Estimate
12 hours
## Delivery
After finish project, share your git repo url to us.

Thanks
