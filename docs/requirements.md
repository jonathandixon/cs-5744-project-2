---
id: requirements
title: Requirements
sidebar_label: Requirements
---

The scope of this test plan will cover all four modules of this system, Sensor Data Hub Module (DE-1), Persistence Module (DE-2), Sleep Intelligence Module (DE-3), and User Interface Module (DE-4). Almost all of the original system requirements will also be covered, including functional and non-functional (listed below).

## Requirements Tested

1. User can update system settings via user interface
    1. User can turn on and off monitoring of sleep data
    2. User can customize what is monitored, when monitoring enabled
    3. User can turn on and off alerts
    4. User can view detailed report of sleep for given night
    5. User can view personalized analysis of factors that result in best sleep
2. System can continuously monitor and process data
   1. System can record environmental conditions
   2. System can record personal health/sleep data
   3. System will automatically pause sensing if user is out of range for specified amount of time
3. System can notify user to predefined conditions in real-time
   1. System can recognize symptoms of sleep apnea
   2. System can alert user to presence of user- and pre-defined conditions
   3. System can adjust Sleep Bed to different height until condition is no longer present
   4. System can adjust Nest Thermostat until condition is no longer present
4. _(Not Tested, see below)_
5.  Non-functional requirements
    1.  System protects access to sensitive health data
    2.  System will be user-friendly
    3.  User interface will easy to use by all users
    4.  User will be assigned unique account
    5.  System will use a standard sensor interface for all sensors


## Requirements Not Tested

This test plan will focus on ensuring the system as a whole as well as the individual components function as defined by the requirements. As such, some of the specific details of how the components operate internally will not be tested. Specifically, the underlying database, cloud storage, and any functions provided by the cloud, such as machine learning algorithms used to analyze user data will not be tested.

The following requirements are not specifically targeted by this test plan. Depending on how the tests are implemented and configured it is possible one or more of these requirements will be covered in this plan.

- 2.4 - System will automatically sync recorded data with cloud-based storage
- 4.1 - System will interface with a doppler radar device to monitor the user
- 4.1 - System will interface with a Nest Thermostat to monitor environmental conditions
