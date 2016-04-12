---
layout: post
title: Salesforce Migration
status: active
type: Project
updated: 2016-04-10 9:25:00
---

The logic to extract customers was originally looking only for customers that had traded alread.  This was partly due to the calculation of a Trade First Date field.

We are looking to explain why there are 600 customers that are not being retrieved from TradeX to refresh the data in Salesforce - find how many are due to not having traded yet.