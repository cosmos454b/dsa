# Youth Risk Behavior Surveillance System (YRBSS)

The Youth Risk Behavior Surveillance System (YRBSS) monitors six types of
health-risk behaviors that contribute to the leading causes of death and
disability among youth and adults.

## Resources

[YRBSS website](http://www.cdc.gov/healthyyouth/data/yrbs/index.htm)

[User
Manual](http://www.cdc.gov/healthyyouth/data/yrbs/pdf/2015/2015_yrbs-data-users-guide.pdf)

[Github.com/hadley/yrbss](https://github.com/hadley/yrbss)

```
install.packages("devtools")
devtools::install_github("hadley/yrbss")
library('yrbss')
names(survey)
```

## Files in directory

**yrbss-days-exercise.csv**: Variable labeled q80 (question 80). Tracks the
number of days a week a respondent exercises. 1 = 0 days, 2 = 1 day, and so on
up to 8.
