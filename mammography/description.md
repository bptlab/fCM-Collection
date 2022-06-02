# Mammography Process

## Source

This example is based on [CM Chiao, V Künzle, M Reichert: Towards object-aware process support in healthcare information systems (2012)](http://dbis.eprints.uni-ulm.de/775/1/eTELMED%202012_CKR.pdf).

## Description
The process starts when a patient arrives.
An anamnesis is conducted and the patient is examined.
Depending on the symtoms found during examniation further steps may be necessary:
- MRI
- Blood Test
- Mammography
Each of these tests can be performed in multiple tests:
the mammography needs to be conducted, a report needs to written, before the mammography is finalized.
The MRI and blood test is structured similarly.
Based on the results of these tests, the physician decides whether to conduct a biopsy or not.
If a biopsy is considered necessary, the patient has to conset.
Afterwards, the biopsy can be performed and the sample can be analyzed.
The process has two outcomes: either a tumor was detected or not.