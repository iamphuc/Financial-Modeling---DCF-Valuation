# Financial-Modeling-DCF-Valuation

![](images/TESLA%20DCF%20Valuation.JPG)

# Development
This work was an effort to derive the intrinsic value of Tesla business. The valuation model was completed on December 6th, 2021 so by now, the valuation could be well off market price. However, the valuation derived by the model needs not to be in the ballpark of market price. The reasons are two-fold. First, I believe that the stock market contains influencers that are different than the intrinsic factors to Tesla business. Market price thus does not necessarily represent the intrinsic value. Second, the model reflects my own understanding of the whole electric cars business that Tesla is trying to do. Therefore, it's my own judgement with respect to projected revenues and costs. In essence, I regard this project as a business valuation exercise.

# Structure
At the heart of DCF valuation technique, it calculates the net present value of all future cashflows generated by a business that is available to equity investors. So the difficulty lies in the assumption made for projection. In my case, I split the future of Tesla into two-stage outlook: (1) there is a 10-year forseable future & (2) terminal prospect.

In the first stage, numerical assumptions for the growth in sales and cost controls for each of the ten years are made. Assumptions are made on the basis of historical records (2018 - 2020) and peer comparison. To provide some sensitivity to the assumptions, I made 3 different cases that could happen to Tesla. The 3 cases are (1) Bull case, (2) Base case, & (3) Bear case. The assumptions are adjusted accordingly to these 3 cases. Formulas are set such that cell B2 is where the change in cases is made i.e., A means bull case, B means base case, and C means bear case. 

In the second stage, I do not make numerical assumptions for the growth in sales and cost controls anymore. The reasons are two-fold. First, it's too far distant that I don't think any specific numerical projection makes sense. Second, Tesla will not experience explosive growth then anymore. Competition will enter during the first stage. Therefore, growth will become less extraordinary. At best, Tesla will grow at the same rate as the US economy of about 2.5%. 

An interesting line of business that I think will happen during the second stage is the Autonomous Driving. I don't think it's an easy sell as there is psychological and legal hurdle. For example, it takes time for people to absorb the idea of transportation carried out by a software. I make this claim because it has also taken time for people to accept electric car. A few years back, concerns about range, recharability, battery life, etc were raised not only for Tesla vehicles but electric cars in general. Now, as the tech becomes more mature and more people adapt to electric cars better, the industry rises as a whole. Therefore, I believe it will happen the same for Autonomous Driving. As for its valuation, I made a modest assumption that about 30% of US population at the time (so mostly middle class working people) would buy into the idea of Autonomous Driving. 

I also seperate the cash the flows through the Income Statement, the Balance Sheet, and the Cash Flow Statement. Adjusted EBITDA is finally adjusted for the changes taxes, capex, net working capital, and others. The resulting cash flows are the Unlevered Free Cash Flow (FCFF), which is the technical term in finance that simply means cash available to equity investors. 

# Potential Improvement
I believe that there are numerous areas that could be improved for this model. For example, I made general percentage assumption for the future growth. Another approach could be to come up with the actual production number of vehicles for each model. This is particular beneficial in terms of business understanding. Likewise, costs could be modeled in greater detailed, especially when we have a better understanding of what Tesla wants to do in terms of service. Right now, more service is being performed for one dollar worth of sales. In the future, Tesla might have to rethink this strategy as the industry becomes more mature. 

# Result
For the best case, I came up with a valuation of US$977 per share of Tesla. The actual low on Dec 6th, 2021 was US$950 and the high was US$1001. For my analysis, I don't see a bargain for Tesla price. 

_Note_: This is no financial advice by any means. Business valuation is something I like to do. So this is really a practice for me. I hope you enjoy it anyhow :)

# Reference
Guidance on this project was obtained from Youtube channel "Cents Invest"



