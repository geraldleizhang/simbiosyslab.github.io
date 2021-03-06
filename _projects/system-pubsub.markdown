---
layout: post
type: system
title: Scaling Publish-Subscribe to a Trillion Topics
date: 2017-09-25 12:00:00
authors:
  - Reza Karimi, Gregory Chockler, Ymir Vigfusson
keywords:
  - Publish-Subscribe
  - pub-sub
---


## What is it?

Increasing number of large scale applications such as online gaming, messaging, social networking which are typically characterized by a large number of participants exchanging messages in a large scale, call for Publish-Subscribe systems that are able to efficiently support a very large set of topics.
 Moreover, the growing number of Internet-connected devices including vehicles,  buildings, home appliances, wearable and mobile devices with large number of built-in sensors and so on, which has a stunning prediction of 50 billion connected devices by 2020, reflects the real need for supporting a huge number of topics by pub-sub systems.
Our system leverages the idea of filtering out the messages being published into topics without any subscribers in order to utilize the resources to deliver the messages published to topics which are of interest. Also, it employs a hybrid memory/disk scheme to store the messages to avoid the slowdown caused by binding to disks.


## Publications

<div class="ui segments">
  <img class="ui centered large rounded image" style="width:80%;" alt="pubsub-poster" src="../resources/projects/pubsub/pubsub-poster.png"  />
  </div>

## Sponsors

<div class="ui segments">
  <img class="ui centered large rounded image" style="width:150px; height:150px;" alt="nsf" src="../resources/projects/pubsub/nsf.png"/>
  <div style="margin-left: auto; margin-right:auto; text-align:center;">NSF CAREER #1553579</div>
  </div>
  <div class="ui segments">
    <img class="ui centered large rounded image" src="../resources/projects/cdr/emory.png"/>
  </div>



## People
<div class="ui four centered doubling cards" style="padding:25px;">

 <a href="http://0xreza.com" class="fluid card">
    <div class="image">
      <img style="width:100%;" src="../resources/people/reza.jpg"/>
    </div>
    <div class="content">
      <div class="header">Reza Karimi</div>
    </div>
  </a>

   <a href="http://www.gchockler.com/" class="fluid card">
    <div class="image">
      <img style="width:100%;" src="https://pure.royalholloway.ac.uk/portal/files/10508164/me.jpg"/>
    </div>
    <div class="content">
      <div class="header">Gregory Chockler</div>
    </div>
  </a>

   <a href="https://ymsir.com" class="fluid card">
    <div class="image">
      <img style="width:100%;" src="../resources/people/ymir.jpg"/>
    </div>
    <div class="content">
      <div class="header">Ymir Vigfusson</div>
    </div>
  </a>

</div>



 
