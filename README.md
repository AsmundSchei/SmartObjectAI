# Smart object AI template 
Smart object AI template for Unreal Engine 5


This is a project intended to make a AI that can select goals based on its current situation. Its heavly inspired by F.E.A.R.s goal oriented action planning AI
system. It uses smart object actors to trigger events like playing a animation. This can be tweaked into more interesting stuff for different use cases.
You can have a look on my Twitter account for more progress https://twitter.com/AsmundSchei/status/1516965728662040578

![image](https://user-images.githubusercontent.com/2607194/164281029-70a04e75-c65c-4369-9adc-a0778b315820.png)




# Known bugs:


* Alot of nodes is outdated, as they updated the SmartObject system for  newer versions since the first commit (might not work properly)
* AI using smart object actor triggers animations multiple times
* Floor material needs re-adjusting, use these values: U tiling: -33,184689 V tiling: −38,202377 (In the text coord node)



![Capture](https://user-images.githubusercontent.com/2607194/178989418-29ed8d5a-b922-43b5-a22d-2a07c44eb04c.PNG)



```diff
Keys:
* 1: Spawns the gun
* Left mouse button: Shoot
* Right mouse button: Aim
* Q/E: Lean left or right
* Left shift: Sprint
* Left ctrl: Crouch
* R: Reload
```


Unreal version: 5.0.3.
Size: 2GB 













