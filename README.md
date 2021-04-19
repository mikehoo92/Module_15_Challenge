# Module_15_Challenge
# Algorithmic Trading
## Trading Bots & Trading Signals

This notebook helps enhance existing trading signals with machine learning algorithms that can adapt to new data. With that being said we will create an algorithmic trading bot that learns and adapts to new data and evolving markets by implementing an algorithmic trading strategy that uses machine learning to automate the trade decisions, adjust the input parameters to optimize the trading algorithm, and train a new machine learning model and compare its performance to that of a baseline model.

---

## Technologies

This project uses AWS and the python language to test and operate the bot:

- AWS Lex: to create the bot and create sample utterances, slots, confirmation, and intitialization.
- AWS Lambda: to validates the user's input and returns the investment portfolio recommendation. This includes testing the Amazon Lambda function and integrating it with the bot.

<img src="Images/testing_roboadvisor_bot.png" width="400" >

---

## Usage

To succesfully run this bot, please be sure to import the required libraries and dependencies in the python file:

```
from datetime import datetime
from dateutil.relativedelta import relativedelta
```

<img src="Images/slots.png" width="750" >

---


## Conclusion

I created the Bot and intially tested it. I then began to create the lambda function code. I got as far as _Step 3: Enhance the Robo Advisor with an Amazon Lambda Function, #4 Complete the starter code so that once the intent is fulfilled, the bot responds with an investment recommendation based on the selected risk level, as follows_ before not continuing. I added the 4 test events in AWS. I did not test however due to issues with the code. 

---

## Contributors

Michael Husary was the main contributer along with fellow classmates and the educational staff. 

--- 

## License

N/A
*(Not sure if a license was required on this Challenge)*
