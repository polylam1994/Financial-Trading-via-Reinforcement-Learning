Link to paper (IEEE USA) https://ieeexplore.ieee.org/document/10417967

Abstract – The paper presents a novel approach to developing
a pair trading strategy for cryptocurrencies by employing a
customized Rainbow DQN and an image encoding technique.
This method transforms candlestick features of Bitcoin (BTC)
and Ethereum (ETH) into images, which are then input into
a Convolutional Neural Network (CNN) for feature extraction
before being fed into the Rainbow DQN model for making trading
decisions. Although the Rainbow DQN strategy outperforms RSI
and correlation strategies, none of them are profitable after
factoring in transaction costs.

P.S. At the time of writing, I wasn't aware that the more rigorous approach to pair trading typically relies on cointegration rather than correlation, so I used correlation to trade the BTC–ETH pair as a benchmark to compare with. That said, this doesn't really affect the core contribution of the paper, which is simply to demonstrate that a reinforcement learning agent can learn to execute buy/sell decisions on a pair. 
