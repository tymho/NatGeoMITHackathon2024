# Updated for 2024
This repo is a fork of the [original](https://github.com/cameronkruse/hacktheenvironment/tree/main) made by @cameronkruse. Edits were made as several software have updated, deprecated, or added to varying components of the project. Most notibly, the CV component now uses Picamera2 with OpenCV and Tensorflow Lite. Small changes were made to monitor setup to accomodate for the new Pi OS release. SSH is the recommended approach to interacting with the Pi. 
On the hardware side, the hardware setup is also reorganized to add more guidance. Instead of the original camera -> BrainCraft HAT flow. The order is now Fan -> Camera -> Display Module as recommended by Adafruit. One additional materia (2 x 20 Socket Riser Header) is also added.

For any issues, please use the Issues tab. I will get back to you in a reasonable window!

## Original README Below
# HackTheEnvironment

[@diegoleonbarido](https://github.com/diegoleonbarido) and I used the materials in this repo to run a three day hackathon for a group of high school students as a part of a summer program in Boston sponsored by Putney Student Travels. We've published them here for others to use and run similar events. If you want to use any of these materials for your event, feel free to fork this repo and customize for your needs. [The branch for the original event with team submissions is here.](https://github.com/cameronkruse/hacktheenvironment/tree/EndicottHack)

We wrote very little new code for this event, but contributed to an already existing body of work by making sure that there was an efficient and easy-to-follow workflow that could allow anyone to build an AI powered raspberry PI. The following links are the tutorials and the most important links that we used for inspiration; most code was directly taken from these:

* [Connecting Raspberry Pi via wifi](https://learn.adafruit.com/raspberry-pi-zero-creation/overview)
* [Connecting Camera](https://projects.raspberrypi.org/en/projects/getting-started-with-picamera)
* [Connecting BrainCraft HAT](https://learn.adafruit.com/adafruit-braincraft-hat-easy-machine-learning-for-raspberry-pi/overview)
* [Setting up Tensorflow Lite](https://learn.adafruit.com/running-tensorflow-lite-on-the-raspberry-pi-4/tensorflow-lite-2-setup)
* [Integrating Teachable Machine Models](https://learn.adafruit.com/teachable-machine-raspberry-pi-tensorflow-camera)

## Format
The event was run over 3 days. The first day was an educational day where we taught fundamental skills and introduced the premise of a hackathon. The second day was mostly spent building the Raspberry Pi camera systems and teams started building out their project ideas. The third day the students finished up their projects and presented their solutions. We had each team submit their final presentations and code to individual Google Drive folders, but you could also use Github repos.

## Resources
* [Ethical Technologist Pledge](./Ethical_Technologist_Pledge.pdf) - each student was required to sign this before the event
* [Schedule of Events](./Schedule.md) - This was loosely adhered to as we tried to match the students pace
* [Tutorial on how to build and set up the Raspberry Pi ML enabled camera systems](./ComputerVisionRaspberryPi_Tutorial.md) - Most of day two was spent following this tutorial
* [Hackathon Prompt](./Hackathon_Prompt.md) - A scenario and explanation of the challenge with rules and judging criteria
* [Educational Material](./Educational_Material) - Presentations shared with the students during educational sessions.


Feel free to reach out to me or [@diegoleonbarido](https://github.com/diegoleonbarido) with questions or comments! We hope you find this helpful.
