# Drone Subproject
## Parts and premise
The goal of this subproject within the VRwaltzLab is to make a simple interactive experience with as little gameplay mechanics as needed to excite users about macroscopic haptic feedback.
The Project has 3 significant layers from a code perspective each will get a repository: the experience layer, the drone layer, and the module layer.
The Experience layer needs to basically define a toy/tool the user will play/interact with.
The Drone layer needs to take the force and torque vectors requested by the experience and combine them with counteracting the drone's weight to produce a target for an inverse kinematics problem which needs to then be solved quickly.
The Module layer then needs to take the desired force vectors and attempt to produce them with precision knowing pressure and temperature, and battery voltage.
## Drone vs Flywheels vs Suit vs Robot
A common question this project has gotten is why a drone over a more traditional bodysuit? A less common question is why not flywheels instead? Another less common question is why not a dance robot?
### Cost:
Of these three techniques, I am under the impression that for a DIY prototype, a drone will be the lowest cost for my application. 
I don't know of any cheaper Commercial Off the Shelf parts for flywheels other than satellites, and satellite tech is expensive.
The amount of motors for a suit or robot exceed those for a drone, because you have to have more than you degrees of freedom, also the strength and weight of those motors are inappropriate for my application.-Alex
### Suit Downsides
#### Human body variance
Human bodies vary in size over time and population. While some people might forget how bodies vary via natural processes, a good designer shouldn't. In order for a suit to work for an entire childhood, It would need to be incredibly dynamic
In contrast, a drone can separate the macroscopic force problem from the body specificity problem via an adaptor/mounting point.
#### Suit is hardest version
Because the suit needs to move around the person and contain the person, it roughly becomes an exoskeleton problem which is famously expensive.
#### Robot partner

### Flywheel Downsides
#### Flywheels produce Torque not Force:
In any closed system, you can only get net torques not forces. Thus flywheels can't do net torques. In order to feel torques, one might have to do some crazy historesis scheme in order to "feel" a net force.
#### Flywheels have high inertia:
In order to produce the torque desired, flywheels use changes in inertia to create impulses. While those impulses create real torque or angular momentum, they come from having inertia there.
Its hard to move something that has a lot of active inertia.
### Drone downsides:
#### Noise:
Drones are loud, but this is a problem being worked on actively.
#### Hair:
Drones could potentially tangle with and rip out hair. This safety hazard needs to be known about, and workaround's are not yet visible.
#### Missle behaviour:
A Drone disconnected from a user on a set force directive would accelerate until all forces are equal. The initial plan is a killswitch strap.
#### Air moves loose things:
UH, no plan right now for that.
