# read.survey

*Update by mjahanshahi to remove requirement for ".xlsx"*

## Install
<code>library(devtools)</code><br>
<code>install_github('mjahanshahi/read.survey')</code>

## Example

<code>download.file('http://help.surveymonkey.com/servlet/servlet.FileDownload?file=01530000002hfBp', 'test.csv', method = 'curl') # Surveymonkey example export file</code><br>
<code>data <- read.surveymonkey('test.csv', convert = TRUE)</code>
