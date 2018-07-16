---
layout: default
description: ''
---

## Introduction

<p style="text-align:justify;">
Recent advances at the intersection of natural language processing and computer vision have
made incredible progress, from being able to generate natural language descriptions of images
and videos, to answering questions about them, to even holding free-form conversations
about visual content! The challenge now is to extend this progress to embodied agents that
take actions and interact with their visual environments.
</p>

<p style="text-align:justify;">
This tutorial will provide a comprehensive yet accessible introduction to the key
innovations that have driven progress in language and vision modeling (such as
multi-modal pooling, visual and co-attention, dynamic network composition,
methods for incorporating external knowledge and cooperative/adversarial games).
We will then discuss some of the challenges in building models for tasks that combine
language, vision, and actions, and discuss recently-released interactive 3D
environments that can be used for these (such as House3D, HoME,
MINOS, Matterport3D Simulator, Gibson, Thor &amp; Chalet).
</p>

{% include tasks.html %}

## Slides

- [Peter] **Introduction** [[pptx][intro]]
- [Peter] **Neural Building Blocks**
    + CNNs and RNNs; captioning, VQA [[pptx][blocks]]
    + Attention mechanisms [[pptx][attention]]
- [Qi] **Neural Building Blocks (continued) and Tricks** [[pptx][p2.pptx]] [[pdf][p2.pdf]]
    + Multi-modal Pooling
    + Dynamic Network Composition
    + External Knowledge / Memory
    + Engineering Tricks
- [Abhishek] **Reinforcement Learning in Language & Vision** [[keynote][rl.key]] [[pdf][rl.pdf]]
    + Train/test discrepancy in language generation
    + Optimizing for metrics
    + Adversarial training
    + Downstream task-based training & evaluation
- **Embodied Agents & Environments**
    + [Abhishek] Introduction and EmbodiedQA [[keynote][embodied_1.key]] [[pdf][embodied_1.pdf]]
    + [Peter] Vision-Language Navigation [[pptx][vln]]
    + [Abhishek] Comparing environments, and next steps [[keynote][embodied_3.key]] [[pdf][embodied_3.pdf]]

## Presenters

<table class='organizer-pics-four'>
    <tr>
        <td>
        <img width="200" class='im-speaker-pic' src='images/peter.jpg' alt='peter'>
        </td>
        <td>
        <img width="200" class='im-speaker-pic' src='images/abhishek2.jpg' alt='abhishek'>
        </td>
        <td>
        <img width="200" class='im-speaker-pic' src='images/qi.jpg' alt='qi'>
        </td>
    </tr>
    <tr>
        <td><a href='http://www.panderson.me/'>Peter Anderson</a> <br>
        Australian National University / Macquarie University</td>

        <td><a href='https://abhishekdas.com'>Abhishek Das</a> <br>
        Georgia Tech </td>

        <td> <a href='http://www.qi-wu.me/'>Qi Wu</a> <br>
        The University of Adelaide</td>
    </tr>
</table>

[intro]: https://drive.google.com/open?id=1THAdQjpONm_jwuJ349TZvXJoFbXrfIln
[blocks]: https://drive.google.com/open?id=1ZMw5GHAYrQfNXy2v06rU3K6GxHixXXSN
[attention]: https://drive.google.com/open?id=1Cgr4BuOkSGNiqEhLB5yPNWd4Wp3AwZYu
[p2.pptx]: https://drive.google.com/open?id=11xi9_kVyDObJynsw8N5qefkoNqSho49d
[p2.pdf]: https://drive.google.com/open?id=1uvQ-qtMwc5CV5kkyGHj2ZB26uSMgbz84
[rl.key]: https://drive.google.com/open?id=1s67Y5rc8RYTD4WGvUg05KAQ3VYiNdPEy
[rl.pdf]: https://drive.google.com/open?id=1CljRRNuKs2ekUt7RArAoCCe0htUmnPpE
[embodied_1.key]: https://drive.google.com/open?id=1uvSg5rY98qtNu-veylfrZ-jsG9vovmoX
[embodied_1.pdf]: https://drive.google.com/open?id=1G9TMQT6Rx-ekTO0w30iYd8yS4noDw3Nw
[vln]: https://drive.google.com/open?id=15QmLgcndu4bYMCxVpEA8EcvEEDILVmmq
[embodied_3.key]: https://drive.google.com/open?id=1KMCY2PDLs99DCEdfwSmIwBpeXNs68n79
[embodied_3.pdf]: https://drive.google.com/open?id=1NuX64KqJPBrzcfk83MXQcAnwhTo68DRt