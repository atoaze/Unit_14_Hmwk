# Unit_14_Hmwk

#### In this Challenge, we assume the role of a financial advisor at one of the top five financial advisory firms in the world. Our firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, our firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.

#### The speed of these transactions gave our firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. We’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, we'll enhance the existing trading signals with machine learning algorithms that can adapt to new data.

## Results:


### Actual returns versus the strategy returns, 1st pass

![Actual returns versus the strategy returns - 3 months](/Users/annatoaze/Documents/FinTech_Bootcamp/Unit_14_Hmwk/Resources_and_images/Returns_v_Strategy_Returns.png)


### Step 1: Tune the training algorithm by adjusting the size of the training dataset (6 months)

![Actual returns versus the strategy returns - 6 months](/Users/annatoaze/Documents/FinTech_Bootcamp/Unit_14_Hmwk/Resources_and_images/date_offset_6months.png)

#### Answer: Inreasing the training window to 6 months increased the accuracy and increased the Strategy Returns

### Step 2: Tune the trading algorithm by adjusting the SMA input features
#### Adjusted: short_window = 6, long_window = 300
#### Answer: Increasing both the SMA windows gave a better result for the Strategy Returns

![Actual returns versus the strategy returns - increased SMA](/Users/annatoaze/Documents/FinTech_Bootcamp/Unit_14_Hmwk/Resources_and_images/increased_SMA_windows.png)

### Step 3: Choose the set of parameters that best improved the trading algorithm returns. 
#### Answer: Increasing the SMA window positivley affected the Strategy Returns compaired to the other adjusted parameters