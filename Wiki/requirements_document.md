# Requirements Document

## Contents

* [Introduction](#introduction)
* [Technical Requirements](#technical_requirements)
* [Project Requirements](#project_requirements)
* [Future V2.0 Requirements](#future-v20-requirements)
* [Glossary](#glossary)

## Introduction

The requirements list matches up to the Initial Questions in step one of the Systems Engineering process as shown below. Each requirement is labeled with FHPR (Far Horizons Project Requirement), followed by the number of the [initial question](initial_questions.md) that the requirement corresponds to, followed by a dot and then the ID number of the requirement.

* ***FHPR 1.x*** - Why are we making this?
* ***FHPR 2.x*** - Who is this for?
* ***FHPR 3.x*** - How will this be used?
* ***FHPR 4.x*** - What features does it need to have (now)?
* ***FHPR 5.x*** - What features does it need to have (later)?
* ***FHPR 6.x*** - What are the legacy requirements?
* ***FHPR 7.x*** - Who's going to build this?
* ***FHPR 8.x*** - How many do we want to make?
* ***FHPR 9.x*** - What is the budget?
* ***FHPR 10.x*** - What is the timeline?
* ***FHPR 11.x*** - What waste products will be produced by the manufacture and/or operation of this?

## Technical Requirements

Technical requirements are those requirements which include measurable performance values. Each technical requirement should be verified through testing to ensure the design meets the requirement.

* ***FHPR 3.1*** The HAB must be able to carry scientific and engineering payloads to a "near space environment" and return the payloads safely.
    * ***FHPR 3.1.1*** Individual modules must weigh 6 lbs or less.
    * ***FHPR 3.1.2*** Total launch weight must be 12 lbs or less.
* ***FHPR 3.2*** The HAB must be able to withstand the near space environment.
    * ***FHPR 3.2.1*** Must be able to operate at a pressure 0.01 atm.
    * ***FHPR 3.2.2*** Must be able to operate at radiation levels of up to 60x that at ground level.
    * ***FHPR 3.2.3*** Must be able to operate at -60 C.
* ***FHPR 3.3*** The HAB electronics must be able to run for a minimum of 2 hours including 1 hour at altitude (these times are subject to individual mission plans).

* ***FHPR 4.1*** The HAB will carry payloads to altitudes between 90k ft and 100k ft.
* ***FHPR 4.4*** The HAB will include a descent system to provide a soft landing (max landing speed of 25 mph).

* ***FHPR 6.1*** The design and operation of the HAB shall comply with [FAR 101](https://www.ecfr.gov/cgi-bin/text-idx?rgn=div5&node=14:2.0.1.3.15).

## Project Requirements

Project requirements are the remaining requirements which are not tied to specific performance values.

* ***FHPR 2.1*** The HAB must be well documented so as to meet the needs of open source spaceflight designers who will design and build High Altitude Balloons (at Adler and elsewhere).
* ***FHPR 2.2*** The HAB documentation and procedures must be complete enough for Adler operators, students, educators, and Makers who want to bring near space missions into the classroom, and anyone else interested in running near space missions.
* ***FHPR 2.3*** The HAB documentation must cover the the development, setup, launch, tracking, and recovery of the HAB.

* ***FHPR 4.2*** The HAB documentation shall include safety guidelines for launch and recovery.
* ***FHPR 4.3*** The HAB will broadcast a tracking signal to facilitate recovery.

* ***FHPR 7.1*** All HAB design documentation must be open and complete enough so that anyone, without necessarily a technical education in high altitude ballooning or engineering, would be able to build and operate the HAB.

* ***FHPR 8.1*** The design and documentation of the HAB must enable the completion and operation of at least one HAB by a third-party.

* ***FHPR 9.1*** The cost of the first third-party operational HAB must not exceed $300 excluding "consumables" and tools.

* ***FHPR 10.1*** The build schedule for the HAB should be between 4 and 5 weeks from project commitment to launch.

* ***FHPR 11.1*** Electronic waste items, including batteries (lithium and others) and circuit boards, must be disposed of according to all local, state, and federal guidelines.
* ***FHPR 11.2*** If the structures of the HAB are damaged beyond repair during operation, proper disposal/recycling guidelines must be followed for the materials used in its construction.
* ***FHPR 11.3*** Wherever possible, the HAB design should make it as easy as possible to replace components which are consumable or relatively easy to damage.

## Future V2.0 Requirements

These are for reference only so that future features can be accommodated in the current design where practical.

Version 2.0 and beyond:

* ***FHPR 5.1*** Implement advanced tracking and recovery systems used by Adler (redundant APRS transmitters/receivers and cut down unit)
* ***FHPR 5.2*** Controlled descent system (guided landings using parafoil/air-ram kite to either hit or avoid landing sites)
* ***FHPR 5.3*** Live two-way telemetry (or command & control) and the ability to receive live experiment and operations data
* ***FHPR 5.4*** Stabilized platform system (Adler is making progress on this one)
* ***FHPR 5.5*** Alternative balloon configurations (zero-pressure, super-pressure balloons)
* ***FHPR 5.6*** Alternate lift gasses (Adler uses helium right now)
* ***FHPR 5.7*** A structure to hold the balloon during filling operations and to automatically stop the filling operation for the desired lift

## Glossary

* _Cut Down Unit_ - Device for detaching the balloon envelop from the flight vehicle to prevent unwanted interactions with the descent control system (often a parachute)
* _FHPR_ - Far Horizons Project Requirement
* _HAB_ - High Altitude Balloon
