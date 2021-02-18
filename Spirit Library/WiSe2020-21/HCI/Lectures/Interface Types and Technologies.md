## Interface Types and Technologies
___
### Intro. Start WIMP 'types'
- Command-based interfaces
	- steep learning curve, but efficient precise and fast
	- alternative to GUIs for visually impaired users
- WIMP and GUI
	- WIMP: windows, icons, menus, pointing device
	- GUI: same building blocks as WIMPS, but more varied
- What's the difference between an icon, an index and a symbol?
	- The level of similarity between the representation and the referent. It can be:
		- **icon**: similar (e.g., picture of file represents object file, picture of printer)
		- **index**: analogical (picture of scissors to represent 'cut', clouds to represent 'rain'), index points to something, metaphorical
		- **symbol**: arbitrary (use of an X to represent 'delete')
- What menu is best for small amounts of options and which is best for a lot of options?
	- Small: flat menus, large: expanding
- What's the most popular type of menu?
	- Cascading menus
- What are contextual menus?
	- They provide access to often-used commands that make sense in the context of current task
	- Good in terms of Fitts' Law
	- Discovered typically by accident, hide view of current action, may not be possible to fit everything in

### Multimedia, VR, Dashboard Visualization
- What's multimedia?
	- the combination of different media within a single interface with various forms of interactivity
- What's VR?
	- computer-generated graphical simulations providing the illusion of participation in a synthetic environment rather than external observation of such an environment
- Research and design issues related to VR
	- identify effective ways to navigate and interact
	- how best interact with abstract information
	- level of realism needed to engender a sense of present
	- how to prevent motion sickness
	- 'gorilla arm' problem - shoulder pain
	- lack of mechanoreceptive feedback
	- pointer/target misalignments impacting motor control
	- temporal misalignment
	- unnatural gesturing
	- efficient locomotion
- What is InfoViz?
	- Computer-generated interactive graphics of complex data
	- Amplifies human cognition, enabling users to see patterns, trends and amplifies anomalies in complex data
- What are dashboards?
	- shows screenshots of data updated over periods of time - to be read at a glance
	- they're not interactive and need to provide digestible and legible information for users
- they need to direct users' attention to anomalies and not be cluttered with information

### The Web, Consumer Electronics, Mobiles
- Websites now should be
	- aesthetically pleasing (distinctive? brand identity, fits with user base)
	- usable
	- easy to maintain
	- accommodated for the platform the website is being seen on
- Design implications for consumer electronics and appliances
	- They have interfaces for short interactions so they should be simple/easy to learn, have visibility of the system status, and decide on physical controls vs touch screen control
- What's gained and what's lost if controls of a toaster are replaced with an LCD screen?
	- Gained: less physical space, provide more information, more options
	- Lost: ease of use for visually impaired users, more complex, steeper learning curve
- Advantage of mobile devices
	- real time access to contextual information (scanning bar codes, QR codes, gaming, anytime learning, etc.)
- Things that require design effort regarding mobile phones
	- small screen and limited control space
	- privacy issues
	- usability and preferences vary (e.g., older users)
	- localized experiences
	- dealing with directions, hands free vs being a distractor

### Speech, Pen, and Touch Input
- Applications of speech/voice interfaces
	- timetable, travel planner, ticket purchase, navigators, call routing
	- supports people with disabilities (e.g., speech recognition, word processors, page scanners, web readers, home control systems)
- Advantages of pen input?
	- capitalizes on well-honed skills developed from childhood
	- quick and easy for annotating documents, sketching, etc.
	- intuitive way to integrate physical paper with digital information & services
- What's a problem with using a virtual keyboard opposed to a physical keyboard
	- Virtual keyboards sometimes don't have haptic feedback - it's easy to get off the button you want to press and accidentally hit another one (the swiping method of typing helped with this)
