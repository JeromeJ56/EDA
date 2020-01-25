# ICC Test Cricket Batting Figures

## Summary :

  Test Cricket is the longest form of cricket which played for five days, each team has two innings of battinng  and bowling. The Data given here is Batting figures of 3000 players from every nations which plays International Test Cricket.
By  doing **EDA** ***(Exploratory Data Analysis)*** on this data we can visualize and answer some basic questions like Top Five Batsman with High Scores,Average and Runs.

## Dropping Last 20 Players:

  Last 20 Players does not have enough data to analyse imputting data would not feasible to analyse imputting data would create ***outliers***.
  
## Missingno :

  Library _missingno_ will help us to visualize missing values in our data frame.
  
## Top Five Batsmen with Runs:

  By using _pandas_ nlargest() function in filtered data frame we can easily get top 5 bastman and by using _matplot.pyplot_ and _seaborn_ we can visualize the data with Bar plot in ascending order.
order of batsmen are **Sachin(IND)**,**Ricky Pointing(AUS)**,**Jacques Kallis(SA)**,**Rahul Dravid(IND)** and **Alastair Cook(ENG)**.
  
## Top Five Batsmen with Number of Not Out:

  Order of batsmen are **James Anderson(ENG)**,**Courtney Walsh(WI)**,**Muttiah Muralitharan(SL)**,**Robert George Dylan Willis(ENG)** and **Chris Martin(NZ)**.
  
## Top Five Batsmen with Average minimum 50 Matches:

  Order of batsmen are **Don Bradman(AUS)**,**Steve Smith(AUS)**,**Herbert Sutcliffe(ENG)**,**Ken Barrington(ENG)** and **Wally Hammond(ENG)**.
  
## Top Five Batsmen with High Scores :

  Order of batsmen are **Brian Lara(WI)**,**Matthew Hayden(AUS)**,**Mahela Jayawardene(SL)**,**Garfield Sobers(WI)** and **Len Hutton(ENG)**.
