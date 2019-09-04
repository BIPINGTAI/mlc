## REST API introduction
MLC provides an API for users to quickly access to exnow's trading system and implement programmed transactions. 

|Address     |Applicable functions    |
| ------ | ------ |
| https://api.mlgo.co/public/v1/markets | Obtain MLC trading pair list |
| https://api.mlgo.co/public/v1/ticker  | Obtain MLC single market real-time quotes |
| https://api.mlgo.co/public/v1/depth | Obtain MLC single market depth  |
| https://api.mlgo.co//public/v1/trades  | Obtain MLC order history |
| https://api.mlgo.co/public/v1/kline  | Obtain MLC K line candle stick chart |
| https://api.mlgo.co/private/v1/balance | Obtain account asset information |
| https://api.mlgo.co/private/v1/limitOrder | Place order |
| https://api.mlgo.co/private/v1/cancelOrder | Cancel order |
| https://api.mlgo.co/private/v1/entrusts | Obtain information about current and historical orders |
| https://api.mlgo.co/private/v1/deals | Obtain transaction record information |



The following functions can be implemented through api：
Market information searching (K line, depth, real-time transaction, 24-hour market)
Account asset information searching
Place order and cancel order
Order history
All requests are base on the HTTPS protocol.
