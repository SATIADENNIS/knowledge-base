---
title: "Does MyEtherWallet have an API?"
date: 2018-06-01 00:02:00
tags:
  - api
categories:
  - 
    - diving-deeper
primary_category: diving-deeper
primary_category_display_name: "Diving Deeper"
alias:
  - en/diving-deeper/does-myetherwallet-have-an-api.html
author: MyEtherWallet (MEW)
---

# **Does MyEtherWallet have an API?**

###### {% read_time title "Does MyEtherWallet have an API?" %} min read

* * *

## **MEW doesn't have an api, but here are the API docs for Etherscan, Infura, Alchemy, and Rivet (the four main providers of public nodes):**

-   [Infura](https://infura.io/#how-to)
-   [Etherscan](https://etherscan.io/apis)
-   [Alchemy](https://docs.alchemyapi.io/)
-   [Rivet](https://rivet.cloud/)

Our backend infrastructure is on AWS. You can actually do it yourself and [run your own public or private node](https://github.com/MyEtherWallet/docker-geth-lb).

Or you could pay a small fee and use [QuikNode](https://quiknode.io/), which makes it even easier.

For both of these options, you could also connect to your own node via the 'Add Custom Node' option in the network selector in the top-right corner. For more information, read our article on [troubleshooting custom node issues](/@@@@@@/networks-and-nodes/unable-to-connect-to-custom-node/).

Or use our API directly to it (see the docs in the above APIs).
