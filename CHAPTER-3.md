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
* Hard Drive
* Random Access Memory (RAM)


## Organization

From last chapter we left off with the Power Supply, we know it gives electricity to the computer and converts the AC power from the wall to DC. This power supply is plugged in directly to the Motherboard. The Motheerboard is epicenter of communication between all components of the computer, it's used as a bridge connecting everything together. If the RAM component wants to communicate with the Hard Drive component, they do so through the Motherboard.

## Processing

The next component is the Central Processing Unit (CPU), which is found ON the Motherboard. This processes tasks and instructions from every component in the computer - much like how the Motherboard is the epicenter of connecting components physically, the CPU is what processes actions done by ALL components - for example: you save a file on your computer, the action is processed on the CPU, and the CPU communicates with the Hard Drive for long-term storage. Anything action your computer does goes through the CPU.

The Graphics Card
