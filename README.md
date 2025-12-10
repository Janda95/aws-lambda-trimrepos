# aws-lambda-trimrepos


##  Summary

An AWS Lambda used for scanning and reporting/removing undesired running repo instances.


### Overview 

AWS Lambda to comb through running repo instances and kill off oldest survivors up to Min Survivors that have passed Time To Live. 

Requires the following:

- yaml file with expected parameters:
    - repo_name
    - ttl_hours
    - min_survivors
- Relavent Permissions
- Report and/or permission to delete selected items


### Setup and Execution


### Example




### Progress and Planned Updates
- [x] Local Testing
- [ ] AWS Config Setup
- [ ] AWS Config Loading and Testing
- [ ] AWS ECRs plugin
- [ ] Lambda Integration
- [ ] Trial Runs
- [ ] Tested and approved