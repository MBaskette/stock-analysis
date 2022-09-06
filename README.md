# Stock Analysis

## Overview of Project
Our good friend Steve just landed his first client as a Financial Advisor, his parents. So Steve wants to make sure he is giving his parents the best advice possible.

### Purpose
Steve's parents would like to invest in green energy companies and have decided on DAQO (DQ), New Energy Corporation. He is not sure about that paticular stock and its history of performance. We are going to help Steve compare this company with several others in the same field to make sure his parents investment is in the right stock. 
Once that is complete we will need to refactor our code to make it faster so Steve will know how long the process will take depending on the amount of data he decides to use in the future.

## Results
After running our inital code we found that DAQO was not the best stock for Steve's parents.
![image](https://user-images.githubusercontent.com/111661058/188523323-5378c8e1-0943-4675-bd45-053e6da449ec.png)

After we had the information we set our sights on refactoring our code to speed up the process.

One of the major changes we made to the code was the use of several new arrays to store the values before outputting to the spreadsheet.
 ```
    Dim tickerVolumes(12) As Long
    Dim tickerStartingPrices(12) As Single
    Dim tickerEndingPrices(12) As Single
```
And as you can see it worked quite well.
![image](https://user-images.githubusercontent.com/111661058/188524008-587bd094-fa2b-4f97-9b52-2eb0de1a561e.png)

## Summary
### Pros and Cons of Refactoring Code
Refactoring code is time consuming to say the least. You may even find that there is simply not enough time to complete the process. You may also end up creating new errors that you now ahve to debug, causing you even more time and money. But there are many advantages to refactoring. It can speed up your processing time immensly. It can make the new code easier to understand for future coders. And it can even make the software run better for the end user.

### Pros and Cons Experienced Refactoring Stock Analysis
**TIME!** It took a great deal of time to finish refactoring the code but that was the only disadvantage. I think the advantages of an 82% drop in speed was well worth the time. 
