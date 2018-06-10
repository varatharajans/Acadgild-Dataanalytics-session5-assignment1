# Acadgild-Dataanalytics-session5-assignment1
DATA ANALYTICS WITH R, EXCEL AND TABLEAU SESSION 5ASSIGNMENT 1

USA states vowels
S.Varatharajan
June 7, 2018
states<-c("alabama","alaska","arizona","arkansas","california","colorado","connecticut","delaware","florida","georgia","hawaii","idaho","illinois","indiana","iowa","kentucky","louisiana","maine","maryland","massachusetts","michigan","minnesota","mississippi","montana","nebraska","nevada","new hampshire","new jersey","new mexico","new york","north carolina","north dakota","ohio","oklahoma","oregon","pennsylvania","rhode island","south carolina","south dakota","tennessee","texas","utah","vermont","virginia","washington","west virginia","winsconsin","wyoming")
library(stringi)
library(stringr)
str_count(states,"a")
##  [1] 4 3 2 3 2 1 0 2 1 1 2 1 0 2 1 0 2 1 2 2 1 1 0 2 2 2 1 0 0 0 2 2 0 2 0
## [36] 2 1 2 2 0 1 1 0 1 1 1 0 0
str_count(states,"e")
##  [1] 0 0 0 0 0 0 1 2 0 1 0 0 0 0 0 1 0 1 0 1 0 1 0 0 1 1 2 3 2 1 0 0 0 0 1
## [36] 1 1 0 0 4 1 0 1 0 0 1 0 0
str_count(states,"i")
##  [1] 0 0 1 0 2 0 1 0 1 1 2 1 3 2 1 0 2 1 0 0 2 1 4 0 0 0 1 0 1 0 1 0 1 0 0
## [36] 1 1 1 0 0 0 0 0 3 1 3 2 1
str_count(states,"o")
##  [1] 0 0 1 0 1 3 1 0 1 1 0 1 1 0 1 0 1 0 0 0 0 1 0 1 0 0 0 0 1 1 2 2 2 2 2
## [36] 0 1 2 2 0 0 0 1 0 1 0 1 1
str_count(states,"u")
##  [1] 0 0 0 0 0 0 1 0 0 0 0 0 0 0 0 1 1 0 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
## [36] 0 0 1 1 0 0 1 0 0 0 0 0 0
vowela<-str_count(states,"a")
vowele<-str_count(states,"e")
voweli<-str_count(states,"i")
vowelo<-str_count(states,"o")
vowelu<-str_count(states,"u")
sum(vowela,vowele,voweli,vowelo,vowelu)
## [1] 171
sum(vowela)
## [1] 59
sum(vowele)
## [1] 28
sum(voweli)
## [1] 42
sum(vowelo)
## [1] 35
sum(vowelu)
## [1] 7
vowela<-str_count(states,“a”) vowele.
Including Plots
You can also embed plots, for example:

Note that the echo = FALSE parameter was added to the code chunk to prevent printing of the R code that generated the plot.


USA states vowels
S.Varatharajan
June 7, 2018
states<-c("alabama","alaska","arizona","arkansas","california","colorado","connecticut","delaware","florida","georgia","hawaii","idaho","illinois","indiana","iowa","kentucky","louisiana","maine","maryland","massachusetts","michigan","minnesota","mississippi","montana","nebraska","nevada","new hampshire","new jersey","new mexico","new york","north carolina","north dakota","ohio","oklahoma","oregon","pennsylvania","rhode island","south carolina","south dakota","tennessee","texas","utah","vermont","virginia","washington","west virginia","winsconsin","wyoming")
library(stringi)
library(stringr)
str_count(states,"a")
##  [1] 4 3 2 3 2 1 0 2 1 1 2 1 0 2 1 0 2 1 2 2 1 1 0 2 2 2 1 0 0 0 2 2 0 2 0
## [36] 2 1 2 2 0 1 1 0 1 1 1 0 0
str_count(states,"e")
##  [1] 0 0 0 0 0 0 1 2 0 1 0 0 0 0 0 1 0 1 0 1 0 1 0 0 1 1 2 3 2 1 0 0 0 0 1
## [36] 1 1 0 0 4 1 0 1 0 0 1 0 0
str_count(states,"i")
##  [1] 0 0 1 0 2 0 1 0 1 1 2 1 3 2 1 0 2 1 0 0 2 1 4 0 0 0 1 0 1 0 1 0 1 0 0
## [36] 1 1 1 0 0 0 0 0 3 1 3 2 1
str_count(states,"o")
##  [1] 0 0 1 0 1 3 1 0 1 1 0 1 1 0 1 0 1 0 0 0 0 1 0 1 0 0 0 0 1 1 2 2 2 2 2
## [36] 0 1 2 2 0 0 0 1 0 1 0 1 1
str_count(states,"u")
##  [1] 0 0 0 0 0 0 1 0 0 0 0 0 0 0 0 1 1 0 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
## [36] 0 0 1 1 0 0 1 0 0 0 0 0 0
vowela<-str_count(states,"a")
vowele<-str_count(states,"e")
voweli<-str_count(states,"i")
vowelo<-str_count(states,"o")
vowelu<-str_count(states,"u")
sum(vowela,vowele,voweli,vowelo,vowelu)
## [1] 171
sum(vowela)
## [1] 59
sum(vowele)
## [1] 28
sum(voweli)
## [1] 42
sum(vowelo)
## [1] 35
sum(vowelu)
## [1] 7
vowela<-str_count(states,“a”) vowele 
barplot(part,col="red")
 pie(part)
 ```
R Markdown
This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see http://rmarkdown.rstudio.com.
When you click the Knit button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:
summary(cars)
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
Including Plots
You can also embed plots, for example:
 Note that the echo = FALSE parameter was added to the code chunk to prevent printing of the R code that generated the plot.
 
 
 Note:-
 Assignmengt with picture files are attached as a single file; Please look into the attachment.






