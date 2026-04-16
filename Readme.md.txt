# AWS CloudTrail Threat Detection Lab

## Overview
This project demonstrates manual threat detection and investigation in AWS using CloudTrail and IAM.

## Scenario
A new IAM user was created and later granted AdministratorAccess permissions. I investigated these actions through CloudTrail event history.

## Tools Used
- AWS CloudTrail
- AWS IAM

## Steps Performed
1. Created a CloudTrail trail
2. Created a new IAM user
3. Attached AdministratorAccess policy
4. Investigated CreateUser event
5. Investigated AttachUserPolicy event

## Security Value
This lab demonstrates how privileged IAM changes can be identified and investigated using native AWS logging.

## Skills Demonstrated
- CloudTrail log analysis
- IAM security monitoring
- Threat detection
- Security investigation