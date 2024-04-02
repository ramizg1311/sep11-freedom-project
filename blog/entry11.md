# Entry 11
##### 4/2/24

Since immersing myself into the documentation of kaboom.js, I've implemented kaboom via CDN and have begun experimenting by doing small things with my code, like trying to change my sprite. For example...
<img src="https://images.rawpixel.com/image_800/cHJpdmF0ZS9zdGF0aWMvaW1hZ2Uvd2Vic2l0ZS8yMDIyLTA0L2xyL3B4MTI5MzM2OS1pbWFnZS1rejJlOXI3OS5qcGc.jpg" alt="My spider-man sprite! (that i can use because of creative common licences)"/>
Here's my spider-man sprite! Unlike regular sprites, I, his creator, will plan on giving him the ability to "leap forward" (or "web sling" forward) by utilizing the following, paraphrased code:

```
LEAPFORCE = 1000 // combination of moving to the 'X' + jumping

function leap() {
		if (player.isGrounded()) {
			player.jump('JUMP_FORCE' + 'SPEED')
		}
	}

onKeyPress("F", () => {
    spidey.leap()
})
```
I'm a bit behind when it comes to progress, but I plan on ramping it up in terms of finalizing what I want my freedom project to be.

[Previous](entry10.md)

[Home](../README.md)