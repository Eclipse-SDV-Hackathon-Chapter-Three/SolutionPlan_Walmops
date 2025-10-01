# **Walmpos - SDV Coordinated Mobility**
## Develping an efficiency oriented coordination solution 

## Team Name / Tagline  
Walmops (it's a long story)

# 1. Team Introduction

In Walmops, we came to the [Eclipse SDV Hackathon](https://www.eclipse-foundation.events/event/SDV-Hackathon-Chapter3/summary) with an idea: solve the time lost in traffic jams cased by the uncoordinated acceleration and deceleration of vehicles.

This rapresents an actual future proof application, when every OEM will be SDV based, these orchestration will be applicable and efficient.


## Team Members  
| Name | GitHub Handle | Role(s) |
|-------|---------------|---------|
| Daniele      |  daniSera             | Hacker        |
| Nadezhda      | mishchenk0              | Hacker        |
| Vladimir      | mircov693              | Hacker        |
| Alex | alexherg | Hacker |
| Eike | eikelang-vm | Hacker |

## Challenge  
The team partecipated in the SDV_Lab challenge.

## Core Idea  

Traffic jams are sometimes literally “phantom” shock waves, caused not by a physical obstacle but by unccordinated maneuvers that force drivers to slow down and accelerate repeatedly. 

Expecially at red lights, these uncoordinated actions between vehicles cause two major outcomes:

- Less vehicle pass through the red light
- More time spent in line on average

Given the open source nature of the Eclipse SDV solution, we immagine a future where every single OEM will ship on their vehicles a coordination workload to manage the vehicles.

The core idea is to expose the informations between vehicles, and coordinate the executions to obtain a syncronized movement: ** yep you got it right, we want to create a train of different OEM vehicles!! 🚗🚗🚗**

## 🛠 Key Features

### 1. Role Declaration

In this solution, each vehicle will be able to determine if its role is a **LEADER** role or a **FOLLOWER** role. Based on information coming from the camera sensor and the radar sensor, a car will understand if it is at the beginnign of a line or is following a vehicle.

This will be crucial to determine the publishers and the subscribers to the mesh messages.

### 2. Action Execution

Once the roles will be defined, the vehicles will enter a **TRAIN MODE*, waiting for the green light to appear. Once the 
vehicles will be free to move, the motion will be syncronized.

The **LEADER** will publish the trottle inputs, the **FOLLOWER** will read the trottle inputs and apply in its own control module, obtaining a seameless train operation.






---

# 2. How Do You Work

Since we are partecipating in a Hackathon, we can simply answer with **we will improvise!** Newertheless, here are some steps htat we will follow.

## Development Process

### Planning & Tracking  
We'll figure that out once we have a clearer understanding of what we want to do

### Quality Assurance  
Manual testing only, unless we come across some very low-hanging fruit

## Communication  
We are a multicultural team so we will speak 3 leanguages: **Russian**, **German** and **English**.

The following hierarchy will be followed:
1. **ENGLISH** - It will be used for the whole team comunication, important milestones and accomplishments will be communicated, but also the information for the development will be expressed.
2. **GERMAN** - It will be used during development phases, because it the most direct leanguage.
3. **RUSSIAN** - When nothing works, blyat.

Joke aside, it is an hackathon, we will try to keep a organized comunication but it is going to be hard.

## Decision Making  
Decisions will be taken as a collective group, based on the suggestion provided by the coaches. It is a 100% democracy based team, so the decisions will be taken accordingly.

