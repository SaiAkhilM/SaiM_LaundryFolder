# Laundry Folding Machine
<!-- Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails! -->

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Sai Akhil M. | Leigh High School | Mechanical Engineering | Incoming Senior

<!-- **Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here] if you need help. (https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html)** -->

<!-- ![Headstone Image](logo.svg)
  
# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->

# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/Iwm2R2zCeQo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

  This milestone contained by far the most challenging engineering problems I've ever faced. This was very surprising since I originally expected this to be very easy and I thought I could complete this milestone pretty quickly. But instead, this milestone took a little over 2 weeks to complete so it threw me off schedule. For this milestone, I basically assembled and constructed my full machine so that it could successfully fold a t-shirt.

  As a base, I constructed an open wooden box by sawing some large wooden boards and drilling them together. I then brainstormed ways to connect the servo horn on my servo motor to the BoxLegend. This was really challenging since the screw hole on the servo horn wasn't aligned nor in the correct orientation to the board of the BoxLegend. To solve this, I decided I could connect L-brackets and connect it to the screw hole of the servo horn and to the BoxLegend by drilling a hole in the BoxLegend board. I did this for the two boards on the servomotor that fold the shirt left and right. But unfortunately, because I bought really strong servo motors (they could turn up to 35 kg), they ended up loosening the L-bracket from the servo horn very easily. So I had to replace them with weaker motors so that the motors can be mounted securely and not force themselves loose. The weaker motors were able to successfully move the L-brackets and the board of the BoxLegend but they faced the same problem as the stronger motors so I used super glue and thread glue to secure the servo horn and the L-bracket later on.   

  The next problem I faced was a way to secure the servo motor to the wooden box so that it doesn't move so that the horn can consistently move the board of the BoxLegend. To do this, I had to figure out a way to mount the servo motor onto the wooden box. I figured that I could use the screw holes provided on the servo motor and connect it to the edge of the wooden box. But I realized that the plastic holes on the servo motor would break away if I mounted it to the wood because the plastic is very weak. To solve the mounting problem, I received specific servo mounts that would attach easily attach to the wood and secure them better. But due to the nature of these servo mounts, I had to rotate the servo horns on my servo motors 90 degrees so that I also decided to flip my open box upside down and mount my servo motors and BoxLegend to a completely flat surface so I don't have to worry about the edges of the box. 

  After doing that and finally coming up with a plan to mount my 4 servo motors, I started permanently mounting each servo motor to the BoxLegend board and the wooden base. I had to elevate the servo motors with blocks of wood because the metal L-brackets were really big and they kept hitting the floor of the wooden base. I also had to cut a lot of the plastic on the BoxLegend to let the BoxLegend board and L-bracket move freely since the L-bracket was too large. And since I had to elevate the first two servo motors, I had to elevate the other two motors and BoxLegend board with large and smaller blocks of wood. I did this by using super glue and wood screws to create thicker and higher pieces of wood on the wooden base. 

  For the last two motors that fold the t-shirt in half, I couldn't use the metal L-brackets anymore since these last 2 servo motors will be turning the boards in a different axis. Instead of an L-shaped bracket to hold the board of the BoxLegend, I needed a long, straight mount that I could attach to the servo horn and the BoxLegend boards. Since nothing like this existed, I designed a 3d part that I could attach to the servo horn and the BoxLegend Board. This was quite challenging as well since I had to figure out a way to attach the servo horn to the plastic securely but I can't use nuts and bolts due to the way the part had to be structured. I concluded that I could use a heat set insert in the plastic and then put a bolt threw the servo horn and into the heat set insert in the plastic. Once I received the 3d-printed parts, I used a soldering iron to heat up the heat set insert and melt it into the plastic hole. But unfortunately, because my soldering iron was too hot, I accidentally melted too much of the hole which made the heat set insert very loose in the plastic which prevented me from securely attaching the servo horn to the plastic part. I overcame this by using super glue to fill in the gaps in the hole and secure the heat set insert into the plastic. This worked after a couple of tries and I was able to mount the servo motor with its mount to the elevated wood and then connect the servo horn and 3d part to the BoxLegend board. Lastly, I drilled wood screws through the BoxLegend and into the wooden blocks to secure the BoxLegend and keep it in place with the servo motors attached to it.  

Before testing the machine to see if the motors can turn the boards of the BoxLegend, I had to change my code for one of the servo motors so that it can start from the opposite direction and turn in the opposite direction compared to the other 3 motors. This was for the servo motor that folded the shirt counterclockwise. This seemingly simple task was overly complicated and it took me a lot of guessing and checking with making minor changes to the code until I got the servo motors to do what I wanted them to do. I also had to alter the code for when I replaced the strong servo motors with the weaker servo motors because I noticed that servo motors acted differently. Originally I thought that these newer servo motors were faulty since what they were doing did not seem like a coding problem. So I opened up the servos and checked the gears. After realizing that it was actually a coding problem, I similarly made very small changes to the code and guessed and checked until I got the servo motors to work properly. When testing the machine, I encountered the boards not moving through their full range of motion due to the L-brackets hitting the other plastic boards. To solve this, I used the Dremel to cut away a lot of the plastic on the BoxLegend so that the boards folded the shirt with the correct range of motion. 

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/fQ9N4MLIFkQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> 

  For my first milestone, I set up the two main parts of my project: the improved BoxLegend (a large flat plastic board used to fold clothes) and the electronics. For the improved BoxLegend, I used parts from two BoxLegends to add an extra joint so that the machine can place a folded article of clothing aside instead of folding it and leaving the folded clothing on top of itself. I had some slight trouble with how to construct this but overall I was able to construct it by using a saw and scissors to cut the plastic and I used hot glue and a hot air gun to attach the two BoxLegends together. 

  For the electronics, I wired my servo motors, Arduino Mega, power supplies, motor driver, and button together. I then wrote the code and troubleshoot until I was able to get the click of a button to consecutively run the 4 servo motors 180 degrees and back. The code was pretty challenging at first since I wasn't used to the functions that controlled the servo motors and because I over-complicated the logic but in the end, I was able to simplify the code and get it to work. Next, I plan to attach the electronics to the improved BoxLegend and assemble all of that to a base so that the machine can successfully fold a shirt and place it aside.  

<!-- # Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. -->

<!--```c++ 
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```


# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/) -->

# Starter Project: DIY RGB
The DIY RGB is basically an RGB that changes colors as you adjust the three linear potentiometers which control the level of Red, Green, and Blue that is in the RGB. This starter project warmed me up for my intensive project. All I had to was solder the RGB and the three potentiometers in the correct orientation into the protoboard. I thought this was going to be easy but I soldered my RGB in the incorrect orientation so I had to spend hours removing the solder with a soldering iron and solder sucker. Eventually, I was able to resolder the RGB in the correct orientation and get the DIY RGB to work after connecting it to power.

![DIY RGB](IMG_2967 (1).png)


