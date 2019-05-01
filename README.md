# The Halalchain Improvement Proposals (HIPs)

  * [Introduction](#introduction)
  * [How to Contrubute](#how-to-contrubute)
  * [HalalChain Improvement Proposals (HIPs)](#halalchain-improvement-proposals-hips)
     * [The HIPs Categories](#the-hips-categories)
     * [The HIPs Status](#the-hips-status)
     * [The List of HIPs](#the-list-of-hips)

# Introduction
The HalalChain Improvement Proposals (HIPs) describe standards for the HalalChain platform, including core protocol specifications, networking protocol, consensus algorithms, client APIs and application-level standards and conventions.

# How to Contribute
First read [HIP-1 : HIP Guidelines ](hips/hip-0001.asciidoc). Then clone the repository and add your HIP to it. There is a template HIP file [hip-x.asciidoc](hips/hip-x.asciidoc). You can copy and modify it to create an new HIP. Then submit a Pull Request to the [HIPs repository](https://github.com/halalchain/hips).

# HalalChain Improvement Proposals (HIPs)

## The HIPs Categories
  * **Core** - HalalChain Core related improvements.
  * **Networking** - includes improvements around network protocol specifications.
  * **Interface** - includes improvements around client API/RPC specifications and standards, and also certain language-level standards like method names etc.
  * **Application** - application-level standards and conventions.
  * **Information** - provides general guidelines or information to the HalalChain community, but does not propose a new feature
  * **Process** - describe a process propose to an implementation, they often require community consensus.

## The HIPs Status
  * **Draft** - an HIP that is open for discussion
  * **Accepted** - an HIP that is under designing and planned to be implemented.
  * **Final** - an HIP that has implemented and finalized
  * **Deferred** - an HIP that is not being considered for immediate implementation.

## The List of HIPs

| No. | Title                                                       | Author     | Type         | Status     |
|-----| ----------------------------------------------------------- | ---------- | ------------ | ---------- |
| 1   | [The HIP Guidelines](hips/hip-0001.asciidoc)                | Alex Wu    | information  | Draft      |
| 2   | [Naming Definition & Terminology](hips/hip-0002.asciidoc)   | Alex Wu    | information  | Draft      |
| 3   | [Convert Block header time from uint32 to uint64](hips/hip-0003.asciidoc) | Jame Van  | Core  | Draft      |
| 4   | [DAG Consensusy](hips/hip-0004.asciidoc)                                  | Jin       | Core  | Draft      |
| 5   | [Cuckoo Cycle POW, a Programmatic Proof-of-Work](hips/hip-0005.asciidoc)  | Eric Lee  | Core  | Draft      |

