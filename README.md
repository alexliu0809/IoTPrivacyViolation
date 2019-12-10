# Measuring How Much Amazon Echo Uploads via Traffic Analysis
This is a course project for CSE 227 Computer Security. 

## Abstract
Smart speakers, such as the Amazon Echo, have gained popularity in recent years. These smart speakers normally have always-on microphones that are used to detect voice commands. While very useful, this behavior of constantly listening has raised a wide range of privacy concerns. These include, but are not limited to, what is be- ing recorded, how the collected data is used and stored, and whether it is being protected well. In this work, we quantitatively answer two frequently asked privacy-related questions about Amazon Echo. First, does it stream any conversation before it is activated? Second, is any audio being sent after the end of a command? We designed and performed measurements that allowed us to answer these two questions. We first confirm that usually Echo is not transmitting any audio that happens before it is activated. We further verify that in the case of correctly detecting the end of a command, Echo will not stream any conversation that occurs after the command. Additionally, we are able to quantify that a 0.7 s gap is needed for Echo to correctly detect the end of a command. While there is a rich literature on analyzing Echo’s network traffic, ours is the first to use its network traffic to answer the two aforementioned questions in a quantitative manner.

## Authors
Enze Liu, TJ Smith, Zesen Zhang

University of California, San Diego

{e7liu,tjs003,zez003}@eng.ucsd.edu

## Misc
[Latex Template](https://github.com/acmccs/format)
