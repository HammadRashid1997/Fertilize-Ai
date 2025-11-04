# Fertilize Ai

## Table of Contents
- [Overview](#overview)
- [Tools](#tools)
- [Approach](#approach)
- [Setup](#setup)

## Overview

Fertilize AI is an agritech chatbot built to offer farmers data-driven fertilizer and crop care recommendations via conversational interfaces like WhatsApp. It analyzes your location, soil type, crop, and weather to suggest precise nutrient (N-P-K) ratios, application timings, and sustainable practices. Its goal is to make expert agronomic guidance accessible—24/7, personalized, and actionable—to boost farm productivity and environmental stewardship.

## Tools

- ✅ **Cypress** for robust and scalable E2E test automation
- ✅ **JavaScript** as the scripting language
- ✅ **Visual Studio Code** as the scripting IDE

## Approach

- ✅ **Page Object Model (POM)** structure to keep the tests modular, reusable, and maintainable

## Setup

The first step is to initialize a folder for cypress related projects. This step is optional but recommended.
```
mkdir cypress-e2e-tests
cd cypress-e2e-tests
```

After this you need to initialize a node.js project in your selected direcotry.
```
npm init -y
```

Open a separate terminal and run the following command:
```
npm install cypress --save-dev
```

This command will install all the cypress related modules and dependencies in the project. 

After this command, you need to start the cypress tool. The command to start cypress is:
```
npx cypress open
```


