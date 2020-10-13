# Live Coding on Tuesday 13th 2020

**When:** Tuesday October 13th 2020 at 2:00 p.m. (GMT-4)

**Where:** http://tinyurl.com/IceData

**Calendar:** http://tinyurl.com/ICE-BYOD-2



## Program

### Part 1: Dataset 1

- Indoor Objects dataset: http://tinyurl.com/ICE-Indoor-Objects
- Notebook : https://github.com/airctic/icedata/blob/master/notebooks/dev/indoor_objects.ipynb 

> **Goal:** This notebook shows how to create a new parser for a custom XML annotation file. The XML file contains all images annotation in one single file. In a sense, it is similar to the COCO annotation format where all the image annotation are stored in the same JSON file as opposed to VOC annotation where each file has its XML annotation file.

## Part 2: Dataset 2

- Plant diseases dataset: http://tinyurl.com/ICE-PlantDoc
- Notebook : https://github.com/airctic/icedata/blob/master/notebooks/dev/plantdoc.ipynb 

The PlantDoc Dataset provides both the VOC annoatation and a CSV annotation. 

> **Goal**: This notebook shows how to parse the PlantDoc dataset using 2 different methods:
- Using the Icevision default VOC parser
- Creating a new parser using the csv annotation file

### Part 3: Demonstrating the new Data Validity Checking API

Virtually, every dataset has some invalid data. Parsing as well training such datasets is time consuming because of the error raised during both those steps. 

In order to overcome those obstacles and to accelerate both parsing and end-to-end training processes, we are introducing some new IceVision features that will automatically check the validity of the dataset as well auto-correcting them whenever is possible.

### Part 4: Some announcements

We will announce some upcoming events as well as some new features that we intend to work on during the upcoming weeks.