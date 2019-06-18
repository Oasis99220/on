# Official Requirements Document

Authors: Costamagna, Davi, Di Chiara, Fenoglio, Ferrazzano

Date: 10/06/2019

Version: 0.0.1

# Contents
- [Abstract](#abstract)
- [Stakeholders](#stakeholders)
- [Context Diagram and interfaces](#context-diagram-and-interfaces)
	+ [Context Diagram](#context-diagram)
	+ [Interfaces](#interfaces) 
	
- [Stories and personas](#stories-and-personas)
- [Functional and non functional requirements](#functional-and-non-functional-requirements)
	+ [Functional Requirements](#functional-requirements)
	+ [Non functional requirements](#non-functional-requirements)
- [Use case diagram and use cases](#use-case-diagram-and-use-cases)
	+ [Use case diagram](#use-case-diagram)
	+ [Use cases](#use-cases)
	+ [Relevant scenarios](#relevant-scenarios)


# Abstract

In a workshop to train staff the new arrivals are joined by trained staff, so production is slowed down. To avoid this it was decided to train staff using augmented reality by creating a special program that recreates the workshop


# Stakeholders

| Stakeholder name  | Description | 
| Administrator | Who create the project |
| User | Use  the device to learn how to behave in the workshop | 

## Interfaces
| Actor | Logical Interface | Physical Interface  |
| Administrator |GUI| Keyboard, mouse, computer, screen |
| User | GUI | keyboard, mouse, computer, screen |


# Stories and personas

john is 20 years old and has just been hired and is at his first working experience, through the staff training program he has learned to use the machinery and how to moves into the workshop.

# Functional and non functional requirements

## Functional Requirements

| ID        | Description  |
|  FR1 | Computer |
|  FR2 | Mouse |
|  FR3 | Keyboard |
|  FR4 | Program: Unreal engine |

## Non Functional Requirements

| ID        | Type (efficiency, reliability, .. see iso 9126)           | Description  | Refers to |
| ------------- |:-------------:| :-----:| -----:|
|  NFR1     | Usability | Use an Haptic suit to have greater sensitivity |  |
|  NFR2     | Visualize | Use a VR |  |

## Use Cases

### Use case 1, UC1 - FR1  Record usage of capsules by colleague

| Actors Involved        | User|
| ------------- |:-------------:| 
|  Precondition     | New hired exist, piece exist |  
|  Post condition     | New hired know how to work in the workshop|
|  | The piece is finish |
|  Nominal Scenario     | Administrator selected piece to do, the operator. the administrator checks if the operator has carried out the operation correctly. |
|  Variants     |  |



# Relevant scenarios

## Scenario 1

| Scenario ID: SC1        | Corresponds to UC1  |
| ------------- |:-------------| 
| Description | User do a piece  |
| Precondition | User have a rough piece |
| Postcondition | User have piece finish  |
| Step#        |  Step description   |
|  1     | Administrator select the piece to do |  
|  2     | Administrator select operator |
|  3     | Operator make the piece |
|  4     | Administrator control the piece finish |