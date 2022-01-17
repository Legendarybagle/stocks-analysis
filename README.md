# stocks-analysis

## Overview of Project
The purpose of this project was to analyze stock data for Steve. The initial code was working but was slow and may not have worked on different stock sets from other years if Steve were to add more so the code was refactored to be more effiecient and versetile.

## Results
(Time to run for old code)
<img width="417" alt="Screen Shot 2022-01-16 at 8 37 09 PM" src="https://user-images.githubusercontent.com/39388246/149709217-aa90e26a-8189-4232-8f3e-f4ac31642014.png">
<img width="421" alt="Screen Shot 2022-01-16 at 8 37 31 PM" src="https://user-images.githubusercontent.com/39388246/149709222-207c8c0b-cb7f-4645-bd7f-757eec853809.png">
(time to run for refactored code)
<img width="419" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/39388246/149709235-01106b9f-52b9-49d2-b126-86024dced3b1.png">
<img width="424" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/39388246/149709241-0f457207-fe43-439c-93cf-92b1bea181e9.png">
In the process of refactoring the code it has been changed to give the same results while only looping thtought the rows once. This has drastically sped up the runtime of the code while giving the same outcome. the refactored code is also applicable to more data as none of the columns or rows are hard coded, as long as the data sheet has the same format as the 2 provided the length should not matter. as you can see in the above screenshots the refactored code runs 4-5 times faster than before.
<img width="238" alt="Screen Shot 2022-01-16 at 8 46 32 PM" src="https://user-images.githubusercontent.com/39388246/149709612-2518b582-8f4f-47dc-ac15-f45c0d97e51f.png">
<img width="238" alt="Screen Shot 2022-01-16 at 8 45 56 PM" src="https://user-images.githubusercontent.com/39388246/149709617-e8b603cb-a7a1-42d5-8ee1-1daa232c52d8.png">
The tables above show that the stocks had sigificantly worse returns in 2018 compared to 2017. However, RUN had a much higher percentage returns and was the only stocks number that went up between the 2 years.

## Summary
1. the advantages of refactoring code is that it can become more efficient, faster and more useful for more data. The disadvantages are that it can take a while to do and gives the same result, so if your inital code works for what you need it to and is fine it might be better to just keep it. It all depends on the specific situation but of course your initial code could already be plenty optimal enough for what you need it to do.
2. the refactored code runs significantly faster, but both are still under a second for the amount of data provided. the new code also works on a greater variety of data and only loops through the code once, but for the data provided both are quite fast. However, if the same code were to be run on a new set of data that was much longer, the old code might be slow enough to matter. Also of note is that there is a lot of money in stocks and getting analysis a couple seconds before others could make a significant difference in trades.
