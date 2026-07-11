# Person

## Purpose

Represents individuals who have significantly contributed to humanoid robotics.

## Required Fields

- Full Name
- Role
- Organization
- Country
- Biography
- Related Robots
- Related Technologies

## Optional Fields

- Website
- LinkedIn
- Awards
- Publications
- Notes

## Example

Full Name: Marc Raibert

Role: Founder

Organization: Boston Dynamics

Country: USA

Biography:
Founder of Boston Dynamics and one of the pioneers of legged robotics.

Related Robots:
- Atlas

Related Technologies:
- Dynamic Locomotion

| Field | Type | Required |
|-------|------|----------|
| full_name | string | Yes |
| slug | string | Yes |
| role | string | Yes |
| organization | relationship | No |
| country | relationship | No |
| website | url | No |
| linkedin | url | No |
| biography | text | No |
