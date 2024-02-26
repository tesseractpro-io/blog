# The Tesseract Pro Ecosystem

Tesseract Pro holds a unique position; we possess an exceptional platform accompanied by vast amounts of data. As of the time of writing, we have over 50GB of market data spanning multiple markets and years. Additionally, our users have manually annotated millions of usefull data points in the form of Markers and Turning points.

In addition to the data, we have the power of our own custom-built Frontend, backend and APIs running on our own powerful servers, making the integration of AI exceptionally powerful!

# AI models

AI models operate on the basis of learning patterns and making predictions or decisions based on data. At their core, these models employ algorithms that iteratively process input data to identify underlying patterns and relationships. The process involves training the model on a labeled dataset, where it learns to recognize patterns through repeated exposure to examples. Once trained, the model can generalize its understanding to make predictions or decisions on new, unseen data.

Using all the data from Tesseract Pro, I have been able to build and train multiple models which are being used to forecast the next turning points and their confidence score ranging from 0% to 100%. I use a approach that is called *model stacking*. In this technique, the predictions and outputs from different models are combined to generate the final prediction.

In the following screenshot you see multiple circles displayed on screen, this is where the AI model has predicted the next turning points will be. Green highlighted circles indicate a direct hit.

![Tesseract Pro AI - Bitcoin 32min](https://tesseractpro-io.github.io/state-of-ai/tpro-ai-btc.png)

In the example above, I utilized two models and integrated them into one prediction:

**Price model**: This model analyzes all available historical data for the selected market, dividing it into segments based on the cycles and quadrants of the timeframe. It then predicts the future price movement based on these patterns and trends.

**Turning point model**: This model is pivotal in the prediction process. By training on all the available turning points within Tesseract Pro, it tries to forecast the location of the next turning point. This model considers factors such as cycles, quadrants, and the PRI (Price Range Index) range to make its prediction.

# Training data

Training and validating of the AI models used by Tesseract Pro works by anonymousing the user data before processing. Protecting user data and maintaining privacy and security standards is a critical ethical consideration when integrating AI into Tesseract Pro, because of this I have included an option under the [Account Settings](https://www.tesseractpro.io/account) of every user to opt-out of the datacollection of the AI model. This means we will not use your data to train or validate the Tesseract Pro AI models. **You are in control**

By constantly updating the model with the latest confirmed turningpoints, the model will (hopefully) improve over time. 

# What we can do

Next to predicting turning points and plot them on your chart, we will be able to use this technique in the future for:
- Automatic buy/sell orders
- Signals on important events
- Signaling when market conditions change unexpectedly
- *[...Your feature request here...]* 😉

# Now what?

As you've seen, there have been significant advancements made with AI within Tesseract Pro, yet I recognize that there is still room for improvement. Refinement of existing models and the development of additional ones are necessary steps to enhance the accuracy of the final predictions. How I am going to distribute this new functionality is yet to be determined fully but I expect it to be a paid additional package to cover the increasently server resources. During the test/beta phase I will be releasing an initial version for **all members** to experiment with in the coming weeks, but it's important to note that utilizing the AI integration during its development phase carries inherent risks. Nonetheless, the trajectory of Tesseract Pro AI appears to be unstoppable, promising even greater strides in the future.

