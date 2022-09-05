# Computer Engineering

Now that we have access to power, the system of the computer is brought to life, but, what makes up this system? How is it organized? And what enables it to allow for programming at the end of the line? This chapter aims to answer all of these questions.

## How are computers structured?

The way a computer's hardware components are structured is referred to as its architecure. The are many different types of computer architecture, but the most famous and widely used design is called "Von Neuman" Architecture, now before I go into the details of this design I want to make clear that the speciality of computer engineering has several layers of abstraction too, I won't be covering all of it in this tutorial simply because it's a high volume of information, so I'll be skipping over a lot of information regarding hardware and focus soley on what affects the workflow of a Software Engineer.

In a traditional desktop computer there are usually 6 components that work together in concert. I've divided them into three groups, they are:


### Organization
* Power Supply Unit (PSU)
* Motherboard

### Processing
* Central Processing Unit (CPU)
* Graphics Card (Video Card)

### Storage
* Random Access Memory (RAM)
* Hard Drive


## Organization

From last chapter we left off with the Power Supply, we know it gives electricity to the computer and converts the AC power from the wall to DC. This power supply is plugged in directly to the Motherboard. The Motheerboard is epicenter of communication between all components of the computer, it's used as a bridge connecting everything together. For instance, if the RAM component wants to communicate with the Hard Drive component they do so through the Motherboard.

## Processing

The next component is the Central Processing Unit (CPU), which is found ON the Motherboard. This processes tasks and instructions from every component in the computer - much like how the Motherboard is the epicenter of connecting components physically, the CPU is what processes actions done by ALL components - for example: you save a file on your computer, the action is processed on the CPU, and the CPU communicates with the Hard Drive for long-term storage. Anything action or instruction your computer carries out is PROCESSED through the CPU.

The Graphics Card is a tricky component. This is because it's essentially a computer itself. It contains a GPU (Graphical Processing Unit) - what the GPU is to the Graphics Card the CPU is to the computer. The Graphics Card contains thousands of cores, which are essentially mini calculators, with the sole function of processing graphics on your screen; this makes videos and other complicated visuals on screen more easily processed. If you left out the Graphics Card, you wouldn't be able to play video games, watch movies or videos, or do anything that uses heavy graphics. The graphics card's purpose is to process complicated visuals. The CPU could technically do this, but it's already processing huge loads of information already, hence why the graphics Card is a necessary component to include in your hardware.


## Storage

Computers can be simplified down to a simple input/output concept. You input something in the computer, there's some sort of processing, and the computer responds with an output. These data points of input/output much of the time need to be stored while they're being used and while they are not being used, that is where storage comes in: If you want to do the calculation 1 + 1 on your computer, your computer first needs space to store the "1" and "+". Because you're using it in that moment, it's stored in Random Access Memory, a temporary storage location for files being currently used. But say you want to save the output of that calculation: "2" for tomorrow, where would you store it? The answer is in the long-term memory storage component of the computer: the hard drive. When you turn your computer off, the data is safely stored in this hard drive, later to be accessed (by RAM) later.


## The Bridge Between Hardware and Software: Firmware

The transition from Hardware to Software is done through "Firmware" - We'll discuss this in the next chapter.

## Chapter 3: Summary

Power is gained through the power supply unit. This is connected to the Motherboard. The Motherboard physically connects all computer components together, the CPU, which is found on the Motherboard, performs all of the computer's tasks and operations. The Graphics Card takes care of operations having to do with complex visuals on screen such as video games or movies. This is all done in real-time through Random Access Memory, which acts as a short-term storage area for manipulating data. If a user wants to save data for later without losing progress, they're able to do that with a Hard Drive.
