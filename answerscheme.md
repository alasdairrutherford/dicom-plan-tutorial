## Assignment

### Part 1 - Calculation
In the resources folder, there is an RP object called `RP.singlefield-assignment.dcm`. 

1. Using this plan object, please produce a step-by-step calculation, and compare the calculated meterset with that in the plan object itself. [4 marks]
2. An OAR is present at 15cm deep from the surface of the patient, on the central axis - what dose would this organ at risk receive (assume it is a point i.e. has no volume) [2 marks]

Present your calculations step-by-step in a document. You may continue to write some code in this notebook to present the DICOM information, or you may download the DICOM file to open in your own environment.

### Part 2 - Single vs.  Multi-field Plans
In the resource folder, there is an RP object called `RP.multifield-assignment.dcm`.

3. Using this plan object, and comparing it against the `RP.singlefield-assignment.dcm` object, describe what 2 mains differences are present between single and multifield plans. What item links these two areas of difference? [2 marks]

### Part 3 - Anonymisation
Considering only the tags from the start of the file to the tag `RT Plan Geometry` in any of the RP objects in the resources section:
4. Select 2 DICOM tags that definitely require alteration, explain why, and what you would do to the data to make it anonymised [2 marks]
5. Select 2 DICOM tags that should not be altered and explain why [2 marks]
6. Select 2 DICOM tags that may or may be not altered, depending on the use of the anonymised dataset. Critically appraise the alteration of these, and describe some of the risks in retaining such information [3 marks]