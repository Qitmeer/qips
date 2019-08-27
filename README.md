# The Qitmeer Improvement Proposals (QIPs)

  * [Introduction](#introduction)
  * [How to Contribute](#how-to-contribute)
  * [Qitmeer Improvement Proposals (QIPs)](#Qitmeer-improvement-proposals-qips)
     * [The QIPs Categories](#the-qips-categories)
     * [The QIPs Status](#the-qips-status)
     * [The List of QIPs](#the-list-of-qips)

# Introduction
The Qitmeer Improvement Proposals (QIPs) describe standards for the Qitmeer platform, including core protocol specifications, networking protocol, consensus algorithms, client APIs and application-level standards and conventions.

# How to Contribute
First read [QIP-1 : QIP Guidelines ](qips/qip-0001.asciidoc). Then clone the repository and add your QIP to it. There is a template QIP file [qip-x.asciidoc](qips/qip-x.asciidoc). You can copy and modify it to create an new QIP. Then submit a Pull Request to the [QIPs repository](https://github.com/Qitmeer/qips).

# Qitmeer Improvement Proposals (QIPs)

## The QIPs Categories
  * **Core** - Qitmeer Core related improvements.
  * **Networking** - includes improvements around network protocol specifications.
  * **Interface** - includes improvements around client API/RPC specifications and standards, and also certain language-level standards like method names etc.
  * **Application** - application-level standards and conventions.
  * **Information** - provides general guidelines or information to the Qitmeer community, but does not propose a new feature
  * **Process** - describe a process propose to an implementation, they often require community consensus.

## The QIPs Status
  * **Draft** - an QIP that is open for discussion
  * **Accepted** - an QIP that is under designing and planned to be implemented.
  * **Final** - an QIP that has implemented and finalized
  * **Deferred** - an QIP that is not being considered for immediate implementation.

## The List of QIPs

| No. | Title                                                       | Author     | Type         | Status     |
|-----| ----------------------------------------------------------- | ---------- | ------------ | ---------- |
| 1   | [The QIP Guidelines](qips/qip-0001.asciidoc)                | Alex Wu    | information  | Draft      |
| 2   | [Naming Definition & Terminology](qips/qip-0002.asciidoc)   | Alex Wu    | information  | Draft      |
| 3   | [Convert Block header time from uint32 to uint64](qips/qip-0003.asciidoc) | Jame Van  | Core  | Draft      |
| 4   | [DAG Consensusy](qips/qip-0004.asciidoc)                                  | Jin       | Core  | Draft      |
| 5   | [Cuckoo Cycle POW, a Programmatic Proof-of-Work](qips/qip-0005.asciidoc)  | Eric Lee  | Core  | Draft      |
| 6   | [Qitmeer compatible atomic swap cross-chain](qips/qip-0006.asciidoc) | Yi Zhang | Core | Draft |
| 7   | [API naming case sensitive](qips/qip-0007.asciidoc)         | Wayman Huo  | Interface | Draft |
| 8   | [Online Confirmation Time](qips/qip-0008.asciidoc)         | Zhixiang Zhu  | Core | Draft |
| 9   | [Block Reward Schedule and Transaction Fees Disign](qips/qip-0009.asciidoc) | blocklee | Core | Draft|
| 10  | [Offline Confirmation](qips/qip-0010.asciidoc)         | Zhixiang Zhu  | Core | Draft |
| 12  | [destroy & mapping v1](qips/qip-0012.asciidoc)         | zhang yi  | Application | Draft |
| 14  | [DAG Algo v2:PHANTOM](qips/qip-0014.asciidoc)         | Jin  | Core | Draft |
| 15  | [Qitmeer public chain for Real Estate](qips/qip-0015.md) |Abdussalam Onagun Ismail, Abdullah Han, Sulaiman Liu | Applications | Draft|
| 16  | [Sukuk Use cases on QIT Public chain](qips/qip-0016.md) |Abdussalam Onagun Ismail, Abdullah Han | Applications | Draft|
| 18  | [Create User's local wallet (Native B/S private wallet)](qips/qip-0018.md) | Application | Process | Draft|
| 20   | [Compact storage in linearly ordered block DAG](qips/qip-0020.md) | forchain | Core | Draft|
| 29   | [Taxing Design](qips/qip-0029.md) | xiaobai | Core | Draft|
| 31  | [Mining and Pre-minding Design in DAG-POW System](qips/qip-0031.md)         | Jeremy Chen | Process | Draft |
| 32  | [QIT-based decentralized gateway](qips/qip-0032.md)         | Zeyu Dai | Process | Draft |


