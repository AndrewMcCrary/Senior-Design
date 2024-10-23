# Task List

## Algorithm Parsing Engine
- Define json/toml/yaml spec
- Create engine to parse definition into usable 

## Algorithm Execution Engine
- Establish indicator pattern
- Create base indicator definitions
- Create indicator ordering / relationship pattern

## Trade Execution Engine
- Create api to buy/sell
- Mechanism to track current cash, which may influence trade quantity

## Brokerage Integration
- Manual API integration (acquire some number of trades from some time period for some symbol)
- Websocket stream integration (acquire trades in real time from some symbol)

## Data Ingestion Engine
- Abstract single brokerage away so multiple brokerages can be used
- (internally) Use channels so that manual api / websocket can be abstracted to be equivalent (potentially kafka down the road)