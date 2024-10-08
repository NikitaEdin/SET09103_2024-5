# Use Case: 01 Produce a Country Report
# Information
## Goal
The organisation wants a report on countries with the report containing: Code, Name, Continent, Region, Population, Capital of each country in the database.
The report will also contain these: All the countries in the world organised by largest population to smallest, All the countries in a continent organised by largest population to smallest. All the countries in a region organised by largest population to smallest.
They also want in the report is: The top N most populated countries in the world, where N is specified by the user. The top N most populated countries in a continent, based on the user’s input. The top N most populated countries in a specific region, as chosen by the user.
## Scope
Country Database
## Level
Primary Task
## Preconditions
That the countries are stored in the databases with their information
## Success condition
A report is produced to the organisation.
## Failed condition
No report is produced to the organisation.
## Primary Actor
Organisation.
## Trigger
Pressing run on the program to produce the report.
# Main Success Scenario
1. Organisation presses run on the program.
2. System reads the database and completes the query and produces the report.
3. Organisation gets displayed the country report.
# Extensions
No country database found.
Number Provided is out of bounds.
# Sub-variations
None.
# Schedule
Release 1.0
