---
layout: post
title: Robotics Senior Design
subtitle: Programming Rethink Robotics' Baxter Robot as a Cooking Assistant
categories: docs
tags:
---

## CHEF BAXTER

BACKGROUND /

This was a project done for a senior design course in Robotics.

![](https://youtu.be/zZRgKAX9xf0)

Overview /
Our goal was to create ROS software to demonstrate basic cooking assistance. This proved to be difficult due to hardware malfunctioning and version collisions, but we did make satisfactory progress.

Within the team, my primary responsibility centered around the Vision subsystem, an essential component in transforming Baxter into “Chef Baxter.” My goal was to enable Chef Baxter to perceive and understand its environment, identify ingredients, and determine object locations for subsequent manipulation. This encompassed configuring and calibrating an RGB-D camera, integrating object detection and tagging systems, and extracting 6D pose information that could be translated into meaningful robot commands.
My efforts included initial camera setup, tuning the pipeline for reliable AprilTag detections, experimenting with YOLO-based object recognition models, and eventually incorporating depth information for retrieving precise object coordinates. Over the semester, I iteratively refined the vision workflow—from raw sensor data capture to robust, real-time object detection and tracking—ultimately providing Chef Baxter the visual “eyes” it needed to assist in the culinary tasks of preparing fruit salads.
