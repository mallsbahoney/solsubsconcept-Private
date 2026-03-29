# solsubsconcept-Private
Private license, all rights reserved. If you open this or access this, you are only allowed to read this &amp; agree to not share or duplicate.


Solana subscriptions  

A user simply has their own PDA with an ATA for each subscription they want to make.

They simply have to make an ATA and designate the subscription holder’s program/address as recipient. 
Any company can use CPI to automatically create an ATA for that subscription holder & automate recipient input from their program.

Withdrawals from the ATA are allowed by the company who created the subscription, but only at the time agreed for the subscription.

Subscription times can be per day, per week, per month, and/or per year. 

The Unix timestamp is saved for the subscriptions, and whenever the company wants to withdraw it they activate it and whenever a user wants to cancel they simply withdraw from the ATA or don’t deposit more at time of subscription. 

Tracking a subscription is as easy as the user giving their ATA address for a program to track (and verify ownership of ATA). 

ANY user can trigger the subscription to be sent to the company from the ATA & get a flat  1 USDC fee from the sub. 
This flat 1 USDC fee is ADDED to 

This creates an action market/free profit for MAINTAINING the automated nature of the subscriptions. 

When activating: program simply compares Unixtimestamp for renewal to current unixtimestamp to determine if renewal is ok.

A single app holds all of a user’s subscriptions ATAs in one place, so a user can easily deposit into the ones they want to keep going and not deposit to the ones that they want to cancel (or withdraw what they already have before renewal date). 

Since a user’s subscriptions are a simple ATA, any user can pay for others subscriptions by simply donating to ATA.

There is a 1% fee ADDED to all subscription payments (separate from the flat 1 USDC fee). 
