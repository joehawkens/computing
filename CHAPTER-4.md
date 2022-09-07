# Software Engineering


## Firmware

So the computer has recieved power from the elctrical grid, all computer hardware is running, so where does software begin to peak its head in this process? The handoff from Hardware to Software begins with **Firmware**. Firmware is a hybrid of Software and Hardware; you can think of it as embedded Software for each piece of Hardware. Firmware is our first taste of Software, it's usually written in low-level/mid-level programming languages (C or Assembly). This Firmware communicates with the Hardware which is translated into Machine Code.

The first piece of Firmware that's activated when you press the power button is the BIOS (Basic Input Output Stream) - A firmware chip attached to the Motherboard. The BIOS runs a test on all the components in the computer to make sure everything is adequately connected - this is called a P.O.S.T (Power On Self Test). When the POST is complete, a single beep sounds from the computer letting you know it's ready to go. Multiple beeps or no beeps indicate there are problems.

There is another computer chip, called CMOS (Complementary Metal-Oxide Semiconductor) which runs constantly, it holds the BIOS data (Hardware Settings, Bootup Settings, Time+Date). It has a battery in it, so even after you turn off the computer, this chip will still be recieving power, the reason for this is because BIOS chips come with default settings. If you add any customization, which you will since date and time is constantly changing, there's no way to store that information after everything is shutoff, so CMOS is necessary to maintain settings and ensure proper bootup when the computer starts.

Once the BIOS communicates with CMOS and recieves the proper information to activate the hardware, a bootup sequence is initiated and the BIOS transfers its keys and power to the Operating System, the first pure piece of Software - which helps to act as a mediator between the user and the machine.


## Operating System

Now that the Operating System is installed on the computer - usually through a disk or a thumb drive that's accessed by the BIOS - and stored in the hard drive, it gives us access to the machine and allows us to interface with it in more human-friendly ways, one of which is having a GUI (Graphical User Interface). The operating system also communicates with device drivers - software that allows understanding between devices and the OS - so that they're able to function properly in the OS environment. The operating system itself are usually written in low/mid-level languages such as C or Assembly.


## What's Next?

Now that an Operating System is in place, we use it as a foundation to build programs. We can explore more in-depth the science of Software - different paradigms, design paterns, problem solving, etc. The next few chapters will dive deeper in Software Engineering and go over key concepts to help you gain a comprehensive overview of the discipline.
