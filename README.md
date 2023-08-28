# Navigation-in-android

![navigation component](https://github.com/Vijaya9418/Navigation-in-android/assets/56352158/4411f755-7fef-4761-a288-273aa9686edf)


**why navigation component?**

when we work with our android apps, when we think about navigation , we simply thinks that navigation is going from one activity to another activity by a button click etc. 

But if want to do something complex like doing navigation with bottom navigation bar, in that we need to take care of lot of things like on click of that button the correct page should open and button should get highligted and need to take care care of back- stack in a uniform way, so that pages don't get piled up again and again. so that users dont get confused. 

![fragment component](https://github.com/Vijaya9418/Navigation-in-android/assets/56352158/f9e42553-2b39-49a1-9f0f-82dd92f50989)

So in cases like this navigation component comes into play.

**what is Navigation component?**

The navigation component is a collection of libraries, plugins and toolings that simplifies android navigation.

**Benefits:-**

1. Simplified approach for smooth and correct navigation.

2. Handles backstask.

3. Type safe argument passing.

4. Handles transaction animations.

5. Most importantly, it gathers the whole information of this navigation component used in your app and centralize into a visual navigation.


**How navigation component works?**

so when we think about navigation component , it works with three major part

1. NavController.
  
2. Navigation Graph

3. Navigation Fragment.


**Navigation Graph:-**

It is a new resource Type. It is an XML file that contains the information and centralize them into a visual state. This information can be visualized in the new editor available in the android studio 3.3. With the help of which we can find the information by clicking on the activity or fragments available in that graph.

![navigation graph](https://github.com/Vijaya9418/Navigation-in-android/assets/56352158/755b5465-d5f3-4bd2-a871-2e9c621945cb)



**NavHost Fragment:-**


It is a layout of the navigation component. It is a fragment widget that you will add to your layout that we are doing the fragment navigation (swiping like left and right).
It is basically a window that swaps in and out to dieffrent fragment destination that are included in the nav graph.

<img width="1382" alt="nav host fragment" src="https://github.com/Vijaya9418/Navigation-in-android/assets/56352158/b9545e27-4679-4c4c-8094-5c7d39ade221">


**NavController:-**

It sits on navhost fragment. Each navhost fragment has a navcontroller that you'll use in your kotlin or java code. which instructs the navigation to occur.


**How Type safe argument passing works in navigation component?**

With SafeArgs Plugins, which is a generated classes based of your navigation graph to ensure type safe access to arguments,destinations and actions.

how it works?

first we will have to add the gradle plugins into our code.
which will generate the classes based on our navigation graph.
It will make the direction classes for any destinations that has actions which we have created in our nav graph.


The navigation components includes the addition UI library in **java** and **ktx** that is an extension in kotlin that have support for options menus, bottom navigations, navigation View, Navigation Drawer.

In kotlin this works with this like of code which handles the actual navigation and handles backstack also handles the highlighting of correct buttons.

<img width="640" alt="Screenshot 2023-06-18 at 6 03 09 PM" src="https://github.com/Vijaya9418/Navigation-in-android/assets/56352158/aeedd18a-1efb-4977-b94d-9b380376a277">




