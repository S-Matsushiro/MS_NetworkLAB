---
title: "Set up the eve-ng on Hyper-v"
date: 2023-07-23T14:39:53+09:00
draft: false
weight: 100
---

# 概要

近年、サーバを物理サーバとして運用する機会は減少している。VMwareなどの仮想プラットフォーム上で何台ものサーバを構築し、ハードウェア資源を効率よく利用するケースが飛躍的に増加している為である。

ネットワークでも、**仮想化技術**を活用してネットワーク演習環境を構築し、仮想環境上で検証することが一般化されてきている。例えば以下のようなネットワークエミューレーション環境やツールがある。
- Common Open Research Emulator(CORE)
- NS3 Simulator
- kathara
- FRRouting(FRR)
- Mininet
- CML2
- GNS3
- eve-ng

これらのシュミレータ及びエミュレータはSDNやその他の技術用途によって使い分けるが、今回の目的はNW機器を仮想環境上(VMware,VirtualBox,Hyper-v,Docker等)で実装し、各々の機器を実装することが目的の為、その手順について解説する。
