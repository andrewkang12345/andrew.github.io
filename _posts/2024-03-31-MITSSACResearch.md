---
layout: post
title: Research for Ohio State & MIT Sloan Conferences
subtitle: Monotonic Neural Networks for Pitch Control Visualization
categories: docs
tags:
---

## PANOCOACH

BACKGROUND /

This was a project done for the Ohio State University SAC and MIT Sloan SAC, under the advisory of Dr. Scott Powers. I thought that the concept of pitch control in soccer analytics could be extended to NFL defense with monotonic neural networks. I hypothesized that this could provide useful visualization for coaches as well as new metrics that explain defensive style.

RESULTS /

Below is a demo video of an arbitrary play from the 2022-2023 NFL Season.
![](https://youtu.be/qz1pFA7cPSo)

ABSTRACT /

[LINK to my conference.](https://buckeyemailosu-my.sharepoint.com/personal/ruddy_19_osu_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fruddy%5F19%5Fosu%5Fedu%2FDocuments%2F2024%20SAA%20Conference%20Program%20%283%29%2Epdf&parent=%2Fpersonal%2Fruddy%5F19%5Fosu%5Fedu%2FDocuments&ga=1)

In soccer, pitch control [6, 2] measures each player's potential influence of the pitch in terms of ball possession. Similar attempts exist around defense in football analytics, such as [1, 4]. Like Chang, et al. [1], our tackle influence quantifies each defender's space occupation, in which a potential runner would likely be tackled by that defender within a given amount of time. Unlike this work, we seek to find non-Gaussian space contours directly from data of tackle success and failure, using temporal tracking data made public for the NFL Big Data Bowl 2024 [3]. This is calculated using a monotonic neural network [5] that considers features such as relative velocity, acceleration, and position of the defender with respect to the runner. Its monotonicity constraint allows us to quickly converge on tackle probability predictions by exploiting our assumption of each feature’s relationship to tackle success. Furthermore, this framework could be used improve the evaluation of runners and runs, using the average change in tackle influence per frame. This method requires less data than current methods to comprehensively assess how effectively runners exploit defenses compared to their peers. Overall, our approach offers a new way to visualize defensive strategies and evaluate runners’ effectiveness in the NFL.
