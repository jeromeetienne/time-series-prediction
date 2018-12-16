# Fix canonisation
- make the canonicasation scale of the stock
- so the timeserie should be stationary if possible
- normalisation in term of 0, 1 scale
- standardisation in term statistic distribution being constant over time, aka mean + standard deviation is constant
- normalisaiton and standardisation are not mutually exclusive
- both are considered scaler

- there is 2 operations. - call that a scaler
  - transform() and invert()
  - blablaTranform(timeSeries) return the invertFunction() and the modified timeSeries
  - implement various Timeseries tranform
  - https://machinelearningmastery.com/how-to-scale-data-for-long-short-term-memory-networks-in-python/

```
let {normalizeTimeSeries, invertNormalisationFct} = TimeSeries.NormalizeTransform(timeSeries)
```



- display the performance of the resulting model
  - display only the next value based on actual labels from the past
  - display only prediction, based on a single time-window of actual labels
  - display prediction on only 'up or down' categories
  - display prediction on only 'up and down' value
- fix the size of the output in the model for lstm
  - i dont need to generate all those values
  - this is likely tempering with the model quality


# Line series prediction is multiple AI problem
- this can be as a classification issue
  - buy/hold/sell based on the pattern
  - so the sliding cnn case
  - slidding CNN
- this can be a normal regression problem
  - based on all those numbers, predict a number, which happens to be the next
- this can be seen as a normal RNN
  - based on this history of values, what is the next
- this can be seen as reenforcement learning
  - if he is wrong, he is punished