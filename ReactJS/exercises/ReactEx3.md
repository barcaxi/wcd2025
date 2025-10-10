# React.js Exercise 3 – React State


# Part 1 - ``ClickedButton`` Component 

1.	Create and test the ``ClickedButton`` component as shown in the slides/videos.  

	```javascript
	import { useState } from "react";

	function ClickedButton() {
	const [count, setCount] = useState(0);
	
	return (
		<>
		
		<button
			onClick={() => {
				setCount(count + 1);
			}}
		>
			Clicked: {count}
		</button>
		</>
	);
	}

	export default ClickedButton;

	```

	This is a simple demostration of the purpose of component _state_.  A change to state causes the component to be re-rendered.


	
<!-- 


## Part 2 - ``Clock`` Component
	
1.	Add and test this ``Clock`` component to your React project `src/Components` folder:

	```javascript
	import { useState } from "react";

	function Clock() {

		const [ date, setDate ]  = useState(new Date());    

		const tick = () => {
			setDate(new Date());
		}
		setInterval(tick,1000);
		
		return (
			<div>
			{date.toLocaleTimeString()}
			</div>
		);
	}
	
	export default Clock;

	```
	
	Notice how component state (date), behaviour (tick), and look (output) is encapsulated in one component.
    This is a good example of what a React component should be.


## Part 3 - ``Timer`` Component
	
1.	Create a new component called `Timer` in your React project `src/Components` folder.  

    The component should countdown from 10 to 0 (zero).
 -->
