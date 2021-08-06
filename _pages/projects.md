---
title:  "Projects"
layout: splash
permalink: /Projects/
author_profile: true
comments: true
---


<h2>A p2p e-Cash System</h2>
<h3>Abstract</h3>
<p>This project implements a purely peer-to-peer version of electronic cash would allow online
payments to be sent directly from one party to another without going through a financial
institution. It might initially seem like a problem to not have a centralized system monitor
and audit the transactions of users, and as digital signatures provide part of the solution,
the main benefits are lost if a trusted third party is still required to prevent double-spending.
We propose a solution to the double-spending problem using a peer-to-peer network. The
network timestamps transactions by hashing them into an ongoing chain of hash-based proof-
of-work, forming a record that cannot be changed without redoing the proof-of-work. The
longest chain not only serves as proof of the sequence of events witnessed, but proof that it
came from the largest pool of CPU power. As long as a majority of CPU power is controlled
by nodes that are not cooperating to attack the network, they'll generate the longest chain and
outpace attackers. The network itself requires minimal structure. Messages are broadcast on a
best effort basis, and nodes can leave and rejoin the network at will, accepting the longest
proof-of-work chain as proof of what happened while they were gone. The project typically
utilizes a Glassfish-enabled server to run the wallet system over a web browser, wherein the
users can utilize a secure peer-to-peer transaction system to buy, sell, and send e-Cash to
fellow users who are also utilizing the platform. The transactions can, if needed however, be
available to the admin on an Open Ledger system but only through obtaining the user’s ID and
key, which by extension means that, for legal purposes the user can give consent to have his
transactions verified. But otherwise, these details are highly secure. If the idea shown in this
project were implemented using real cash, it would be a secure, reserved, and trusted platform
to buy, sell and share bitcoins among each other.</p>

Request for complete document [here.](mailto:tanmayi.jandhyala@gmail.com)



<h2>Implementing Data Deduplication for DropBox and OpenStack</h2>
<h3>Description</h3>
<p>Files that are stored on the cloud often are vulnerable to security threats as
they are put over to the internet. Often, when a local cloud is deployed by a
closed organisation, and utilised for file storage, the problem of a security
breach always exists. The main objective of this project is to implement the
Advanced Encryption Standard algorithm to encrypt files on the local file
system, and then integrate these encryption techniques to Google DropBox
first, and then to Openstack cloud. OpenStack is set up on a cluster of systems and
a live cloud is deployed on it. The cloud will contain the nodes, configured on
the HPC lab node cluster: Controller, Compute, Block, and Object Storage.
Setting up Openstack is a sensitive and tardy process. Once it is set up, the
Openstack dashboard (Horizon) is fired up to access the ‘Compute’ feature,
which is what I will be utilising for my project to upload and download files to
the local cloud deployed in the lab. </p>

Request for complete report [here.](mailto:tanmayi.jandhyala@gmail.com)


<h2>An Educational Social Engineering attack using Kali Linux</h2>
<h3>Description</h3>
<p>Researchers have enunciated the capability to use malware attacks to disrupt critical
infrastructure sectors-including power, water, transportation, and communication
systems-for years. When these attacks take place, effects are felt not only in military,
but also in the physical world, making them especially threatening.
Studying these malwares, the schema in this project has been structured. The aim of
the schema is to get a picture of what the victim is working on in his system. It has
been done on a Linux platform, utilising various tools for designing the malicious code
required to make the attack. The code is camouflaged behind an image, which, upon
clicking, executes it by downloading it from a webserver hosted by the attacker. The
image is sent through an e-mail by altering its signature so that there is no trouble in
sending it to the victim. Care is taken so as to ensure that the code cannot be detected
by antivirus on the victim’s computer and our purpose is fulfilled successfully. </p>