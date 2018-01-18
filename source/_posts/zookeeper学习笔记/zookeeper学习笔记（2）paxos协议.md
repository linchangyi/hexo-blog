---
title: zookeeper学习笔记（2）Paxos Made Simple【翻译】
date: 2018-01-18 16:50:04
tags:
---
> [Paxos Made Simple](http://lamport.azurewebsites.net/pubs/paxos-simple.pdf)

## 介绍
为具备容错能力的分布式系统而设计的Paxos算法，曾被认为难以理解，可能是因为那个希腊故事（拜占庭将军问题）。事实上，Paxos算法是最简单和直观的分布式算法。