---
layout: post
title: Dotfuscated Checker
description: A simple GUI tool to simply check for obfuscated assemblies and digital signing at a glance.
keywords: c# programming, dotfuscated checker, obfuscated assemblies, dotfuscator, dotfuschecker, .net obfuscation, dotfuscation checking, digital signing checking
tags: [CSharp, WPF]
comments: true
---

**Dotfuscated Checker** is a simple GUI tool I created with .NET C# and WPF to easily check if the required assemblies from the software build are obfuscated and digitally signed before they can be deployed for a production release. This tool may help Software Quality Assurance Engineers who work with .NET based projects to check for obfuscation at a glance. Other than obfuscation, you can check for digital signing too - no need to manually check File Properties for each of the assemblies.

> **NOTE:** This tool is only tested to work with .NET based assemblies which are being obfuscated using [Dotfuscator](https://www.preemptive.com/products/dotfuscator/overview) software. What this tool does is quite simple; loading the assemblies, check for the present of Dotfuscator attribute in each of the assemblies and check for digital signing too.

### Screenshot (v1.0)

![Dotfuscated Checker v1.0](https://i.imgur.com/2iYCNYO.png)

### Downloads

[**Download Dotfuscated Checker v.10**](https://www.dropbox.com/s/8lss51zhhx0p4xq/DotfuscatedCheckerV1.zip?dl=0) (EXE, 1.46 MB)

Prerequisite: [.NET Framework 4.6.1](https://www.microsoft.com/en-us/download/details.aspx?id=49981)

If you have any problem with the tool e.g. issue, or question to ask, you may drop me an email to: [hello@nrird.xyz](mailto:hello@nrird.xyz)
