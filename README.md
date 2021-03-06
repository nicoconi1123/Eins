***
![](./image/logo.png)
# Einspy - Simulations of Traffic System Based on the Theory of Cellular Automaton
***
[![Build Status](https://travis-ci.org/xiongbeer/Eins.svg?branch=master)](https://travis-ci.org/xiongbeer/Eins)
[![LICENCE](https://img.shields.io/badge/licence-MIT-blue.svg)](https://raw.githubusercontent.com/xiongbeer/Eins/master/LICENSE)
[![Docs](https://readthedocs.org/projects/veinsdocs/badge/?version=latest)](https://veinsdocs.readthedocs.io/zh_CN/latest/?badge=latest)
## 项目介绍
* 道路交通流理论模型大体可分为三大类:宏观,中观,微观.  
元胞自动机属于微观模型,是集中于单个车辆在相互作用下的个体行为描述.  
主要用于研究高速公路与交通和城市网络交通.
* 该项目旨在提供一个简易上手且功能丰富的元胞自动机交通模拟库，包含了基于元胞自动机(NaSch)的多个经典交通数学模型

## 支持的数学模型 && TODO-List
* [x]  NaSch Model
* [x]  TT Rule
* [x]  BJH Rule
* [x]  VDR Rule
* [x]  VE Rule
* [x]  CD Model
* [x]  MCD Model
* [x]  View Rule
* [x]  多车道CA
* [x]  车辆换道支持
* [ ]  KKW Model
* [ ]  BML Model
* [ ]  交通匝道
* [ ]  十字交叉路口
* [ ]  T型环路
* [ ]  环岛
* [ ]  辅助信号灯
* [ ]  道路缩减
* [ ]  收费站
* [ ]  公交线路 Model

## 文档与教程
[Einspy-Docs](http://veinsdocs.readthedocs.io/zh_CN/latest/index.html)

 ***
* A Ns Model Eg:
![](./image/demo.gif)
![](./image/demo2.jpg)

 ***  

## 依赖
* python 2.7
* matplotlib
* pandas>=0.19
* numpy
* colorama  
* tqdm

## 安装

> pip install einspy

## 其他
* 如有问题和需求请提issues，平时我极少看邮件
* 另外一个[Veins](https://github.com/sommer/veins)专业和复杂的多，如果有更高层次需求不妨去看看
