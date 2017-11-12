# addDateToLog
A bash script to add dates to log files
## Scenario
Suppose you have a programm runninig that writes a log file
but it misses to write dates to its entries. If the entries consist
of a single line of text and you want to add Dates to each written
line, then here you find the solution.

## Installing
Make sure you have `git` installed. Then move to a directory
where you want the script to be installed. Execute:
```bash
git clone https://github.com/emanuel-minetti/addDateToLog.git
```
Replace `./test.log` in `addDate` with `/path/to/LogFile.log`
if `/path/to/LogFile.log` the path to your log file and `./newTest.log`
with `/path/to/NewLogFile.log`. Be carefull: There is a long line in `addDate`!
If You use `nano` to edit the file, use `nano -w`!

Make the script executable:
```bash
chmod a+x addDate
```

## Running and Stopping
