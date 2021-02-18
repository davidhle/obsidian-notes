## Modeling User Interaction
___
### Intro; descriptive methods: HTA
- What is a descriptive model?
	- a model that provides conceptual framework that simplifies a system, allows statements about likely characteristics. gives a basis for understanding, reflecting and reasoning about facts and interactions
- What is a predictive model?
	- a model that makes **educated guesses about the future** based on model of interaction (based on empirical knowledge), often predict performance
- What is hierarchical task analysis (HTA)?
	- a way to model user tasks by identifying main tasks for achieving a user goal, and breaking those tasks into sub tasks. usually focused on physical and observable actions
	- ![[Hierarchical Task Analysis.png]]
- What are the pros of HTAs?
	- you can compare designs based on user tasks and it supports understanding at varying levels of abstraction
- What are the cons of HTAs?
	- It is difficult to represent complex real-world tasks
	- can't model overlapping, parallel tasks or interruptions
	- results in inflexible workflow if implemented too directly

### Descriptive Models (GOMS, 3-state Interaction, Bimanual Skills)
- What is the GOMS model?
	- a descriptive model that splits user tasks into goals that are achieved by solving sub goals in a divide and conquer fashion, and has more of a focus on cognitive aspects than HTA
	- Goals
		- Verbal description of what a user wants to accomplish at various levels of abstraction or complexity
	- Operators
		- Possible basic actions in the system (various levels of abstraction possible : sub goals, keystrokes, etc.)
	- Methods
		- sequences of operators that achieve a goal
	- Selection rules
		- rules that define when a user employs which method
- What is the 3 state model?
	- A method that describes graphical input (i.e., mice, button presses, etc.)
	- ![[3 State Model.png]]
- What is Guiard's Model of Bimanual skills?
	- Tasks are asymmetrical with regard to left and right hands. This model identifies the role of the non dominant and dominant hands 
	- The non dominant guides the dominant hand and does more coarse movements, whereas the dominant/preferred hand performs fine/detailed actions. Non-dominant hand creates a frame of reference for dominant one (think of writing/drawing, putting thread in needle)
	- Application: can use when designing interactions for systems with bimanual interactions like VR
### Fitts' Law
- What is Fitts' Law?
	- It's a robust predictive model of human psychomotor (brain and muscles involved) behavior that predicts movement time for rapid, aimed pointing tasks. It describes movement time in terms of distance & size of target and device. Purely ergonomic, doesn't take into account cognitive aspects of user behavior.
	- ID (index of difficulty) predicts achievable speed of selecting target
	- The time to acquire a target is a function of the **distance** to and **size** of the target and depends on the particular **pointing system** 
	- $MT = a + b\log_{2} \left ( 1 + \frac{D}{W}\right )$
		- MT: movement time
		- a and b: constants dependent on the pointing system (in seconds) - a is start/stop time and b is inherent speed
		- D: distance to the target area
		- W: width of the target
		- $ID = \log_{2} \left ( 1 + \frac{D}{W}\right )$ - describes difficulty of task independent of device
	
### Fitts' Law for new devices; Implications for Interface Design
- What might Fitts' Law tell us about interface design?
	- Bigger Buttons are easier to hit - use them for buttons that are more common to press
	- Use cursor location for pop up menus to minimize travel distance
	- Use edges and corners of screen - "infinite height and width", cursor stops no matter the speed (think of mac menus on top of screen)
- Is pointing on a touchscreen the same as a screen with a mouse?
	- No, because the mouse stops at the edge, a touch screen is a normal target for Fitts' law
- What is the most optimal menu type according to Fitts' Law?
	- Pie menus because similarly to pop up menus, it pops up where the mouse is, and all of the options are at an equal distance from the mouse. It also helps build muscle memory. BUT labeling is difficult and uses more screen space
- What is the Steering Law?
	- A law that models movement time of a pointer through a 2D tunnel to acquire a target
	- $MT = a + b \frac{D}{W}$
	- ID is linear, not logarithmic, steering is more difficult than pointing!
- What's an example of Steering Law in Practice?
	- Nested menus like in Spotify. It's very easy to accidentally go out of the tunnel which would make the menu disappear
- What's the idea of a crossing menu?
	- You cross an item to select it, which allows you to easily select multiple things without having to slow down. Based on steering and crossing, is an optimization on Fitts' Law, and is ideal for pen and finger interactions

### Keystroke Level Model (KLM)
> If asked to calculate a KLM time, don't forget reaction times for pages to load, hand from keyboard to mouse
- What is the KLM and how does it work?
	- A predictive model that predicts how much time it takes to execute a task. It's essentially a simplified version of GOMS
	- The execution of a task is decomposed into primitive operators and each operator is assigned a duration of how long it would take a user to perform it
		- Physical motor operators: pressing a button, pointing, drawing a line, etc.
		- Mental operator: preparing for a physical action
		- System response operator: user waits for the system to do something
	- ![[KLM.png]]
- What if you want to use KLM on a different system than the traditional mouse and keyboard?
	- Change and maybe add operators to fit the interactions possible by the system's environment (e.g., G for gesture: time needed for system that uses gestures such as rotating, shaking, drawing numbers in the air)
- What is KLM good for?
	- Helps us identify where common tasks take too long to consist of too many statements, where to simplify. It can also show advantages of new interaction techniques.
- What are advantages of KLM?
	- Quick and easy to apply and prepare
	- Quick to analyze
	- Precise to interpret
	- Easy to convey to management
- What are disadvantages of KLM?
	- Only operators on keystroke-level, so it focuses on very low level tasks
	- No multiple goals
	- Strictly sequential

### Recap of Traditional Modeling
- What are some downsides to predictive models?
	- Only work for well defined (limited, simple) routine cognitive tasks (out of context)
	- Assumes expert users that know the steps
	- Does not consider slips or errors, fatigue, social surroundings
	- Need to adapt for special user groups with different performance/cognitive behavior
	- Need to empirically determine variables for new interaction methods and styles
