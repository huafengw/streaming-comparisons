# Delivery Guarantee

Then let’s talk about message delivery. Here we have three semantics:

## At Most Once
At most once delivery means that for each message handed to the mechanism, that message is delivered zero or one times, so messages may be lost. 

## At Least Once
At least once delivery means that for each message handed to the mechanism potentially multiple attempts are made at delivering it, such that at least one succeeds. Messages may be duplicated but not lost. 

## Exactly once
Exactly once delivery means that for each message handed to the mechanism exactly one delivery is made to the recipient, the message can neither be lost nor duplicated.

![](img/delivery_guarantee.png)

