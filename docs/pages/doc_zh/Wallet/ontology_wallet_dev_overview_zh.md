---
title:
keywords: sample homepage
sidebar: Wallet_zh
permalink: ontology_wallet_dev_overview_zh.html
folder: doc_zh/Wallet
giturl: https://github.com/ontio/documentation/blob/master/walletDevDocs/ontology_wallet_dev_overview_zh.md
---

[English](./ontology_wallet_dev_overview_zh.html) / 中文


<p align="center" class="version">Version 1.0.0 </p>

内容:
* [钱包集成](#wallet-integration)

<h1 align="center">钱包集成</h1>





钱包包括资产账户和身份两部分.详情请参考文档 [钱包规范]()

钱包集成需要完成如下功能:

| 模块                |                    子模块                    |     测试用例     |
| ------------------    | :----------------------------------------------: | :------------------: |
| Wallet management    |           create                                 |     Use the mnemonic words when creating wallet(Based on BIP39 and BIP44 specifications)   |
|                       |          export                                 |    Export keystore      |
|                      |           import                                 |   Import keystore to wallet  |
|                      |                                                  |   Import from the mnemonic words  |
|                      |                                                  |   Import from private key      |
|                      |                                                  |    Import from WIF            |
|                      |         delete                                   |   Delete wallet account     |
|                      |        Information service                      |    Query balance of ONT&ONG |
|                      |                                                  |   Query details of ONT&ONG  |
|                      |                                                  |  Query unclaim ONT&ONG   |
|    Transfer Assets   |          Transfer                                |    ONT/ONG transfer        |
|                      |                                                  |      ONG Claim              |
|   ONT ID management  |         Create                                   |   Create a new ONT ID and write onto blockchain   |
|                      |        Import                                    |     Import keystore of ONT ID |
|                      |        Export                                    |     Export keystore of ONT ID |
|                      |       Information service                        |    Query ONT ID events , create, delete,etc.    |
|                      |                                                  |    Query ONT ID             |



这些SDK已经完成了钱包规范:

Java SDK ：[Java SDK](https://github.com/ontio/ontology-java-sdk/blob/master/docs) 

Typescript SDK ：[Ts SDK](https://github.com/ontio/ontology-ts-sdk/tree/master/docs) 

Android SDK ：[Android SDK](https://github.com/ontio-community/ontology-andriod-sdk)

Golang SDK ：[Go SDK](https://github.com/ontio/ontology-go-sdk) 

Python SDK ：[Python SDK](https://github.com/ontio/ontology-python-sdk)
