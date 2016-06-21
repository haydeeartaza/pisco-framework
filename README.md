# PisCO: A Performance Indicators Framework for COllection of Biological Resource Metrics

PIsco is a Node.js JavaScript framework for collection, registration and sharing of metrics for biological data, software and training material resources. Metrics input in PIsCO can strategically help evaluate the impact of specific bioinformatics resources. Metrics stored in a common repository and can be shared and reused by others teams, laboratories or academic institutions.

## PIsco structure

This framework consists of 3 different subcomponents that work together:

1. **Compoonent**. defines the metric standard definition (common metadata into  XML schema), and metric functionality (following a basic structure: code, documentation, guidelines, and examples, stored into the source code manager).
2. **Components Registry**. registers the component metadata into a registry to make them available for use. The component metadata will be used to install this component into the framework repository.
3. **Data and Monitoring Repository**. installs, executes components and collects data from the component execution.  Metrics results, generated from each component execution are stored in a Mongodb database and they are able to be used and interpreted.
