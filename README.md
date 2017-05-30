# Raspberry Pi 3 Projects for Java Programmers
This is the code repository for [Raspberry Pi 3 Projects for Java Programmers](https://www.packtpub.com/hardware-and-creative/raspberry-pi-3-projects-java-programmers?utm_source=repository&utm_medium=github&utm_campaign=repository&utm_term=9781786462121), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Our book is a project-based guide that will show you how to utilize the Raspberry Pi's GPIO with Java and how you can leverage this utilization with your knowledge of Java. You will start with installing and setting up the necessary hardware to create a seamless development platform. You will then straightaway start by building a project that will utilize light for presence detection. Next, you will program the application, capable of handling real time data using MQTT and utilize RPC to publish data to adafruit.io. Further, you will build a wireless robot on top of the zuma chassis with the Raspberry Pi as the main controller. Lastly, you will end the book with advanced projects that will help you to create a multi-purpose IoT controller along with building a security camera that will perform image capture and recognize faces with the help of notifications.


## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

The code will look like the following:

  ```
    /**
    * Run the LCD example.
    */
     public final void runExample(){
    /// Clear the display
    handler.clear();
   /// Cursor to home position (0,0)
    handler.setHome();
   /// Write to the first line.
    handler.write("-- RASPI3JAVA --");
   /// Create a time format for output
   SimpleDateFormat formatter = new
   SimpleDateFormat("HH:mm:ss");
  /// Sets the cursor on the second line at the first
   position.
   handler.setCursor(1, 0);
  /// Write the current time in the set format.
   handler.write("--- " + formatter.format(new Date()) +
  " ---");
  }
```

## Related Products
* [Raspberry Pi Projects for Kids - Second Edition)](https://www.packtpub.com/hardware-and-creative/raspberry-pi-projects-kids-second-edition?utm_source=repository&utm_medium=github&utm_campaign=repository&utm_term=9781785281525)

* [Raspberry Pi for Python Programmers Cookbook - Second Edition](https://www.packtpub.com/hardware-and-creative/raspberry-pi-python-programmers-cookbook-second-edition?utm_source=repository&utm_medium=github&utm_campaign=repository&utm_term=9781785288326)

* [Raspberry Pi Cookbook for Python Programmers](https://www.packtpub.com/hardware-and-creative/raspberry-pi-cookbook-python-programmers?utm_source=repository&utm_medium=github&utm_campaign=repository&utm_term=9781849696623)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions. 

