# Experimenting about Time Series Predictions


---

# Notes

- TODO experiment with fft prediction
  - https://www.youtube.com/watch?v=VYpAodcdFfA&fbclid=IwAR3jvud7-1zIPZGNqgIp79cLFJ5S2ZNaVx7BmvqntTn3n-RycDB3fvsVGTM
- tensorflow python version of a bitcoin trader - https://github.com/lefnire/tforce_btc_trader
  - excelent intro to the field... with even teaching on trading!!!
  - podcast associated to it - http://ocdevel.com/mlg/26
- https://stackoverflow.com/questions/39138447/how-to-stack-lstm-layers-using-tensorflow?rq=1
- basic example of lstm + tensorflow.js 
  - https://stackoverflow.com/questions/50728673/tensorflow-js-lstm-time-series-prediction
- lstm example: https://github.com/tensorflow/tfjs-examples/blob/master/addition-rnn/index.js
- Do web, no node.js
  - still run in the browser + es6 module
  - this is the environment you know
- about lstm parameters - https://stackoverflow.com/questions/49573242/what-is-sequence-length-in-lstm

- timeseries with only dense layer ??? see it here
  - https://medium.com/@andrewtrahan/trials-and-triumphs-of-time-series-machine-learning-with-tensorflow-js-4f1a1140fe10
  - it could temporarily remove the issue with the lstm setup... and unblock

- Very complete implementation
  - https://www.codeproject.com/Articles/1265477/TensorFlow-js-Predicting-Time-Series-Using-Recursi

- now that you got a kind of prediction, display the graph
  - delta between prediction and label - how to visualise that 
  - what if only prediction based on a single time window


# Good Links on reenforcement learning
- https://thecodingtrain.com/CodingChallenges/100.1-neuroevolution-flappy-bird.html
- https://blog.apptension.com/2018/06/27/tensorflow-js-machine-learning-and-flappy-bird-frontend-artificial-intelligence/

# finane.yahoo.com URLS
- https://finance.yahoo.com/quote/AAPL/chart

# Steps
- make a lstm run in the browser
- try to find a time series
- no over engineering at first
- run the lstm on csv
- display the result
  - may be nice in tfvis
- DONE download a stock in csv
- DONE display csv in canvas
