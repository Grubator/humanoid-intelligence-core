# Country

## Purpose

Represents countries participating in the global humanoid robotics ecosystem.

## Required Fields

- Country Name
- ISO Code
- Region
- Description
- Number of Manufacturers
- Number of Robots
- Leading Companies
- Research Institutions
- Government Initiatives

## Optional Fields

- Funding Programs
- Regulations
- Events
- Notes

## Example

Country Name: South Korea

ISO Code: KR

Region: Asia

Description:
One of the world's leading countries in robotics, supported by strong government investment and industrial innovation.

Leading Companies:
- Rainbow Robotics
- Hyundai
- LG

Research Institutions:
- KAIST
- KIST

Government Initiatives:
- K-Humanoid Alliance

## Database Fields

| Field | Type | Required |
|-------|------|----------|
| name | string | Yes |
| slug | string | Yes |
| iso_code | string | Yes |
| region | taxonomy | No |
| description | text | No |
