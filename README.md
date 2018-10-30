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

The two CSV files published here contain the unit prices as communicated
back from provider and contributed to GIT via pull requests. The format is 
straight forward:

|  investment-datetime   | issue-date | buy-value | sell-value |
|  -------------------   | ---------- | --------- | ---------- |
|2018-10-25T08:21:00+1100| 2018-10-30 |   0.9660  |            |

Investment datetime is the date and time the confirmation of an investment
via email. That usually happens immediately after one added a deposit via 
the app or shortly after a pre-schedule deposite occurred.

Issue data is the date (without the time!) the units have been issued. 
This is date is clearly stated within the email received from them.

Buy value is the unit price provided via email.

Yes... we know one probably will either know the buy value *OR* the sell
value. That is fine.

Feel free to contribute to it.
