# Insurance Claim Handling Process

## Source

This example is based on the fCM model in [Stephan Haarmann, Marco Montali, Mathias Weske: Refining Case Models Using Cardinality Constraints. CAiSE 2021: 296-310](https://doi.org/10.1007/978-3-030-79382-1_18).

## Description

The model describes the claim handling process at an insurance company.
It starts when a new claim is recieved and continues with a check for completeness.
If the claim is incomplete, updates are requested and received from the client.
This may be repeated until the claim is complete.
Afterwards, teh risk is assessed.
Once the risk is assessed reviews can be created:
if the risk is low, a single internal review is created.
If the risk is high, one or multiple external reviews are created.
All reviews are considered to make a decision
- the claim can be approved
- the claim can be declined
- an additional review can be request, requiring an additional decision in the future.
Reviews that have been assigned to external reviewers but not received yet can be canceled.
Depending on the decision outcome, the rejection or acceptance is send to the client a reimbursement is payed.