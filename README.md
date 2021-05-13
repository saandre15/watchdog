# watchdog
Deep learning dog monitoring software for commercial facility and personal usage.

## Goal
* **Personal**: Smart monitoring software that alerts the dog owner when the dog is injured or doing something that it isn't suppose to do.
* **Commerical**: The current goal of this software is not to completely automate the kernel tech job, but to allow them to independently manage more dog at a time. The eventual goal is to not only inform people, but to enact decisions based off the given circumstances. The development of smart dog boarding, daycare, and grooming facilties product that integrates with around this software is the end goal of this software. Smart facility ideas such as smart waterjets that sprays water at dogs that are about to fight would be an example of such ideals.

## Features
* Identifies the breed of the dog using video processing
* Track dog location using camera, microphone, and RFID technology
* Plug and play to any websocket streams
* Uses microphones to detect dog's distress/anxiety levels/frequency [wimpering] and sends a notification above a certain threshold
* Uses web camera to detect injured dog [Wound licking, visible bleeding, limping, and etc] and sends notification
* Estimates the time the dog has been outside and sends an notification above a certain time limit
* Detects if the dog has done its business outside and can go inside
* Sends a notification when a probable agression/fight is about to occur.
* Identifies when the dog is doing something it not suppose to be doing such as eating out of the trash and so on.
* Integrates with the PetExec API
* Integrates with RFID chipset

## Training Data Used
* Dog Boarding, Daycare, and Grooming Salons [See participating companies](https://github.com/saandre15/watchdog/blob/main/PARTICPATION.md)
* Youtube, Vimeo, and etc Videos

## Server Specs Used
* 1x On-Site w/ GTX 1080 16 GB RAM 4 Cores
* 1x On-Site w/ NO GPU 64 GB RAM 24 Cores
