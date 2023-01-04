# Approaches To System Development - Implementation

## Terms:
* [Changeover](#Changeover): The switching from an older system to a newer system, there are 4 methods through which it is done.
* [Implementation](#Implementation): Describes the process of creating a working computer system based on a given system design documentation (produced earlier)
* [Maintenance](#Maintenance): 
* [Technical Documentation](#Technical-Documentation): Documentation providing developer information needed to successfully maintain a piece of hardware or software.
* [User Documentation](#User-Documentation): Documentation providing the user all the information needed to successfully use a piece of hardware or software.

# Changeover:

There are `four` main methods of changeover, as follows:

## Parallel Running:

Parallel running involves using _both_ the old and new systems for (what is usually) a short time. <br/>

Advantages:
* The old system available as backup in event of new system failing.
* The results of both systems may be compared to ensure functionality of new system.

Disadvantages:
* There is an increased workload on those running the system.

<picture>
    <source media="(prefers-color-scheme: dark)" srcset="./graphics/Parallel%20Running%20Dark.png"/>
    <source media="(prefers-color-scheme: light)" srcset="./graphics/Parallel%20Running%20Light.png"/>
    <img src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png" alt="Example of parallel running." style="width:450px" />
</picture>

## Direct Changeover:

Direct running involves moving from the old system directly to the new system, immediately stopping use of the old system. <br/>

Advantages:
* No cost of running the old system like with other methods.

Disadvantages:
* No old system as a backup.
* No way to compare with older system.

<picture>
    <source media="(prefers-color-scheme:dark)" srcset="./graphics/Direct%20Changeover%20Dark.png"/>
    <source media="(prefers-color-scheme:light)" srcset="./graphics/Direct%20Changeover%20Light.png"/>
    <img src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png" alt="Example of direct changeover." style="width:450px">
</picture>

## Phased Implementation:

Phased implementation involves gradually moving from the old system to the new one, replacing the old system with the new one task by task until the entire operation has moved over.

Advantages:
* Allows for gradual installation of new system, allowing time for end users to grow familiar and to work out any kinks, staff training will also likely be easier due to the slower pace of change.

Disadvantages:
* If the new system fails after having fully transitioned no backup is available.

> Image pending because I have some stuff I need to do at time of writing, please remind me about this if I forget!

## Pilot Running:

Similar to [phased implementation](##Phased-Implementation) but the new system only processes a portion of the new system's data (all data handled by the new system is also handled by the old one).

Advantages:
* Both systems' outputs available for comparison.
* Staff involved in the pilot can assist those less familiar with the new system if/when a change to the new system occurs.

Disadvantages:
* Cannot test the efficiency of the new system with the quantities of data used by the old system.

> Image pending because I have some stuff I need to do at time of writing, please remind me about this if I forget!

## Comparison Of Changeover Methods:
| Method | Comparisons? | Increased Workload? | Time To Gain Familiarity? | Backup? |
|--------|:------------:|:-------------------:|:-------------------------:|:-------:|
|Parallel| ✅           | ✅                  | ✅                        | ✅      |
|Phased  | ✅           | ✅                  | ✅                        | ✳️      |
|Pilot   | ✅           | ✅                  | ✳️✳️                        | N/A     |
|Direct  | ❌           | ❌                  | ❌                        | ❌      |

✳️: Only before the transition is completed.<br/>
✳️✳️: Only for those managing the pilot.

# Implementation:
The process of creating a working computer system based on a given system design documentation. <br/>

This design may include:
* Systems Diagrams
* Interface Designs
* Specification of verification/validation techniques

**_HOWEVER_** the process of implementation only refers to the process of putting these design elements into practice.

# Technical Documentation

Technical documentation is documentation written for the professionals involved in the design, implementation, testing, and eventual continued Maintenance of the system.

# User Documentation
User documentation is documentation which provides the user with all the information they need to support them in their successful use of a piece of hardware or software.

Depending on the nature of the hardware/software for which the documentation is relevant, it may **not** include much technical detail, however this is usually dependent on how technical the end user is supposed to be.

A good way to think of this is that the documentation for a game engine will be much more technical than the documentation for recording software.

The user documentation is only used to describe what the system can do. Whereas [technical documentation](#technical-documentation) will provide information as to it's inner workings.

User documentation will frequently incorporate some if not most of the following:
* A table of contents/index
* Minimum hardware/software requirements
* Installation instructions
* Instructions on starting/stopping the system
* Detailed instructions on how to use the main features of the system
* Examples of inputs or outputs that may be relevant to the system
* Troubleshooting

These will be used as appropriate and likely annotated with references to other relevant pages of the documentation, or images/diagrams to provide examples of things referenced in the documentation.

User documentation may be provided in a variety of formats, such as a hard copy, online, or even embedded within the system itself.

More advanced online or embedded documentation may make use of things such as videos and tooltips.

# Maintenance
Ideally all of the users' needs are addressed before the system's development has elapsed. However some issues are only identified following the main development of the system.

Maintainence refers to any action taken with regards to a software system following it's main development cycle.

There are `three` main types of maintenance, as follows:

## Corrective Maintenance:
Corrective maintenance is maintenance in response to a system/component failure. It is a reactionary response to errors or other issues as they arise.

Usually the action taken to fix the issue would be issuing a "software patch" the end user may install to fix the issue.

## Adaptive Maintenance:
Adaptive maintenance is maintenance in response to changes in the working environment of the software, or shifting user requirements.

The dynamic nature of most working environments means that some form of adaptive maintenance is inevitable. However the need for a high level of adaptive maintenance immediately after the delivery of the software may indicate that the user requirements provided were not sufficient.

## Perfective Maintenance:
Perfective maintenance is maintenance in regards to the improvement of the performance of the software.

Perfective maintenance allows the system to develop and incorporate changes demanded by the client, and is also a great opportunity for the developer to upgrade code, making it more efficient.

As with [adaptive maintenance](##Adaptive-Maintenance), a high amount of perfective maintenance immediately following the delivery of the software may indicate that the user requirements provided were not sufficient.
