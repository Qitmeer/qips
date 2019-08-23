# The Qitmeer Improvement Proposals (QIPs)

  * [Introduction](#introduction)
  * [How to Contribute](#how-to-contribute)
  * [Qitmeer Improvement Proposals (QIPs)](#Qitmeer-improvement-proposals-hips)
     * [The QIPs Categories](#the-hips-categories)
     * [The QIPs Status](#the-hips-status)
     * [The List of QIPs](#the-list-of-hips)

# Introduction
The Qitmeer Improvement Proposals (QIPs) describe standards for the Qitmeer platform, including core protocol specifications, networking protocol, consensus algorithms, client APIs and application-level standards and conventions.

# How to Contribute
First read [QIP-1 : QIP Guidelines ](hips/hip-0001.asciidoc). Then clone the repository and add your QIP to it. There is a template QIP file [hip-x.asciidoc](hips/hip-x.asciidoc). You can copy and modify it to create an new QIP. Then submit a Pull Request to the [QIPs repository](https://github.com/Qitmeer/hips).

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
| 1   | [The QIP Guidelines](hips/hip-0001.asciidoc)                | Alex Wu    | information  | Draft      |
| 2   | [Naming Definition & Terminology](hips/hip-0002.asciidoc)   | Alex Wu    | information  | Draft      |
| 3   | [Convert Block header time from uint32 to uint64](hips/hip-0003.asciidoc) | Jame Van  | Core  | Draft      |
| 4   | [DAG Consensusy](hips/hip-0004.asciidoc)                                  | Jin       | Core  | Draft      |
| 5   | [Cuckoo Cycle POW, a Programmatic Proof-of-Work](hips/hip-0005.asciidoc)  | Eric Lee  | Core  | Draft      |
| 6   | [Qitmeer compatible atomic swap cross-chain](hips/hip-0006.asciidoc) | Yi Zhang | Core | Draft |
| 7   | [API naming case sensitive](hips/hip-0007.asciidoc)         | Wayman Huo  | Interface | Draft |
| 8   | [Online Confirmation Time](hips/hip-0008.asciidoc)         | Zhixiang Zhu  | Core | Draft |
| 9   | [Block Reward Schedule and Transaction Fees Disign](hips/hip-0009.asciidoc) | blocklee | Core | Draft|
| 10  | [Offline Confirmation](hips/hip-0010.asciidoc)         | Zhixiang Zhu  | Core | Draft |
| 15  | [Qitmeer public chain for Real Estate](hips/hip-0015.md) |Abdussalam Onagun Ismail, Abdullah Han, Sulaiman Liu | Process | Draft|
| 20   | [Compact storage in linearly ordered block DAG](hips/hip-0020.md) | forchain | Core | Draft|
| 31  | [Mining and Pre-minding Design in DAG-POW System](hips/hip-0031.md)         | blocklee | Process | Draft |

