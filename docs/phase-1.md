---
id: phase-1
title: Sensor Data Persistence Phase
sidebar_label: Sensor Data Persistence Phase
---

## Build

The build for this phase consists of two of the four modules: <abbr title="Sensor Data Hub Module">DE-1</abbr>, <abbr title="Persistence Module">DE-2</abbr>.

## Purpose

The purpose of this phase is to test the behavior of the database and various system sensors as the sensors capture data and the system cleans and filters it before it is stored. Testing will ensure that the sensors are properly capturing data and filtered/transformed into a standard format for easy storage and processing. Testing will also ensure that after the data is processed that is stored correctly in the local relational database and synced with cloud databases.

## Test Cases

| Test | Goal | Procedure |
|------|------|-----------|
| 1.1  | Sensor data received/captured | Add sensor(s) to system. Verify that sensors are outputting data. |
| 1.2  | Sensor data capture triggers Sensor Data Processor | Add multiple sensors to system, including Thermometer sensor, Doppler Radar sensor, Nest thermostat, Apple Watch. Observe if this triggers the Sensor Data Processor to process the data. |
| 1.3  | Data processed into standard format. | Feed the Sensor Data Processor captured data from connected devices. Validate that it is actively converting data to the standardized format. |

## Additional Software

No additional overhead software will be needed for this phase.