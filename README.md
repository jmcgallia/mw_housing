# Vizualizing the affordability of housing in the US over time
## Summary

### The Map
An interactive map to visualize how many hours one person would need to work on minimum wage in order to afford different kinds of housing over time. The user can choose different combinations of years and housing types (studio, 1BR, 2BR, etc) and see how the value of the minimum wage has changed over time when it comes to housing. The colors on the map represent hours worked in order to afford a home in the 40th percentile of price in that county. 

A popular rule of thumb would be that your rent should be about 30% of your pre-tax income. Given a standard month with 160 hours of work being completed, this implies that about 48 working hours would ideally be dedicated to paying rent. Therefore, counties where you could pay rent with 48 hours of work or less are marked with dark blue.

Anywhere where half or more of your working hours would be dedicated to paying rent on minimum wage are dark red. The colors gradient shows everything in between.

### The Graphs
Users can also view a graph showing the counties with the most and least affordable accomadations given the local minimum wage. Maybe someone could use it while brainstorming about where to move.

## Technology / skills used
- Excel
- Tableau
- Researching and finding data
- Data cleaning/organization/compilation
- Data analysis and visualization

## About the data used
### Notes
Minimum wage is a complicated subject because many states have complicated laws regarding it. For example in a given state minimum wage for a given job depends on whether the job provides health insurance, the profits of the employer, the number of employees, etc. Certain towns and counties may also impose their own separate minimum wages.

During my data gathering, for any given county I used the lowest wage that the majority of people might have. For example, if in one state minimum wage is 9 dollars if insurance is provided, and 10 if not, I would go with 9. If a city taking up the majority of the population of a county has an ordinance for a higher minimum wage than the state, I would go with that minimum wage for the county.

### Sources
#### Minimum Wage
- **State-level**: Department of Labor minimum wage history: https://www.dol.gov/agencies/whd/state/minimum-wage/history
- **Individual Cities**:
#### Housing Costs
- US HUD fair market rents (40th percentile): https://www.huduser.gov/portal/datasets/fmr.html?aid=03c3fad7-bea6-4ab9-9a7a-82f4d6380c42

## Future Work
In the future, I would like to.. 
- lengthen the timespan available.
- Let user toggle between minimum hourly wage and median minimum since in some places is not common to make minimum wage and I think median wage is a better indicator of how easy living somewhere would be.
