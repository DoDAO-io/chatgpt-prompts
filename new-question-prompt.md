Create three MCQ questions  with four choices from the below text. Mention the correct choice and the explanation also.

Then populate the questions in the following YAML template

```
- uuid: 440017c8-3054-413c-9766-f4064609d8b1
  type: SingleChoice
  content: What is Juicebox and what kind of projects does it serve?
  hint: 'Nohint    '
  explanation: >-
    Juicebox serves as a blockchain equivalent of crowdfunding platforms like
    Kickstarter, Patreon, and Gofundme, or even a substitute for venture
    capital.
  answerKeys:
    - B
  subTopics: []
  difficultyLevel: Medium
  choices:
    - content: Juicebox is a platform for individuals to pay for goods and services
      key: A
    - content: >-
        Juicebox is a platform for web3 native projects or DAOs to raise funds
        for their projects
      key: B
    - content: Juicebox is a platform for large corporations to create tokens
      key: C
    - content: Juicebox is a platform for buying and selling NFTs
      key: D
```

Here 
- uuid is a random UUID4 
- content is the question
- hint is constant as 'NoHint'
- explanation field includes the explanation for the correct choice
- answerKeys includes the "key" field corresponding to the correct choice. The choices are present in the choices field that is explained below.
- subTopics is empty array
- difficultyLevel is Medium
- choices has two fields. "content" field is the content of the choice and a random character from A,B,C,D goes into the "key" Field. The key corresponding to the correct choice goes in "answerKeys" field. Make sure the correct choice is random for every question.

Output the questions in yaml format and write all the yaml in "markdown code" so that its nicely formatted 

Here is the text for creating the questions

Exchanging Assets
Cryptocurrencies are exchanged for reasons similar to those in traditional financial markets, including investment, trading, hedging, risk management, payment purposes, access to new tokens and projects, and regulatory compliance. Cryptocurrencies are seen as a new asset class with high potential returns and are highly volatile, creating trading opportunities for investors. Cryptocurrencies can be used to hedge against other investments or to manage risk in a portfolio. They can also be used as a means of payment for online transactions or remittances. Investors may exchange cryptocurrencies to gain access to new tokens or projects not available on traditional markets or to comply with regulations.

Traditional Way - Order Book
Assets are traded on an exchange through a centralized platform, an order book, where buyers and sellers place orders to buy or sell a specific asset. Trading involves placing an order, matching orders based on price and other parameters, settling the trade, and clearing it through a central counterparty.


An order book is a list of buy and sell orders for a financial instrument. It shows the supply and demand for the asset and allows traders to make informed decisions. Each order includes the type, price, quantity, and time. Orders are matched and filled based on price and time stamp. Order books are used in exchange-traded markets for transparency and price discovery.

New Way - Automated Market Maker
An automated market maker (AMM) is a type of decentralized exchange (DEX) protocol that uses a mathematical algorithm to create a market for trading assets without market makers. It creates a liquidity pool for each asset pair, and the pool's algorithm determines the asset's price based on the ratio of tokens in the pool. The AMM algorithm ensures that the pool has sufficient funds for trading and adjusts the price according to the trading volume and liquidity.


AMMs are used in DeFi platforms and are popular for their simplicity, transparency, and accessibility.
