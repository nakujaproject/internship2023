# RESEARCH ON DUAL PARACHUTE
The dual parachute deployment technique in rocket design involves the use of two parachutes in the recovery system of a rocket. Dual deployments addresses two main issues that would otherwise lead to extensive damage to our electronics or complete loss of our rocket. 

> These problems include:
> 
> - Initial deployment at high speed (usually because the motor delay is either chosen incorrectly or does not perform as expected and the rocket still moves fast when the ejection charge fires)
> - High altitude parachute deployment that results in long drift times and thus difficult recovery of a landed rocket.

The primary parachute, also called a drogue chute, is typically deployed first at **apogee** and is designed to slow the descent of the rocket and bring it to a stable descent rate. The secondary or reserve parachute, is typically deployed if the primary parachute fails, or if the rocket needs to be brought down more slowly or at a specific location.

> The advantage is that the rocket falls fast for most of the descent and does not drift very far.
>
>> The primary parachute is usally smaller whil the secondary chute is larger and is ejected at lower altitude.


## PRINCIPLE OF OPERATION
The control altimeter works by sensinsing the altitude of the rocket and then sending a charge at two different ejection charges at the apropriate times i.e at apogee and at some distance from the ground.

> While the drogue chute brings down the rocket quickly, the electronic payload is still sensing the altitude of the rocket. When it descends to a pre-programmed height (which you control), it then triggers a second time. 
[The first event, deployment of the drogue chute](https://westrocketry.com/articles/DualDeploy/dualevent1.jpg)
[The second event, deployment of main chute](https://westrocketry.com/articles/DualDeploy/dualevent2.jpg)
>
> Since the rocket is now closer to the ground, the wind really doesn't have the time to push it downrange too far. So it lands slowly, but much closer to the launch pad. That means you don't have to walk very far to retrieve your rocket.

In some cases, both the primary and secondary parachute can be deployed simultaneously, this is known as tandem or multi-point deployment. This allows for more control over the descent rate and landing location of the rocket.

The use of dual or multiple parachutes can increase the chances of a successful recovery of the rocket and its payload, and it is a widely used technique in rocketry.

[Reference here](https://www.apogeerockets.com/Intro-to-Dual-Deployment)

### REQUIREMNETS FOR DUAL DEPLOYMENT
We primarily need a dual deployment electronics bay with a capability of atleast two pyrocharges. The selection may be categorised into:
- Flight computers 
- Altimeters
- Ejection charge (black powder, pyrodex)

[Reference here](https://www.apogeerockets.com/Electronics_Payloads/Dual-Deployment)

##### There are three basic types of deployment triggers:

* Dual Event Altimeter; Altimeter is a device that continuously measures atmospheric pressure. The altitude of the rocket is immeditatelly computed from the difference of pressure at the ground level (as sampled during altimeter activation) and currently measured pressure. 
> Dual Event Altimeter is an altimeter with some additional functionality. First of all, it is able to detect apogee and "throw-a-switch" when the apogee is detected (this can be used to fire a drogue parachute ejection charge). 
>
> Second, the dual event altimeter will continue to monitor the altitude even during the descent and can "throw-another-switch" when a predetermined altitude is reached (and thus fire the main parachute ejection charge). Most of the dual event altimeters also record the graph of altitude vs. time for the whole duration of flight.
* Dual Event Accelerometer; Accelerometer is a device that continuously measures acceleration (G's). It also computes instant speeds of a moving rocket and detects an apogee as a point of zero speed. Just like a dual event  altimeter, dual event accelerometer  it is capable of "throwing a switch" at both an apogee and a preset altitude.
* Timers; Timer is a device that can "throw a switch" after certain time after the liftoff. Timers are usually single event devices (can throw only one switch). Timers cannot detect apogee so their use is generally limited to a deployment of the main parachute only (or other functions that do not require apogee detection).

[Reference here](https://westrocketry.com/articles/DualDeploy/DualDeployment.html)

The choice of these said components affects the ease of deployment and control emmensely. The amount of charge will primarily be determined by how much volume inside the rocket needs to be pressurized to provide enough kick to blow the nose cone off and eject the chute out of the rocket.


#### CONCLUSION ON ITS FEASIBILITY
Having dual parachutes in a rocket is a feasible design option. The use of multiple parachutes can provide redundancy in the event that one fails to deploy or malfunction. This can increase the chances of a successful recovery of the rocket and its payload. 

Additionally, dual parachutes can also be used to control the descent rate and landing location of the rocket. However, the implementation of dual parachutes will also depend on the size, weight, and cost constraints of the rocket.

It is therefore, reasonable to conclude that for a successful recovery of our entire rocket, the dual deployment is the most accurate and feasible means of chute deployent.

