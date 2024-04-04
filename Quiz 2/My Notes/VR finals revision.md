# History of XR
1957 Sensorama - 3D images, smells, sounds
1968 First HMD
2012 Oculus Rift DK1

# Milgram-Kishno' RV Continuum
Dimensions of RV Continuum
Extent of Real world knowledge: **Real world** modelled with increasing detail
Reproduction Fidelity: Increasing **quality of the display**
Extent of Presence: **Interaction** increasingly similar to reality
Coherence: Increasing immersiveness, flow

# Evaluating Immersive Experiences
- Explain Immersion as system/user properties
- Key dimensions of presence, flow and cybersickness
- how to employ different quantitative and qualitative user research methods to evaluate presence flow and cybersickness
- Explain role of affordances in immersive experiences
## Immersion from a System/User perspective
Systems perspective refer to the hardware of the device some qualities are
Wide FOV, 8k Resolution display, 6 DOF inside-out tracking
User or experiential perspective refers to how the users feel in the virtual environment
Higher Spatial presence, Higher place illusion, Lower cybersickness

## Famous Validated Questionnaires to use in user studies
TODO
Flow State Scale (FSS)

## Affordance
Ways to implement affordances are
Hand tracking that allows natural manipulation of objects
having objects with clear grooves for gripping
haptic feedback when an object correctly fits into place
highlighting interactive objects with subtle glow effects

# Development Tools
OpenXR
WebXR
Babylon.js
Unity
# Hardware & Software Components
- Describe common hardware components in XR devices
- Explain the image formation process in XR HMDs
- describe common software components in imersive applications
- describe architecture of a typical WebXR application

# Creating Virtual Environments
- 3D virtual environment with skybox and geometric primitives in WebXR
- implementing a simple GUI in XR application
- implement anchors to overlay 3D virtaul objects in camera video in WebXR
- Implement basic audio in WebXR applications
- Model-based vs image-based methods

Model-based approach
3D models with technical art expertise
Enables full interactive implementations

Image-based approach
360 photos/videos
more accessible, limited to static surroundings
Used for quick prototyping/design for story based immersive applications with limited need for interaction

# Interaction Mechanics
Viewpoint control, hand gestures, body gestures
Passive Interaction, Viewpoint control
Active Interaction, Hand  gestures
Both, active viewpoint control (look at object to x seconds to interact with it)

Artificial magical interaction - casting spells
Artificial augmented natural interaction - enhanced natural actions, grab from afar
Natural Interaction - natural actions

# Embodiment
Perception that a virtual body is one's own, often correlated to Presence
e.g. Users avoid touching fire due to high embodiment via realistic hand representation and precise tracking

# Implementing Interaction
## Behaviors
Predefined, reusable interactions
Common interactions like dragging, scaling, following
## Action Manager
Property changes triggered by pre-defined events
## Observables

