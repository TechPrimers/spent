<img src="/images/logo.png" style="width: 50%" alt="spent logo" />
 
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![Build Status](https://travis-ci.com/TechPrimers/spent.svg?branch=master)](https://travis-ci.com/TechPrimers/spent)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/ddac01ec34cd4c41a2bbed7505953736)](https://www.codacy.com/app/MovingToWeb/spent?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=TechPrimers/spent&amp;utm_campaign=Badge_Grade)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/techprimers/spent.svg)](https://github.com/techprimers/spent/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/techprimers/spent.svg)](https://github.com/techprimers/spent/issues) 
[![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/techprimers/spent.svg?maxAge=2592000)]() 
[![GitHub forks](https://img.shields.io/github/forks/techprimers/spent.svg)](https://github.com/techprimers/spent/network)

# Open Source Project for tracking all your spends based on your Bank Statements
In India, we have so many banks and with the movement of Digital Banks and Wallets, we don't have a way to reconcile our income, spend and savings. The idea of this project is to create a personalized way to track your spend to identify how much you **spent** based on your bank statements

Table of Contents
=================

   * [Features](#features)
   * [Upcoming](#upcoming)
   * [Structure](#structure)
   * [Architecture](#architecture)
      * [Microservices Patterns](#microservices-patterns)
      * [Flow](#flow)
   * [Start UI](#start-ui)

Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc)

## Features

## Upcoming
- Read SBI Bank Statements in CSV format
- Read HDFC Bank Statements in CSV format
- Read Citi Bank Statements in CSV format
- Read Kotak Mahindra Bank Statements in CSV format

## Structure
- `spent-react-ui` - UI for the Spent Dashboard
- `spent-server` - Micronaut based server which extracts, transforms and loads into a local postgresql database

## Architecture
### Microservices Patterns
- Event Sourcing and CQRS. Reference eg:- [Eventuate Kanban board](https://github.com/eventuate-examples/es-kanban-board)

### Flow
<img src="/images/architecture.png" alt="architecture" />

## Start UI
- Start the React UI using the following command
```
cd spent-react-ui
npm start
```
