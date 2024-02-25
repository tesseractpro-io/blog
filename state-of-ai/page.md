# The Tesseract Pro Ecosystem

Tesseract Pro holds a unique position; we possess an exceptional platform accompanied by vast amounts of data. As of the time of writing, we have over 50GB of market data spanning multiple markets and years. Additionally, our users have manually annotated millions of data points in the form of Markers and Turning points.

# AI models

AI models operate on the basis of learning patterns and making predictions or decisions based on data. At their core, these models employ algorithms that iteratively process input data to identify underlying patterns and relationships. The process involves training the model on a labeled dataset, where it learns to recognize patterns through repeated exposure to examples. Once trained, the model can generalize its understanding to make predictions or decisions on new, unseen data.

Using all the data from Tesseract Pro, I have been able to build and train multiple models which are being used forecast the next turning points and their confidence score ranging from 0% to 100%. I use a approach that is called *model stacking*. In this technique, the predictions and outputs are combined to generate the final prediction.

In the following screenshot you see multiple circles displayed on screen, this is where the AI model has predicted the next turning points will be. Green highlighted circles indicate a direct hit.

![Tesseract Pro AI - Bitcoin 32min](https://tesseractpro-io.github.io/state-of-ai/tpro-ai-btc.png)

In the example above, I utilized two models and integrated them into one prediction:

**Price model**: This model analyzes all available historical data for the selected market, dividing it into segments based on the cycles and quadrants of the timeframe. It then predicts the future price movement based on these patterns and trends.

**Turning point model**: This model is pivotal in the prediction process. By training on all the available turning points within Tesseract Pro, it tries to forecast the location of the next turning point. This model considers factors such as cycles, quadrants, and the PRI (Price Range Index) range to make its prediction.

# Training data

Training and validating of the AI models used by Tesseract Pro works by anonymousing the user data before processing. Protecting user data and maintaining privacy and security standards is a critical ethical consideration when integrating AI into Tesseract Pro, because of this I have included an option under the [Account Settings](https://www.tesseractpro.io/account) of every user to opt-out of the datacollection of the AI model. This means we will not use your data to train or validate the Tesseract Pro AI models. **You are in control**

By using constantly updating the model with the latest confirmed turningpoints, the model will (hopefully) improve over time. 

