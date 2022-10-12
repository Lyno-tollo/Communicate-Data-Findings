# (Prosper Loan Data Exploration)
## by (Lyno Kipkogei Tolo)


## Dataset

> The dataset consisted 113,937 loans and their attributes. The attributes included original loan amount, borrower's Prosper rating, loan term, borrower's stated monthly income, as well as many other features such as borrower's employment status, debt to income ratio, current loan status etc. The dataset can be found https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv, with feature documentation available https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0


## Summary of Findings

> In my data exploration phase, i predicted that four variables, BorrowerState,IncomeVerifiable,EmploymentStatus and ProsperScore would determine the outcome of my variable of interest,LoanStatus. However, IncomeVerifiable proved to be a tussle to further investigate since it's nature of being a boolean came with limitations and had to drop it after observations with my variable of interest.
At the end of my exploration, i was able to conclude that following conditions if satisfied will result in Completed loans:
1.ProsperScore : This proved to be the main determinant with ProsperScore of 6.5 and above regardless of employement status
2.EmploymnetStatus: Employed,Full and Part-time 
3.States:Borrowers from the states of FL,IL,NY,CA,WA and NC.

Apart from the above findings, i explored other relationships such as CreditScoreMean and ProsperScore which revealed that they are highly correlated. This means that the ratings by Prosper and Creit Agencies correspond to each other well.In addition, Defaulters have a high ProsperScore than Chargedoff loans which might be very incorrect in determining how loans should be awarded. 

## Key Insights for Presentation

> For purposes of presentation, i focused on my variable of interest which is LoanStatus and the other variables that i predicted would affect the outcome of the former. I took a closer look at the distribution of LoanStatus using a barplot.
Further, I checked the distributions of EmploymentStatus, ProserScore and BorrowerState using histogram and countplots.
The next step was to check the relationships between EmploymentStatus,LoanStatus,ProsperScore and BorrowerState using boxplots and barplots.
Finally, i investigated the effect of ProsperScore on the interactions between LoanStatus, EmploymentStatus and BorrowerState using both barplot and point plot.

## Acknoledgement

A very special appreciation to ALX Africa scholarship program without which i would not have been able to participate in this program. In addition i'm very grateful to Udacity for their well packaged and sound curriculum. More power to your elbows. Finally, thanks to my parents, teachers,mentors,friends,colleagues and all who have helped me to be who i am today. God Bless!