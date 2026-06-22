KinectBuzzCinder FULL SKELETON VISUAL

Replace your existing src/KinectBuzzCinderApp.cpp with this file.

Changes:
- Draws full Kinect v1 skeleton bones and joints
- Better vertical centering: visualScaleY=0.70, visualCenterY=0.40
- Adds glowing hand rings and an energy ball between hands
- Keeps MIDI mappings unchanged:
  CC74 cutoff, CC71 resonance, CC91 reverb, CC93 delay, CC7 energy/volume

Requirements:
- Cinder 0.9.3
- Kinect SDK 1.8
- loopMIDI port named KinectBuzz
- Linker: winmm.lib and Kinect10.lib
