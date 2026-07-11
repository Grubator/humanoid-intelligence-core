# Event

## Purpose

Represents events related to humanoid robotics.

## Required Fields

- Event Name
- Event Type
- Start Date
- End Date
- Location
- Country
- Organizer
- Website
- Description
- Related Robots
- Related Manufacturers

## Optional Fields

- Prize Money
- Number of Participants
- Sponsors
- Videos
- Photos
- Notes

## Example

Event Name: RoboCup 2026

Event Type: Competition

Start Date: 2026-07-01

End Date: 2026-07-05

Location: Incheon

Country: South Korea

Organizer: RoboCup Federation

Website: https://robocup.org

Description:
International robotics competition featuring humanoid soccer, rescue and service robots.

Related Robots:
- Unitree G1
- Booster T1

Related Manufacturers:
- Unitree Robotics

## Database Fields

| Field | Type | Required |
|-------|------|----------|
| name | string | Yes |
| slug | string | Yes |
| event_type | taxonomy | Yes |
| start_date | date | Yes |
| end_date | date | No |
| country | relationship | No |
| city | string | No |
| website | url | No |
| description | text | No |
