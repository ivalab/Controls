+++
title = "IVALab Controls Research"
+++

Our research on this front stems from recent research related to
Adaptive Control.  Neuro-adaptive control historically involved a
fixed network structure whose parametric values (or weights) evolved.
However, the machine learning community has devised many schemes for
data-driven creation of equivalent neural network structures. Our
question was: how could machine learning theory and adaptive control
theory be united in order to create a truly adaptive system from zero
knowledge?  Here zero knowledge means that the network starts with no
nodes (e.g., no activation function/basis functions, however you would
like to call it). The data-driven, machine learning module builds up the
network as data is collected, while the adaptive control component
optimizes the network parameters (weights) based on the closed-loop
dynamics of the system and the model reference tracking error.

Traditional machine learning has often emphasized high accuracy
irrespective of the time cost of the offline or initial model training,
followed by modest demands regarding real-time operation, which do not
get close to control feedback rates (which are in tens of milliseconds
or lower). Consequently, a fully data-driven approach following standard
ML would not be real-time operable.  Employing nice research from about
a decade ago on kernel machines or Gaussian processes for robotics, we
established a way to bound the size of the network so that its
computational footprint could be upper bounded.  This involved modifying
the network structure by replacing stale basis elements with better ones
as the system evolved within the state space. Importantly, the
integration of analytical tools from machine learning and from control
theory led to a Lyapunov proof on the convergence of the method.  The
technique could arguably be considered one of the first methods to wed
machine learning and control, and have an attendant stability proof.
Prior to this learning in robotics and control was purely empirical.
Successful application of the technique was evidence in favor of the
technique. 

Since then we have slowly been exploring the landscape of learning and
adaptation in control with the aim of understanding just how we can
arrive at a simple but potentially general approach to online adaptation
for ensuring stabilization of uncertain control systems.


### Investigators Involved

- [Patricio A. Vela](http://pvela.gatech.edu)
- [Hassan Kingravi](http://hassanakingravi.com/)
  ([Linkedin](https://www.linkedin.com/in/hassan-kingravi-6040824))

#### Former Investigators

- Vahid Azimi
  ([Linkedin](https://www.linkedin.com/in/vahid-azimi-56118362))

### Collaborators 

##### Current Collaborators

- [Aaron Ames](http://www.bipedalrobotics.com/)

##### Former Collaborators
- [Girish Chowdhary](https://ece.illinois.edu/directory/profile/girishc)
- [Jonathan How](https://aeroastro.mit.edu/jonathan-how)
- [Dan Goldman](http://crablab.gatech.edu/)

