Goal 1

execute a single trading algorithm defined by spec (json/yaml/etc) on a single equity, by a single application instance, using alpaca as a brokerage api connection.

Goal 2

Allow a single trading algorithm to be backtested by running the application in some specific configuration

Goal 3

Allow multiple trading algorithms to be hosted on a single application instance

Goal 4

Create dynamically allocated infrastructure using containers based on compute resources




1. A user should be able to define a trading algorithm using json/yaml/toml.

2. A user should be able to backtest their trading algorithm over some period of time.

2. A user should be able to forward test their trading algorithm in real time.

3. A user should be able to supply a trading algorithm spec, that will then execute trades based on the spec

4. A user should be able to view executed trades made while forward testing in real time.

5. A user should be able to view executed trades made while backtesting.

6. A user should be able to view executed trades made whiel the algorithm is running in real time.
