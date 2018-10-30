# DISCLAIMER

**While we make every effort to ensure that material on this site is accurate 
and up to date, such material does in no way constitute the provision of 
professional advice.**

**The authors does not guarantee, and accepts no legal liability whatsoever 
arising from or connected to, the accuracy, reliability, currency or 
completeness of any material contained on this website or any linked site.**

**Users should seek appropriate independent professional advice prior to 
relying on, or entering into any commitment based on material published 
here, which material is purely published for reference purposes alone.**

# vger

A palliative solution to a certain managed fund lack of public NAV values

We all know that a certain financial service provider in Australia has so
far declined customer requests to publish the daily NAV prices for some of
its investments.

This repository tries to minimise the impact of the service provider 
actions by relying on the user data to provide the data as they know.

The two CSV files published here contain the unit prices as communicated
back to users and contributed via pull requests. The format is straight
forward:

|  investment-datetime   | issue-date | buy-value | sell-value |
|  -------------------   | ---------- | --------- | ---------- |
|2018-10-25T08:21:00+1100| 2018-10-30 |   0.9660  |            |

Investment datetime is the time you received a confirmation of an investment
or via email. That usually happens immediately after you added a deposit via 
the app or shortly after a pre-schedule deposite occurred.

Issue data is the date (without the time!) your units have been issued. 
This is date is clearly stated within the email you receive from them.

Buy value is the unit price provided via email.

Yes... we know you probably will either know the buy value *OR* the sell
value. That is fine. Just provide the data you have.

Hope this will help folks out there. Thanks for sharing!
