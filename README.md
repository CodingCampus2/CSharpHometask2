# Task 1

## Prerequisites:
Read Chapter 5 of .NET Book Zero and https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/tokens/interpolated

## Description:
There is a city in Programland with the name [Task1.City.Name] and [Task1.City.Population] people living in it.
There are [Task1.City.SickPercentage] people that are sick with a deadly virus with the name [Task1.Virus.Name].
The probability of death is [Task1.Virus.KillProbability].

## Goal:
Compose a string that tells how many people were killed by the virus in the city.

## Example input: 
[Task1.City.Name] = "Virtualiev"  
[Task1.City.Population] = 1400  
[Task1.City.SickPercentage] = 0.3  
[Task1.Virus.Name] = "Hlomanda"  
[Task1.Virus.KillProbability] = 0.2  

## Example output:
"There are 420 people sick with Hlomanda in the city of Virtualiev, 84 of which died"

## Clarifications:
Input variables that contains only numbers should be parsed to floats.  
Numbers, if needed, should be rounded by casting to int. (For this task only).
