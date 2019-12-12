# Basic Capella Viewpoint
This project a basic Capella Viewpoint for quality assessment developed with Capella Studio

## Getting Started

This projects has the source code of the viewpoint and the generated and packaged viewpoint

### Prerequisites
To change in the source code you will need to have:
* [Capella Studio](https://www.eclipse.org/capella/download.html) - Open source SDK to develop Capella add-ons

To use the packaged version of the project (QualityAssessment_201912031504.zip) you will need to have:
* [Capella](https://www.eclipse.org/capella/download.html) - Open source MBSE tool to create system, software or hardware architectures


### Installing the source code
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Before starting you should make sure that Capella Studio is well installed (mentioned above)

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Step 1: Download the project**

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Clone the project to your local repository

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Step 2: Opening the project**

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Use Capella Studio to open and edit the project

### Generating the viewpoint
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; This step is to generate the viewpoint after editing the source code

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Generate**
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Right click in the .spec.vptext and click on Generate Viewpoint

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Generate and package**
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Right click in the .spec.vptext and click on Generate and Package Viewpoint

### Adding Viewpoint to Capella
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; This step is to integrate the developed Viewpoint into Capella 
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Step 1 : Add the viewpoint to Capella**
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Copy the generated package (Extracted) into the repository of capella/eclipse/dropins 

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Step 2 : Open viewpoint**
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Windows -> Show View -> Others
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Choose Viewpoint Manager under Kitalpha
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Step 3 : Reference the viewpoint**
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Right click on the viewpoint and press Reference
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Step 4 : Layers**
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In the layers button, press on the viewpoint in order to view the viewpoint tools in the palette
	
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Step 5 : Use the viewpoint**
  
  ![alt text](https://github.com/houssamkanso/basiccapellaviewpoint/blob/master/img/Capella%20Studio.png)

## Built With

* [Capella Studio](https://www.eclipse.org/capella/download.html) - Download page


## Authors
* **Houssam KANSO** - *Development* - [Houssam Kanso](https://github.com/houssamkanso)


## References
[Creation of viewpoint with Capella Studio 1.1](https://www.youtube.com/watch?v=zvIzyDxAj1c&t=301s) - Youtube tutorial

[Viewpoint: the making of. Customizing Capella with Capella Studio in 20 minutes](https://www.youtube.com/watch?v=lhNvmjHRa0o) - Youtube tutorial

