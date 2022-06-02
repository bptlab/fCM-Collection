# Computer Aided Translation Process

## Source

This example is based on an interview with a translator and is part of the following publication:
[Stephan Haarmann, Adrian Holfter, Luise Pufahl, Mathias Weske: Formal Framework for Checking Compliance of Data-Driven Case Management. J. Data Semant. 10(1-2): 143-163 (2021)](https://doi.org/10.1007/s13740-021-00120-3)

## Description
When a translator is offered a job, they reject or accept it.
If they accept the job, they have to create a translation.
First, they use the CAT tool and its inbuild translation memory to enter pre-translated text blocks.
Afterfords, the text is split into segments, which can be translated one at a time.
Once all segments have been translated the translation is finalized.
Using the original text and the translation an alignment can be made (automatically) and been verified manually.
Alternatively, the alignment can be created manually.
The alignment is used to update the translation memory for future projects.