---
title: Maverics Command Line
date: 2016-04-20T00:00:00.000+00:00
categories: []
description: A portable device for epileptic patients.
banner_image: "/uploads/2019/05/10/wave3.jpeg"
sub_heading: Command Line tools for integrating on premises identity systems
tags:
- CLI
- Windows
- Active Directory
- Mac
- Identity
slug: ''

---
## Maverics CLI

The Maverics CLI is used to run various plugins and integrations with target identity systems running on premises. There are a variety of integration options, the most common being Active Directory and Oracle Identity Management. 

You create secure connections to your target identity system, read out identity data including users and groups, configurations, policies for controlling user access through group memberships, and integrations between your source system and your target. 

## Platform Support

The CLI is designed to run on any platform - Windows, Mac, and Linux. The CLI doesn't need to know or care about what platform your source system runs on, although in some cases there are separate integration components that must be installed on the source system - on a domain controller, for example - and so will have certain OS level dependencies that must be satisfied. The CLI will handle the install and configuration of those components for you, and hopefully the experience is transparent.

## Use Cases

* Discover schemas and objects stored in Active Directory.
* Read out users, groups, group policies, group memberships, access policies, and domain policies.
* Migrate passwords from Active Directory to a target cloud identity system.
* Encrypt passwords and transition users to stronger authentication schemes including MFA.