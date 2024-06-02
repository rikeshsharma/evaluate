# Software Requirement Specification (SRS)

for project **"evaluate"** \
version 0.0.1

prepared by \
Rikesh Sharma \
Apuroop Sigilipalli \
Ajay Dama

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
| Ajay          |               |                      |             |

## Introduction

### Purpose

The software aims to enhance online learning by providing a tool to evaluate users' comprehension of various materials, including articles, video tutorials, and discussion forums. By offering multiple methods to assess understanding, this tool helps prevent superficial or incorrect interpretations of the content studied online.

### Document Convention

Follows standard markdown conventions.

### Intended Audience and Reading suggestions

This document is intended for developers, project managers, testers, and documentation writers. It includes the product description, functional and non-functional requirements, use cases, and constraints. Each section can be read independently, providing a comprehensive guide for understanding and implementing the software.

### Product Scope

This product is designed to enhance research and online learning by offering tools such as an embedded online note-taking feature within web pages. It also aims to evaluate users' understanding by providing questions on the material they have studied, helping to identify areas of misunderstanding and thereby deepening their comprehension and retention. It aims to provide wide range of accessibility tools that makes online learning easier and less stressful. Additionally, the product will leverage AI to assist users in their learning process.

### References

TODO

## Overall Description

### Product Perspective

This product serves a dual purpose: it assists users in their online learning and research. To be a constant companion during internet browsing, we are developing a browser extension. This extension will feature tools to help users read large articles with less fatigue and allow for on-the-fly note-taking with feature-rich tools. Additionally, we aim to incorporate AI-powered enhancements to streamline the note-taking process, enabling users to focus more on learning.

The second aspect of this product is a dedicated website. Often, there are limited means to test the knowledge acquired from online learning. While the internet is a vast source of information, it lacks tools for assessing comprehension. Our website will generate questions in real-time based on the articles and YouTube videos users have engaged with. For instance, after watching a YouTube video on "The First Law of Thermodynamics," users may forget certain concepts. Our platform will create questions based on the content to reinforce understanding, allowing users to answer these questions and identify areas for improvement.

This product acts as both a learning companion and a teacher, helping users enhance their knowledge and test their understanding, guiding them towards better retention and deeper comprehension.

TODO Diagrams

### Product Functions

- Web annotation
- Note-taking
- Question generation
- Note enhancements
- Note and question storage
- Website and note mapping
