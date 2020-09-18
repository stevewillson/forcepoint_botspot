# Forcepoint botSpot

Tool to display activity in a chart of forcepoint policy violations

Extract a CSV file from a forcepoint device
Make the first row have the column names ('a', 'b', 'c',...)

The program currently looks for the following column names

'b' -> time
'p' -> source_ip
'aj' -> url 

Load the CSV file and look for long streams of violations, that's probably a bot.


