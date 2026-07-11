# Component Entity

## Purpose

A Component is a physical part used to build a humanoid robot.

## Examples

- Battery
- Actuator
- Electric Motor
- Harmonic Drive
- Cycloidal Gearbox
- Camera
- LiDAR
- Microphone
- Force Sensor
- IMU
- Tactile Sensor
- GPU
- CPU
- Hand
- Arm
- Leg

## Required Fields

## Required Fields

- Component name
- Category
- Manufacturer
- Country
- Description

## Relationships

- Robots
- Technologies
- Manufacturers
- Companies


Field	Type	Required
name	string	Yes
slug	string	Yes
category	taxonomy	Yes
manufacturer	relationship	No
country	relationship	No
weight_g	decimal	No
description	text	No
