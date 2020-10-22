# SAP Cloud Platform Process Visibility Samples
[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/cloud-process-visibility)](https://api.reuse.software/info/github.com/SAP-samples/cloud-process-visibility)

## Description
This project contains sample code and sample scenarios that would enable you to learn more about and gain instant value using SAP Cloud Platform Process Visibility. This project is referenced by tutorials and blogs.

The project contains:
* Sample Code to integrate SAP Cloud Platform UI Applications into SAP Fiori Launch Pad
* Sample Scenarios (model and events) that can be imported into the Configure Business Scenario and Event Acquisition Application in Process Visibility 


## Requirements
The following SAP Cloud Platform Services are needed to run the project:
* Process Visibility
* Portal
* Application Runtime
* SAP WebIDE


## Download and Installation

### Set Up the Prerequisites
Create service instance of process visibility and assign process visibility roles to users - for more details see [Getting Started with Process Visibility](https://help.sap.com/viewer/62fd39fa3eae4046b23dba285e84bfd4/Cloud/en-US/5d048d285e1b43d29efe04e2f9ab98fb.html).

### Integrate Process Visibility UI Applications in SAP Fiori Launchpad 
1. Import Project [FLPConfigForPVS](../../releases/download/1.0.0/FLPConfigForPVS.zip) into SAP WebIDE - for more details see [Import Project](https://help.sap.com/viewer/825270ffffe74d9f988a0f0066ad59f0/CF/en-US/e39599b757c541beb8e50b454f8d2431.html).
2. Build and deploy it into your space - for more details see [Packaging and Deploying Applications](https://help.sap.com/viewer/825270ffffe74d9f988a0f0066ad59f0/CF/en-US/1b0a7a0938944c7fac978d4b8e23a63f.html).

### Gain Insights into Lead to Cash Sample Scenario
1. Import the [Lead to Cash Events](../../releases/download/1.0.0/LeadToCashEvents.json) into the Event Acquisition Application - for more details see [Import Events](https://help.sap.com/viewer/62fd39fa3eae4046b23dba285e84bfd4/Cloud/en-US/72a054799c6f41e08b5445b950ac512d.html).
2. Import the [Lead to Cash Scenario Model](../../releases/download/1.0.0/LeadToCash.zip) into the Configure Business Scenario Application - for more details see [Import Business Scenario](https://help.sap.com/viewer/98815fb01f144355b2e8ceab5a338330/Cloud/en-US/879735a2cbc244578767d32610c8c141.html).
3. Activate Scenario using the Business Scenario Configuration Application.

### Gain insights into Design to Operate Sample Scenario 
1. Import the [Design to Operate Events](../../releases/download/1.0.0/DesignToOperateEvents.json) into the Event Acquisition - for more details see [Import Events](https://help.sap.com/viewer/62fd39fa3eae4046b23dba285e84bfd4/Cloud/en-US/72a054799c6f41e08b5445b950ac512d.html).
2. Import the [Design to Operate Scenario Model](../../releases/download/1.0.0/DesigntoOperate.zip) into the Configure Business Scenario - for more details see [Import Business Scenario](https://help.sap.com/viewer/98815fb01f144355b2e8ceab5a338330/Cloud/en-US/879735a2cbc244578767d32610c8c141.html).
3. Activate Scenario using the Business Scenario Configuration Application.

## How to get support 
[Post questions on SAP Community](https://answers.sap.com/questions/ask.html) and specify the primary tag as SAP Cloud Platform Process Visibility.

## License
Copyright (c) 2019 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt).
