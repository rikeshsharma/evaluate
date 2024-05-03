# Software Requirement Specification (SRS)

for project **"evaluate"** \
version 0.0.1

prepared by \
Rikesh Sharma \
Apuroop Sigilipalli

date: 29/04/2024

## Table of contents

1. [Introduction](#introduction)
    - [Purpose](#purpose)
    - [Document Conventions](#document-convention)
    - [Intended Audience and Reading Suggestions](#intended-audience-and-reading-suggestions)
    - [Product Scope](#product-scope)
    - [References](#references)
2. [Overall Description](#overall-description)
    - [Product Perspective](#product-perspective)
    - [Product Functions](#product-functions)
    - User Classes and Characteristics
    - Operating Environment
    - Design and Implementation Contraints
    - User Documentation
    - Assumptions and Dependencies
3. External Interface and Requirements
    - User Interface
    - Software Interfaces
    - Communications Interfaces
4. System Requirements
    - Functional Requirements
5. System Scenarios
    - Use-case Diagrams
    - Scenarios
6. System Contraints
    - Important NonFunctional Requirements
7. Other Requirements
8. Appendix

## Revision History

| Name          | Date          | Release Description  | Version     |
|:-------------:|:-------------:|:--------------------:|:-----------:|
| Rikesh        |               |                      |             |
| Apuroop       |               |                      |             |

## Introduction

### Purpose

Internet is a vast source of information. We read articles, watch online tutorial like on youtube and explore the discussions. However there is a no way to evaluate our understanding of the material that we went through. This may lead to superficial/wrong understanding of the material. This project aims to build a tool to assist online learning and provide several ways to test user's understanding of the study material that he studied online be it textual or videos like on youtube.

### Document Convention

Follows standard markdown conventions.

### Intended Audience and Reading suggestions

This document is intended to read by developers, project managers, testers and documentation writers. The rest of the document contains the product description, functional and non-functional requirements, use cases and contraints. Each section of the document can be read independently.

### Product Scope

This product aims to assist research and online learning by providing tool like online note-taking on the go with embedded note taker with the web page. It aims to provide questions on the material that user studied to evalute their understanding and guide them what did not understand hence increasing their depth of understanding and retain their learning. This product aims to utilise AI to assist user's learning.

### References

TODO

## Overall Description

### Product Perspective

This product has dual nature. To assist user in their online learning and research product should be a companion always present with user while they surf the internet and learns. Therefore we aim to provide a browser extension. This browser extension will have features that will assist user to read large articles with less fatigue. It will allow users to take notes on the fly with feature reach note-taking tools at their side. We also aim to provide AI powered note-taking enhancement so user can focus more on learning than worrying. The second nature of this product is a website. Often after learning online their are no means to test what you learn. Internet is filled with alot of information but less to test you that you grasped them. The website will provide questions generated on fly on the basis of articles, youtube videos that one went through, so for example let's say you just watched a youtube video on "First laws of thermodynamics" but you may forget the concepts, to make your understanding better we will generate questions based on the concepts that you just learned, you may try to answer them on the website. This product is your friend that helps you learn and a teacher that test what you learn and guide you in areas of improvement.

TODO Diagrams

### Product Functions

- Web annotation
- Note-taking
- Question generation
- Note enhancements
- Note and question storage
- Website and note mapping
