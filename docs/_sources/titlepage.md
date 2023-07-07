# Trash: Here and Now

## Draft 

Notes and calculations for a manuscript about assessing beach litter data from one municipality over time from 2015 - 2022. *The changes in beach litter density over time are assessed by considering the results from the most recent regional survey. Two methods are explored to determine the probability and magnitude of the expected density of beach litter. One mucipality, Saint Sulpice, on Lac Léman is surveyed every year by students of the EPFL. Their have been three large scale campaigns in the Léman region since sampling started at Saint Sulpice, this includes 35 different locations from > 20 municipalities. The most recent campaign dates from 2022 by the Association pour la Sauvegarde du Léman. The sampling campaigns were conducted by very distinct groups using the same protocol.*

## Purpose

Demonstrate the utility and applicability of observational data to environmental assessment process for managing public spaces. Beach litter data is chosen because there is a rich data set of independent observations. In the region of interest there are 250 samples representing the number of objects found from a list of 230. Anthropologists should delight. __Plastics and toxicity is a persistent topic that the industry can not seem to shake. In this regard the EU has opted for the principle of precaution, establishing a recommended limit of ~ 20 piece of trash per 100 meters__. Municipalities manage the resources for preventing and reducing plastics in our water, they must have a tool to aid the decision making process. This tool should be evidence based, easy to replicate and interpret.

## Introduction

Beach-litter data is `count` data. Gathered by volunteers following a protocol, the data is highly variable for many reasons. In most studies the median is less than the mean and in the case of the data for this study, the standard deviation is greater than the mean. Statistical tests dependent on linear relationships may not be appropriate, depending on the scale of the analysis OLS methods may be to granular. The guide from the JRC suggests using a Negative binomial distribution for modeling extreme events.

This demonstration amounts to the accounting of the interaction of multiple variables and a data set that can only be described as highly variable at all levels of aggregation. The EPFL students provide an ever-changing but constant population type among the multitude of actors that are associated with  _The litter industry_. __Observations from groups like the WWF, EPFL, ASL or smaller local groups should not be excluded from the assessment process. In reality, they gain in value when compared to other groups__. It is sufficient to know how they differ and establish usability in terms of scale and measuring techniques.

* In section one we want to know how the counts change when a different group or person is counting.  

__In section two we are modeling the experience of the litter-surveyor or an attentive beach-comber__. This includes recognition and classification of the environment in which the object was found.  It is assumed that there is an exchange between the lake and shoreline. Therefore, land use adjacent to the survey location is considered another source of objects on the beach. Experience tells us this and the data bear it out. 

Mechanically we are accounting for the variables that describe the cartographic features present (land-use) for each object at each survey. With the features defined all the survey locations can be classifed according to the environmental conditions that define them. Bayes theorem is applied for each object-instance, therefore each count value is considered a random variable defined by the independent variables that describe the economic and topographic features adjacent to it. In section two we use a hexgaon of 3000 meters, with the survey location at it's center, as the definition of adjacent.

To better control (eliminate) trash in the environment it is essential that the limited resources that are attributed to this domain be used as efficiently as possible. Correctly identifying zones of accumulation and or the objects that are accumulating in the watershed would enable more coordinated and precise actions between stakeholders. The process of identification needs to fulfill certain operating requirements to be effective:

* accurate
* repeatable
* scale-able (up and down)

__Authors:__ Roger Erismann, Bhavish Patel

For information regarding the contents of this document contact analyst@hammerdirt.ch
