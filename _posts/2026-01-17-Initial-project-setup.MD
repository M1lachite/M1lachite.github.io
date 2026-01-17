---
layout: post
author: M1lachite
title: Initial project setup
tags: [Docker, DevSecOps, infrastructure, CD/CD]
---
I created this project to get hands-on experience with practical solutions I plan to use in my future career. DevSecOps is the path I want to follow to constantly improve my skills, so expect more projects like this in the future.

The purpose of this series is to document the issues and struggles I face while delivering this solution, and to share my approach to problem-solving.

Day 1: Setup & Architecture

![folder_structure](/assets/images/folder_structure.jpg)

Today, I officially set up the project on GitHub and established the directory structure. I've designed it carefully to ensure each catalog has a clear and distinct purpose.

Architecture-wise, I decided to go with a hybrid approach (running tooling outside the cluster) to optimize resource usage and spare the Kubernetes (K3d) cluster for application workloads.