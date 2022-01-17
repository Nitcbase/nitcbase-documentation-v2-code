---
sidebar_position: 1
title: 'Introduction'
tags:
  - overall design
  - introduction
  - design
  - diagram
---
NITCbase is a tiny relational database management system. It has a very simple specification that allows a junior undergraduate computer science student to implement it in a few months. NITCbase follows a seven layer design, with the basic capabilities of a standard relational database including creation and deletion of tables, managing records, selection queries and indexing using B+ Tree.

###### TO BE FILLED AND COMPLETED ######

## Overall Design/Architecture
The following diagram gives an idea of the system that we are building and it's components on a higher level.

![Design Diagram](../../static/img/overall-design.png)

There are two command line interfaces, a disk and the Seven Layers. Since NITCbase is a relational database, it supports execution of SQL-like queries on the commandline interfaces. Disk is the single storage unit for for all data present in NITCbase. 