# Ringworld Perspective Test (Halo-Inspired)

## Prompt
A black-and-white ink illustration, parodying the 2001 Halo: Combat Evolved cover, drawn in the style of 1950s science fiction artwork. The armored protagonist is standing on the surface of a massive ringworld, facing the viewer. The camera is positioned at eye level, looking outward from the surface. The ring’s curve should rise into the background behind the character, suggesting immense scale and perspective distortion.

## Result
![Ringworld perspective test](https://github.com/Remshard/vision-model-failures/blob/main/halo-ringworld-perspective.png?raw=true)

## Evaluation
Despite clear prompt instructions for a first-person perspective standing on the ringworld, the model rendered a composition where the ring floats behind the figure—similar to a conceptual backdrop—rather than as a continuous ground plane beneath and behind the subject.

There is no curvature of terrain underfoot, no distortion consistent with standing on a curved megastructure, and no attempt at aligning vanishing lines from the viewer’s perspective. The output matches a learned layout (poster-style) rather than a physically coherent space.

## Takeaway
The model demonstrates difficulty reconciling prompt constraints involving viewpoint, surface continuity, and horizon curvature. This test reveals limitations in spatial reasoning when prompts imply geometric consistency beyond pattern recognition. This inspired a follow-up prompt involving a hamster running on a wheel, viewed from a similarly constrained geometric perspective, an inch from its face, designed to further test the model's ability to construct the illusion of depth and maintain coherent 3D spatial logic from a grounded camera viewpoint.

In layman’s terms, the model appears to compose a 2D subject against a 2D backdrop, like stacking flat cutouts on a green screen, instead of simulating a scene with depth. This suggests it may be reasoning within an X-Y plane, with limited capacity to construct or represent a Z-axis for depth or perspective alignment.