- What is touch offset?
	- Offset between the target on a mobile screen and where the finger actually touched. This can be useful in the design of mobile UIs (e.g., things in the corners may need to be bigger so it's easier to access with fingers)

### Mid-Air Gesture Interfaces
> Think of XBox Kinect, digital golf interfaces
- What are mid-air gesture interfaces?
	- Interfaces that may use camera recognition, sensors and computer vision techniques to track people's body, arm and hand gestures (e.g., XBox Kinect)
- Possible limitations or problems with the Kinect?
	- needs a lot of space to use - requires you to move furniture to be able to detect the users' full bodies
- Possible applications to gesture interfaces
	- Operation theater in hospital, distance physical therapy, museum exploration/playing/learning
- What is an exertion interface?
	- a form of gesture interface that uses user's physical exertion to engage them (e.g., a game with balls to hit the wall with)
- Research and design issues
	- how does the computer recognize and delineate (start/end) user's gestures?
	- Gestures vs unconscious gesticulation (accidentally doing a gesture but just talking with your hands)
	- What's intuitive memorable, ergonomic?
	- Control device vs hands free - what's better and more intuitive?
	- What can we actually do and support with this, that's interesting and valuable? How to design for these application scenarios?

### Haptic Interfaces
> Haptic = tactile feedback
- Examples of applications of vibrotactile feedback?
	- Vibration in a car seat to alert the driver that there's a car in the blind spot
	- Learning to play violin: vibrate when playing incorrectly
	- Learning to snowboard: a vibration to indicate where to shift their weight/where to turn
		- had to be adaptable to individual users because they could interpret the vibrations differently
	- games (e.g., VR boxing)
- Research and design issues
	- where to place actuators on the body/object
	- whether to use a single or sequence of touches
	- when to buzz and how intense of a buzz
	- how does the wearer feel it in different contexts?
	- how to use vibrotactile feedback creatively in new smartphones/smart watch apps? (e.g., slow tapping feels like water dropping to indicate it is about to rain, heavy tapping to indicate a thunderstorm is coming)

### Multimodal, Tangible Interfaces
- What is a multi-modal interface?
	- An interface with a combination of input/output modalities and multiplies how info is experienced through those different modalities (either simultaneously or alternatively)
		- speech and gesture
		- eye gaze and gesture
		- pen input and speech
- What is a tangible interface?
	- an interface with physical objects that are coupled with digital representations
		- sense of (manipulation of ) physical objects and feedback in digital or physical space
		- interplay of different devices and objects
		- no enforced sequence of action or modal interaction (unlike the 3 state model! see: [[Modeling User Interaction#Descriptive Models GOMS 3-state Interaction Bimanual Skills]])
		- intrinsically shareable
		- physical affordances and constraints can guide users
	- e.g., those devices that make plants into musical instruments (maybe?)
- Example of tangible interfaces
	- Illuminating clay: manipulating environment projected on clay
	- ReacTable: sound manipulation system using blocks
- Questions and areas for research
	- when is tangible better than virtual?
	- what is the extra value of the interface? why should it be tangible rather than just on a screen?
	- feel-good effect vs performance?
	- how to best combine tangible and virtual components or augmentation
	- influence of concrete materials (haptics, psychological association)
	- shareable interfaces
	- how can we escape limitations of dead matter? (shape-change interfaces)

### Augmented and Mixed Reality
> Not only seeing real world, but you see virtual elements as well (not only visual, but audio as well!)
- What's augmented reality?
	- virtual representations are superimposed/overlayed on physical devices and objects or their view (camera image)
	- the most established is handheld AR: using smartphones' display as a peephole
	- on mobile example: medical AR to project anatomy, X-Rays, etc. for education and practice
- What's mixed reality?
	- views of the real world are combined with views of a virtual environment
- Research questions
	- what kind of augmentation?
	- what kind of device?
	- ergonomic issues

### Wearables
> Started with head and eye wear mounted cameras, now there's jewelry, head-mounted caps, smart fabrics, shoes, jackets, etc.
> Choice of clothing is tied to identity, this extends to wearables which are a part of both the fashion industry and the electronics industry
- Applications of wearable technology
	- automatic diaries, tour guides, cycle indicators, fashion clothing, health & sport tracking, phone, professional clothing
- Requirements for wearables
	- comfortable
	- hygiene (washing)
	- usability (how controlled)
	- design/fashion
	- social acceptance and privacy
- Takeaways from Google Glass?
	- When designing a product, **both the problem space and the solution space** need to be considered
	- It was being pushed into the commercial space when it wasn't designed to solve any problems in that space, but later it was found to be useful with manufacturing because it had a reason to be of use and didn't break any norms of that space

### Robots, Brain-Computer Interaction and Shareable Interfaces
> Robots: originally for manufacturing and for exploration of dangerous environments, but now domesticated to help around the house, be companions and caretakers, and even work collaboratively and socially with humans
- What are minimalistic robots?
	- "physically embodied systems capable of enacting physical change in the world"
	- e.g., spoon that helps people with limited hand and arm movement
> BCIs work through detecting changes in the neural functioning in the brain to carry out tasks for the user
- What is a Brain-computer interface (BCI)?
	- an interface that provides a communication pathway between a person's brain waves and an external device such as a cursor on a screen
- What is a shareable interface?
	- a multi-user interface for flexible group collaboration
	- can provide multiple inputs and often allow simultaneous input
	- shared point of reference
	- e.g., large wall displays, tables, part of furniture

### Conclusion and Outlook
> Are computers natural? Will they ever be natural?
- What is a natural user interface?
	- refers to touch, gesture, tangible and voice
	- argument: same interaction mechanisms as with natural world