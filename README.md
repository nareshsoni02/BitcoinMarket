# Bit Coin Market App

RFQ engine allow the business to enter the bitcoin market. For a given currency and amount, it provides Quote based on
live order.

Assumption :-

1) Live orders board Classes (Order, LiveOrderBoard and LiveOrderBoardImpl) are pre-existing
2) Give API definition can not be changed
3) For invalid input(non-existing currency and amount<1), empty quote will be returned
4) All exceptions will be suppressed and logged and it will return empty quote
5) It will only return bid which are above profit

Package :-
beans :- All bean classes
client:- Test app to verify real implemenation
configuration :- Spring bean configuration
constants:- All Constants classes
enum:- Enum Constant classes
liveboard:- Existing implementation of live order board
serice:- Stores service classes
validation :- Stores validation classes

# Getting Started

This service can be run on jvm

# Pre-requisities

In order to run this service you need java 8 runtime and maven

# Running the tests

mvn test

# End to end Integration tests

com.creditsuisse.bitcoinmarket.service.impl.RfqServiceImplTest contains end to end integration test cases.

# Built With

Java 8
Spring 4
Mockito 1.9.5
Log4j 1.2.17
Junit 4.10
Maven

# Versioning

Github

# Authors

Naresh Soni - Initial work - PurpleBooth

# License

This project is licensed under the Credit Suisse License - see the LICENSE.md file for details

