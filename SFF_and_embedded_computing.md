# Raspberry Pi, Arduino, and Small Form Factor Computing
### What does it do?
While looking similar to a new observer, the Arduino Family and the Raspberry Pi are both very different devies.  Arduino is a brand name that has become synonymous with microcontrollers much like Kleenex has become to tissue paper while the device that is most commonly thought of when discussing the Raspberry is in fact a fully featured computer.  Both were developed as educational tools but have found uses with hobbyists and researchers and have even been deployed into production environments in a variety of operations.

We will explore the differences and similarities over the next few paragraphs and look at the differences in application for these and similar devices.  

#### What is the Raspberry Pi?
The Raspberry Pi Family consists of a number of device types.  The original Model B was released in 2012 and met with a huge demand.  Personally I experienced a 2 month wait to receive mine.  Initially the Pi was released with USB, HDMI out, 256MB of RAM, and an SD card slot for loading the OS.  This Pi was slightly larger than a credit card in its major dimensions and at its tallest, the height of a PCB mounted RJ45 jack.  Over the years this form factor has had a further three iterations with extra features added including Wifi and Blutooth and the family has expanded to include the Raspberry Pi Zero and the Raspberry Pi Pico, both much smaller in size.  What was revolutionary about the Pi was the incredible performance at the price and the access to the General Purpose Input Output pins.  This was something that computer hobbyists in the past had never really had access to in the past without performing modifications to their existing PCs.

#### What is the Arduino?
It is important to note that Arduino is not actually a specific device or chip, but rather a foundation with a goal to lower the barrier to entry into the world of electronics and microcontrollers.  When Arduino is discussed, the most common item that is thought of is the Arduino Uno with the ATmega328 DIP IC.  The Uno itself is a single breakout board with an on board ATMega328 Microntroller and the associated electronics required to make it a functional piece of equipment out of the box.  Prior to Arduino, when someone wanted to explore the world of electronic engineering and microcontrollers, they had to create a lot of the circuitry themselves and purchase other equipment such as PIC programmers.  When referring to an "Arduino", someone may be referring to any number of microcontroller development or breakout boards however they all tend to be programmed using some sort of UART interface using a C like language in the arduino IDE.  Since the release of the Arduino Uno, a number of other devices (of note, the ESP32 and ESP12) have been released onto the market with extra features such as wifi and bluetooth.

#### What is the difference?
While the two devices are similar in appearance and can perform some similar applications to each other, the application can vary dramatically.  The Raspberry Pi is really just a small computer and as such can support a number of higher level applications, while the arduino is a device that is generally used for an embedded application and rapid prototyping of electronic gadgets.  Once you have developed a protoyped it is common to develop your own circuit board around the chip itself, omitting circuitry from the development board that is no longer required and miniaturising the whole assembly for production.  

The Raspberry Pi generally runs a Linux Operating System, while the arduino is generally coded in C and then compiled into Assembly.

#### What is the future of this technology?
As technology improves, further enhancements will be able to be made.  In the case of the Arduino style of microcontroller development board, more and more new ICs will be miniaturised and delivered to the market.  This will bring newer technologies into the reach of more creators, educators, and hobbyists, which in turn will drive innovation and further new technologies.  The future is bright for those that can operate these tools.

The future of the Raspberry Pi I predict will share a similar trajectory to that of the Arduino, but for a slightly different audience.  While the Arduino family comes in a number of different form factors, since the raspberry Pi2, the pi has become locked into its current form factor by its desire to remain backwards compatible with the sheer amount of expansion boards that are available to it.  The Raspberry Pi foundation has sought to work around this possible limitation by releasing the Zero and Pico Models, both of which boast similar specifications to their larger brother but with an even smaller form factor.

### What is the likely impact?
With the Pi, an update is normally made every couple of years to improve the specifications of the product and add features as newer technology becomes cheaper and allows the Raspberry Pi Foundation to continue to deliver a low cost product in line with their goals.  The future of the Arduino Uno will still remain, however newer chips with better performance and more features in a smaller package continue to be put onto development boards and marketed while the community develops compilers to program them.

The older Raspberry Pis will become obsolete for some use cases as system requirements advance although there will still be a place for them for their orignal purpose of education or even some hobbyist implementations.

The vision of both the Arduino and the Raspberry Pi foundations are very similar, and any improvements that can be made to the technology that allows them to deliver their original visions at a low cost will have a positive impact across the world.  Of particular note are groups that may never had access to these sorts of educational materials in the past.  As part of the Australian Governments Digital Technologies curriculum, students in year levels as low as 3 and 4 can be taught the basics of flow control and iteration (Ref Page 2: <https://docs.acara.edu.au/resources/Digital_Technologies_-_Sequence_of_content.pdf>).  The low cost of the Raspberry Pi allows this education to be delivered to areas that in the past could never have hoped to deliver this type of content.  Secondly, the low cost allows the technology to be brought into more and more homes where access to anything IT related may have been out of reach in the past.

While developments to these items may not directly make any individual item redundant or relegate it to history, the knowledge, experience, and ideas gained from individuals experimenting and developing these sorts of platforms will continue to drive innovation an the IT and electronic engineering sectors.

### How will this affect you?
#### How will it affect me personally
I am always finding a use for this sort of technology in various hobbies and further improvements and miniaturisation is only every a good thing in my opinion.  More access to this sort of technology will enable innovation from a wider cross section of the community.  A person who may have only had a passing interest in electronics or engineering may be driven to explore the topic further and accomplish great things because the basic tools were accessible to them easily.

#### How will it affect the wider community
##### Changes to how we use IT
While a computer may have been a ubiquitous item in the household recently, more and more the internet is being accessed by mobile devices instead of computers (Ref: <https://www.abs.gov.au/statistics/industry/technology-and-innovation/household-use-information-technology/latest-release>).  Personally I have friends and colleagues with children in Primary school that do not have a laptop or desktop computer in the house and instead accomplish the entirety of their online lives using mobile devices.  These same people have no interest in setting aside their limited space for a desktop computer or an IT workspace.
##### Where does this leave the children?
Consider a child growing up in a household like the one detailed above.  It would be such a shame to see the interest in technology or creativity stifled due to a large cost barrier to enter or the amount of space that a dektop computer or an electronics workspace could take up in a small envirnoment.  This problem is overcome by the small nature of devices like the Raspberry Pi and Arduino family.  Being able to cultivate interst in these fields from a young age at home and at their own pace may be enough to change the trajectory of their life and career forever.

### Final thoughts
While researching this, I came across the blog page <https://www.raspberrypi.org/blog/> on the Raspberry Pi Foundation website.  A number of the stories listed echo my own thoughts and the facts detailed above.  I would encourage anyone reading this to have a quick browse and see how the foundation is indeed making a difference.

## References
- Raspberry Pi Foundation
   - Pi, R., 2022. Teach, Learn, and Make with Raspberry Pi. [online] Raspberry Pi. Available at: <https://www.raspberrypi.org/>
- Arduino Foundation
   - Arduino.cc. 2022. Arduino - Home. [online] Available at: <https://www.arduino.cc/>
- Australian Curriculum: Digital Technologies: Sequence of content 
   - Australiancurriculum.edu.au. 2022. PDF documents. [online] Available at: <https://www.australiancurriculum.edu.au/f-10-curriculum/technologies/digital-technologies/pdf-documents/>
- ABS: Household use of IT
   - Australian Bureau of Statistics. 2022. Household use of information technology, 2016-17 financial year. [online] Available at: <https://www.abs.gov.au/statistics/industry/technology-and-innovation/household-use-information-technology/latest-release> [Accessed 7 January 2022].

