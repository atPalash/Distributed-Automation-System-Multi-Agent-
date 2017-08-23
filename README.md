# Multi-Agent System (Workstation and Work-pieces interacting to achieve the desired GOAL)

## Objective

The production system (physically located in Ri208, simulator of the system - http://escop.rd.tut.fi:3000) is composed of 12 work stations. The line makes mobile phones that can come in 729 variations (3 screen shapes * 3 colours * 3 keyboard shapes * 3 colours * 3 frame shapes * 3 colours). 10 workstations (WS2-WS6; WS8-WS12) are in charge of making mentioned frames, screens and keyboards. A product can be seen as a combination of a frame, a screen and a keyboard.
The line should be controlled using MAS (Multi-Agent System). Identifying what is an agent in the context of given production line, then implementing the agents using Node.js and demonstrate the approach by actually controlling the line.

As a system receives an order to make a mobile phone, the agents should negotiate between each other developing the way to make the phone and then executing actual production of the phone.

## Implementation
Each workstation and pallets were identified as agents. On reaching the start point of each workstation the pallet agent asks the workstation agent for the decision ie to go into production or by-pass it.
Each workstation has diffent capabilities some can load pallet, some can unload and others can make mobile of single color.

### video
please watch the video in the report file folder for explanation/demonstration:https://www.youtube.com/edit?o=U&video_id=J8FZJvHFlQM

