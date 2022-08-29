# A. Descriptive Questions:
## Can we nest the Scaffold widget? Why or Why not?
#### Yes Flutter allow this,But we are nested because The Scaffold was designed to be the single top level container for a MaterialApp and it’s typically not necessary to nest scaffolds. For example in a tabbed UI, where the bottomNavigationBar is a TabBar and the body is a TabBarView, you might be tempted to make each tab bar view a scaffold with a differently titled AppBar. It would be better to add a listener to the TabController that updates the AppBar
## What are the different ways we can create a custom widget ?
#### 1. Create dart class file that extend stateless or satefull.
#### 2. Create function that have a return type Widget.
## How can I access platform(iOS or Android) specific code from Flutter?
#### Wiith the help of method channel functionality provide by flutter.
## What is BuildContext? What is its importance?
#### BuildContext is a locator that is used to track each widget in a tree and locate them and their position in the tree. The BuildContext of each widget is passed to their build method. Remember that the build method returns the widget tree a widget renders.

# B. Coding Questions:
### 1. Refactor the code below so that the children will wrap to the next line when the display width is small for them for them to fit.
<img width="545" alt="image3" src="https://user-images.githubusercontent.com/4019977/187225239-1a96ee9b-9f60-4c4e-b787-2f432e7efbcd.png">
Just replace row to Wrap

### 2.Identify the problem in the following code block and correct it.
#### It blocks your app because counting to ten billion is a computationally expensive task, even for a computer.Dart code runs inside its own area of memory called an isolate — also known as memory thread. Each isolate has its own memory heap, which ensures that no isolate can access any other isolate's state.
 
 <img width="566" alt="image1" src="https://user-images.githubusercontent.com/4019977/187225344-101bca38-0098-4bbe-b2ce-1197f7bed04b.png">

### 3. In the below code, list1 declared withvar, list2 with final and list3 with const.What is the difference between these lists? Will the last two lines compile 
<img width="742" alt="image2" src="https://user-images.githubusercontent.com/4019977/187225371-47ad40f9-0ca7-475b-a95e-d8f44218014d.png">


