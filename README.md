[![Documentation](https://img.shields.io/badge/documentation-read-green)](https://docs.deepfence.io/flowmeter)
[![GitHub license](https://img.shields.io/github/license/deepfence/FlowMeter)](https://github.com/deepfence/FlowMeter/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/deepfence/FlowMeter)](https://github.com/deepfence/FlowMeter/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/deepfence/FlowMeter)](https://github.com/deepfence/FlowMeter/issues)
[![Slack](https://img.shields.io/badge/slack-@deepfence-blue.svg?logo=slack)](https://join.slack.com/t/deepfence-community/shared_invite/zt-podmzle9-5X~qYx8wMaLt9bGWwkSdgQ)

# FlowMeter
FlowMeter is an experimental utility built for analysing and classifing packets by looking at packet headers. 

## Primary design goals:

FlowMeter aims to:

 - **Classify packets and flows as benign or malicious with high true positives (TP) and low false positives (FP)**. 
 - **Use the labeled data to reduce amount of traffic requiring deeper analysis**. 

Additionally, Deepfence FlowMeter also categorizes packets into flows and shows a rich ensemble of flow data and statistics.

| <img width="1559" alt="Flowmeter-flows" src="https://user-images.githubusercontent.com/26308648/165219276-e9c9a99a-1bc1-40c9-bfaa-779b6380ae67.png"> |
|:--:| 
| *FlowMeter takes packets and returns file with statistics of flows.* |

| <img width="1559" alt="Flowmeter-flowsClassification" src="https://user-images.githubusercontent.com/26308648/165219569-42a84939-8c28-4b70-b864-f4980c3ee27d.png">
|:--:|
| *Flowmeter takes packets and returns file with statistics of flows and classifies packets as benign or malicious.*  |

## When to use FLowMeter

Use FlowMeter if you wish to build and operate machine-learning models on network packet data.

