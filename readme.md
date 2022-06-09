# fCM: Collected Examples

Fragment-based case management (fCM) is an academic case management approach.
In fCM, a business process is split into fragments that can be flexibly instantiated and combined at run-time.
However, during execution, the process must not violate data constraints.
An fCM model consists of four parts:
- An eponymous set of process fragments (acyclic control-flow graphs)
- A domain model (a class diagram structuring the process data)
- A state transition system for each data class (describing the object behavior)
- A termination condition specifying the goal

This repository includes a collection of fCM examples of different domains.

## Tools

The models can be opened and edited with common tools for BPMN and UML modeling, such as
- Signavior (process fragments)
- Camunda Modeler (process fragments, *may break the definition of data inputs and outputs*)
- Papyrus (domain model and state transition tiagrams)
- Any text editor (termination condition)

## Models
- [Job Application Process](application/)
  - [Fragments](application/fragments.bpmn)
- [Computer Aided Translation](computeraidedtranslation/)
  - [Fragments](computeraidedtranslation/fragments.bpmn)
- [Conference Submission and Reviewing](conference/)
  - [Fragments](conference/fragments.bpmn)
- [Diagnosing Diabetes and Initial Treatment](diabetes/)
  - [Fragments](diabetes/fragments.bpmn)
- [Enrollment in Study Program](enrollment/)
  - [Fragments](enrollment/fragments.bpmn)
- [Fixed Price Request](fixedpricerequest/)
  - [Fragments](fixedpricerequest/fragments.bpmn)
- [Insurance Claim Handling](insurance/)
  - [Fragments](insurance/fragments.bpmn)
- [Mammography](mammography/)
  - [Fragments](mammography/fragments.bpmn)
- [Deutsche Presse Agentur](press/)
  - [Fragments](press/fragments.bpmn)
- [Seminar Organization](seminarorganization/)
  - [Fragments](seminarorganization/fragments.bpmn)
- [Criminal Justice](criminaljustice/)
  - [Fragments](criminaljustice/fragments.bpmn)