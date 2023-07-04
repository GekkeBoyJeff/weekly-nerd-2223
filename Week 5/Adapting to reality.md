Progressive enhancement by Aaron Gustafson

Aaron Gustafson works for microsoft on the progressive enhancement team.

## Web design & development is hard
In the beginning the web was very small in terms of screen sizes. we started with 640 x 480.
We built fix-sized web pages.

Later we were able to make websites for 800 x 600 resolutions. 
We had no media queries to fix things.

Screens kept getting bigger. then we were at 1024 & 768 > 1200 x 800

We were happy to ignore mobile screens example: (240x 240 or 640 x 200)

We did this untill smartphones came around. they were able to produce web sizes of 320 x 480 and bigger.

To handle all kinds of screen sizes we got media queries. they made fixed layouts and called it adaptive layouts.
They also started making responsive layouts as we know today.

Desktops today have big resolutions. normal screens have 1920x1080 but we're already going towards 

## Chasing screen sizes is clearly a fool's errand

"In the second quarter of 2008 we detected 71 different screen resolutions among our visitors. In the first quearter of 2014 we detected 1062"
- Jaron Samuels
  IT Manager, National councel on family relations.
  
## And then there's everything else

### Your content can go and will go anywhere that's connected
Like wearables, smart tv's IoT devices and assistants.

### Meaning users will need to interact in different ways

- Eye tracking
- t9
- touch
- mouse
- remote
- pen
- braille
- print
- keyboard
- audio
- gamepad

Also controllers with toung movements etc...

### Over varied networks and in changing conditions

- Wifi
- hardline
- mobile
- homes
- buildings
- cars
- buses
- trains
- airplanes

Things like latency can affect how our content is being experienced.

### And ultimately, our users all have different needs too

Has anyone noticed I haven't mentioned browsers?

So...? how do we cope with everything

Nothing about our users'experiences of the web has ever been as homegenous as we imagined

- creating ideal scenario is an edge case

We're developing for people like us; excluding a large group of people
we're also holding the web back.

### Smartphone penetration
global smartphone penetration is about 66% but that differs per country. The uk for example has 83%, The netherlands 79%, china 68..4% but india has 44%

This also differs when people earn less or more. The higher people's income is, the higher the chance is that they browse the web with their mobile browser.

1 in 6 U.S. adults is a smartphone-only Internet user

### Not all smarthones are equal
- Screen size 
- ram
- storage
- camera's
- processor speed
- android version
- cost

In the 2017 survey, smartphone users who fell into the lower income group experienced app errors 52% of the time!

Sometimes an accassibility solution has further consequences
- High contrast for example helps the visually impaired people but also people who look at the screen in bright sunlight.

### We try stuff, make mistakes, & learn from them

# Progressive enhancement
Progressive enhancement in a nutshell is: rising to the occasion
It is about improving the user experience. It is also about creating a resiliant experience.

## Graceful degradation

Focusses on modern browsers and created the ideal scenario, you could give older browsers feedback on having an old browser.

Progressive enhancement looks like graceful degredation.
Progressive enhancement will degrade gracefully.

Progressive enhancement is about starting with what matters and build out on that.

Progressive enhancement step by step:
1. Focus on what matters
2. Write it out, then read it back.
3. Look for semantics that support Step 1 & 2 
4. THink about how design can mprove comprehansion
5. Consider how your design choice impact the reading experience.
6. Think about the many different ways folds might interact
7. Map the potention experiences by for example; 
	1. Flow charts
		1. Does this browser support javascript, and what happens when it does or doesn't.
		2. etc...
8. Iterate on this approach to continue to refine this experience.





---

In a recent talk by Aaron Gustafson, a member of Microsoft's Progressive Enhancement team, he emphasized the importance of progressive enhancement in web design and development. Gustafson pointed out that the ever-evolving landscape of screen sizes, user needs, and devices has made it increasingly difficult for designers and developers to create optimal user experiences. This article will explore the key points of Gustafson's talk and discuss how progressive enhancement can help address these challenges.

## The Challenge of Evolving Screen Sizes

Web design and development have come a long way since the early days of fixed-size web pages designed for resolutions like 640 x 480 pixels. With the advent of smartphones, designers and developers had to adapt to new screen sizes, often resorting to media queries, adaptive layouts, and responsive design techniques. However, chasing screen sizes is a never-ending task, as Jaron Samuels, IT Manager at the National Council on Family Relations, noted that the number of screen resolutions detected among their visitors increased from 71 in 2008 to 1,062 in 2014.

## Beyond Screen Sizes: Varied Networks, Devices, and User Needs

In addition to screen sizes, designers and developers must also consider the many other factors that impact user experience, such as:

-   Different devices, including wearables, smart TVs, IoT devices, and virtual assistants
-   Varied interaction methods, like eye tracking, touch, mouse, keyboard, audio, and gamepad
-   Diverse network conditions and environments, from Wi-Fi and hardline connections to mobile networks in homes, buildings, vehicles, and airplanes

Moreover, designers and developers must recognize that their users have different needs and preferences, often shaped by factors like income, location, and the type of smartphone they use.

## Progressive Enhancement: A Solution for Inclusive Web Experiences

Progressive enhancement is a design philosophy that focuses on creating resilient and inclusive web experiences. Instead of designing for an ideal scenario, progressive enhancement starts with the most basic functionality and builds upon it to accommodate more advanced features and technologies.

Gustafson outlined the following steps for implementing progressive enhancement:

1.  Focus on what matters: the core content and functionality.
2.  Write out the content and read it back to ensure clarity and accessibility.
3.  Look for semantic markup that supports the content and functionality.
4.  Consider how design can improve comprehension and accessibility.
5.  Evaluate how design choices impact the reading experience.
6.  Think about the many different ways users might interact with the content.
7.  Map potential experiences using flowcharts, considering factors like browser support for JavaScript.
8.  Iterate on this approach to refine and optimize the user experience.

By adopting progressive enhancement, designers and developers can create web experiences that are not only resilient in the face of constantly changing technology but also inclusive of users with diverse needs and preferences. This approach ensures that the web remains accessible to all, regardless of their device, network, or personal circumstances.