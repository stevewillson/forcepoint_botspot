# botSpot

Tool to display activity in a chart of time / ip / url displays 

Collect a CSV file with the following columns: 'time', 'ip', 'url'
Ensure there are column names in the first row ('a', 'b', 'c',...)

The program currently looks for the following column names

'time' -> time
'ip' -> source_ip
'url' -> url 

Load the CSV file and look for long streams of connections to websites, that's probably a bot.

