# Manufacturer Entity

## Purpose

A Manufacturer is an organization that designs, develops or produces humanoid robots.

## Examples

- Tesla
- Unitree
- Figure AI
- Apptronik
- Boston Dynamics
- Fourier
- UBTech

## Required Fields

- Company name
- Country
- Headquarters
- Founded
- Website

## Relationships

- Robots
- People
- Technologies
- News
- Events
- Partners

Field	Type	Required
name	string	Yes
slug	string	Yes
headquarters_country	relationship	Yes
founded_year	integer	No
founder	relationship	No
website	url	No
logo	image	No
description	text	No
