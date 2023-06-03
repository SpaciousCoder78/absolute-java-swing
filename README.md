# absolute-java-swing
 Learn Java Swing from the scratch for free
 
# Contents
- What is Swing?
- How to Use Swing?
- Creating a window using Swing
- Adjusting size of the window
- Closing the window

## What is Swing?
Swing is a built-in GUI library that comes with JDK. It's a lightweight and easy to use library. It's also an extension of AWT. Swing supports a lot of features and its the ideal library for building simple and interactive desktop GUI apps. JavaFX is the successor of Swing but it has a learning curve and is mostly used for web applications whereas Swing can be used for small-scale GUI applications .

## How to use Swing?

Since Swing is a built-in library, we can directly import it from our java file without the need of Gradle or Maven. 

It can be imported using ```import javax.swing.*``` 

Once you add that line of code to your java file, you can start using Swing's elements in your Java code.

## Creating a window using Swing

In Swing, we use a JFrame to store our UI elements. It's the basic window where our UI elements are placed. Without a JFrame, we won't be able to see any Swing elements that we code into our app.

Let's create a JFrame now.

``` JFrame frame = new JFrame("newwindow")```
And that's it, we've created a JFrame but if you try to run this code in a main function in your java code, you'll see nothing. It's because by default, JFrame is set to invisible. You need to make it visible by manually typing ```frame.setVisible(true);```.

## Adjusting the size of the window

Now we've made a JFrame. If you run the code, you'll notice that it looks something like this.
![image](https://github.com/SpaciousCoder78/absolute-java-swing/assets/88923986/0db40992-a6ef-4674-9564-8e232d8fa5cc)

This is because we didn't set the size of the window. To set the size of the window, add ```frame.setSize(x,y);``` where x is the width and y is the height of the frame.

I'm setting it to 400x400.

![image](https://github.com/SpaciousCoder78/absolute-java-swing/assets/88923986/775d728a-9362-42c9-9460-776dd8c63ca0)

Now it looks nice and neat.

## Closing the window

If you close the window, you'll notice that the code still doesn't terminate. It still runs. To avoid this, add ```frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);``` to your code.

## Adding components to the JFrame

So, we've made a 
