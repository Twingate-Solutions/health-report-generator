# Twingate Insights Report Generator



This repository contains a python notebook that can be used to generate insights reports from Network Events exports.

Those reports are useful for many reasons, including answering questions for customers such as:

- which are my most active resources?
- which resources create the most errors for end users?
- which resources are no longer required?
- which resources create the most traffic?
- which services are being accessed, on which port(s) and protocol(s)?
- which addresses are served by more than 1 Resource?
- which addresses are served by more than 1 Remote Network?
- Which resources seem to be occasionally unreachable by Connectors?
- which resources seem to be occasionally unresolvable by Connectors?
- How can I refine by resource definitions?
- How can I go from broad definitions to narrow ones without breaking access wherever needed?
- are there potential routing issues due to resource ambiguity for some users & resources?
- where are end users connecting from?
- how many different networks do users connect from?
- who are the busiest users in terms of number of connections?
- who are the busiest users in terms of bandwidth?
- who are the users with the most errors?
- is there Remote Networks lacking Connector redundancy?
- is there any imbalance between Connectors in a single Remote Network?
- would any existing Remote Network benefit from spinning up an additional Connector?
- does increased activity on a Connector correlate to higher error rate?
- do Connectors show any “seasonality” in activity load?
