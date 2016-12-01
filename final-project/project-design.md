### Project Writeup

The problem I am solving is this: is there a correlation between political initiative and the number of terrorist groups.


My data set will be the initiative section of this site: http://www.idea.int/themes/direct-democracy


EDIT:

Used these data sources instead:

http://www.pewglobal.org/2014/12/18/many-in-emerging-and-developing-nations-disconnected-from-politics/engagement-report-04/

https://en.wikipedia.org/wiki/List_of_designated_terrorist_groups


My outcome will be a continuous variable - number of terrorist groups.
At the current moment I'm planning to count any political group that has carried out an act of violence, and any group that self-reports as the definition of a terrorist group (group with political grievance espousing violence as a tactic).

EDIT:

Had to adjust this to groups that have been designated as terrorist groups... I did read the notes on why each country classifies a group as such, but since it's country by country-based it's a little suspect.

I will use a linear regression on the variables I can pull out of the initiative section to calculate either total number of terrorist groups, or terrorist groups per capita.

EDIT:

Also tried a logistic regression, treating the number of terrorist groups as a categorical variable, which makes no real sense unless I reclassify it as a measure of terrorist risk. E.g. Thailand having the same category of terrorist group risk as Turkey.