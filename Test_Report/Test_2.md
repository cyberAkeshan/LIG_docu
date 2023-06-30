- Introduction
  This test is a Frontend test with Java Espresso

- Test Strategy

  To ensure that the frontend of our app works perfectly, we have implemented Java Espresso testing. We programmed our app in Android Studio, which provides us with the option to use Espresso without any additional efforts,   as it is already built-in as a feature for developers.

  We test each individual activity of our app so that we can precisely identify which activities might be causing issues. Additionally, we conduct comprehensive tests for entire processes, starting from the initial 
  registration to creating an item and adding it to the shopping list.

- Test Plan
   
   - Registration
   - Login
   - Create a list
   - Create an Item
   - Check the checkbox of an item
 
- Test Results 

  All individual activities work perfectly fine. However, when testing the entire process from the initial registration to creating an item and adding it to the shopping list, some errors occur. We suspect that this might be due to the limitation of testing individual subprocesses only with Espresso.

  
