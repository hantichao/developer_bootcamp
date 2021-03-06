# Tutorial Overview

## Scenario

EnOS provides REST APIs that cover the core business processes of the system. Based on these APIs, developers can integrate the device, asset, data, and alert resources on EnOS Cloud in one application, meeting the requirements of various business scenarios.

In the [Device Connectivity and Management](https://github.com/EnvisionIot/developer_bootcamp/blob/master/Day2_Device_Connectivity_Management/lab_tutorial/302-1_connecting_device_to_EnOS_cloud.md) lab, we have connected smart batteries into EnOS. In this tutorial, we will develop a web based application with Python to query and display the list of smart battery devices, the health, remaining energy, current, voltage, temperature, and alert data of each smart battery. 

This tutorial walks you through a typical path of developing an application using the EnOS Python Core SDK (Athena), and that is:

- Getting the SA (service account) of the application that is registered on the EnOS Console.
- Creating a Python Flask web project and installing the EnOS Python Core SDK 
- Invoking EnOS API with SDK and verifying the returned data
- Developing back-end interfaces for data to be displayed on the front-end
- Viewing the queried battery data on the front-end interface

## Prerequisites

1. You have completed setting up the Python development environment.
2. You have completed the lab for connecting smart batteries into EnOS and uploading the simulated data to EnOS.

## Units

This tutorial includes the following units:

> [Unit 1. Getting the SA of the Application](getting_app_sa.md)
>
> 10 minutes

> [Unit 2. Creating a Web Project](creating_web_project.md)
>
> 30 minutes

> [Unit 3. Invoking EnOS APIs](invoking_api_python.md)
>
> 30 minutes

> [Unit 4. Developing by Yourself](developing_by_yourself_python.md)
>
> 30 minutes

