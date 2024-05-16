# eureka-to-human
This repository tracks the progress of potentially using eureka to train a task in simulation, port that task to a physical robot, then port that task to a Neuralinked individual. This would allow the training of any skill in simulation to be moved to a human which would be mechanically turked into performing tasks they have never known how to do.

I want this technology to spread to everyone in the world. I want this to promote human growth and capability. Bamboo spreads, grows fast, and grows tall, hence the name.

## Step 1: Leveraging Eureka as in prior works:
Eureka was used to train a robotic dog to move during a simulation. The results are detailed in this following article: https://interestingengineering.com/innovation/nvidia-robot-yoga-ball-balance

The first step would be to recreate this work - use Eureka to train a robot to do a task. 
Eureka is detailed in the following: https://eureka-research.github.io

## Step 2: Port Eureka to a robotic form
The second step in this process is to move the trained model from Eureka to a robotic form. This proves that the code is useable in a robotic form. Imagine training in Eureka and porting to Spot (which has a public sdk: https://dev.bostondynamics.com/docs/protos/readme). 
This process was detailed in the following article: https://interestingengineering.com/innovation/nvidia-robot-yoga-ball-balance

## Step 3: Porting the code to a Neuralinked animal
In this step, a Neuralinked animal would be mechanically turked to move based upon inputs. The neuralink would need to be attached to locations of the brain that control muscular movement. Fine-grained movement would need to be controlled and translated to some sort of API. From which the task that was trained in simulation would be used to train the human or animal. 

Rather than the Neuralink reading the positions of joints as in the following clip, the movement would be written to by sending a physical voltage to the area of the brain associated with stimulating the muscles that control that movement. See the video clip below:

https://youtu.be/m5TORNl_jgg?t=39

This limiting factor for this work is step 3 - I believe it is possible to send a signal to the brain to move an animal's physical appendages, but it is unknown publicly if this is done or, if it is, to what degree this is acheived. Is there an API? Is there an interface that allows the control such as in the following clip? 

https://www.google.com/search?q=black+widow+pig+scene+breathing&safe=active&client=safari&sca_esv=697ef796fdf142b1&rls=en&ei=80VFZsqENvuCwbkPrZW58AY&ved=0ahUKEwiKypK16JCGAxV7QTABHa1KDm4Q4dUDCA8&uact=5&oq=black+widow+pig+scene+breathing&gs_lp=Egxnd3Mtd2l6LXNlcnAiH2JsYWNrIHdpZG93IHBpZyBzY2VuZSBicmVhdGhpbmdImxdQyg1Y1RZwAngBkAEAmAFkoAGRBqoBAzguMbgBA8gBAPgBAZgCBqAC-QLCAgoQABiwAxjWBBhHwgIGEAAYFhgewgILEAAYgAQYhgMYigXCAgUQIRigAcICBRAhGJ8FmAMAiAYBkAYIkgcDNC4yoAfiEA&sclient=gws-wiz-serp#fpstate=ive&vld=cid:2c0cd745,vid:fWO9Lw4Z48E,st:0

