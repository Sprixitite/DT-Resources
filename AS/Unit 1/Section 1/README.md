# Approaches To System Development

## Terms:
* [Implementation](#Implementation): Describes the process of creating a working computer system based on a given system design documentation (produced earlier)

* [Changeover](#Changeover): The switching from an older system to a newer system, there are 4 methods through which it is done.

* []()

# Implementation:


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