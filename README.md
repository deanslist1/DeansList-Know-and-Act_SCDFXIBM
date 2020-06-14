# DeansList_integratedapp_SCDFXIBM


Hi! Our team name is Deans List, comprising of members Teo Zhen Jie, Marvin Pranajaya, Joshua Toh and Ivan Tan.


## Contents

1. [Short description](#short-description)
1. [Demo video](#demo-video)
1. [The architecture](#the-architecture)
1. [Long description](#long-description)
1. [Getting started](#getting-started)
1. [Running the tests](#running-the-tests)
1. [Live demo](#live-demo)
1. [Built with](#built-with)
1. [Acknowledgments](#acknowledgments)

## Short description

### What's the problem?

Covid-19 and the Australian wildfires are just 2 examples of how sheer complacency, ignorance and misinformation can give rise to disastrous consequences. This, combined with the increasingly pervasive threat of fake news to society, can potentially undermine our very fragile social systems. In the case of the Australian wildfires, a lack of accurate and reliable information on locations of fire may have made evacuation efforts less spontaneous. In the case of Covid-19, some citizens may not understand the various nuances of this virus and their actions may jeopardize the health of entire communities. In both cases, even if citizens are well-educated about the actions they ought to take, they they lack the decisiveness to act immediately, making the effect of solutions less immediate. 

### How can technology help?

Technology can help pool and filter all relevant and accurate infomation that may be of interest to a member of public and present them in a convenient and cogent way. Also, technology can eliminate the existential intertia that citizens have to act by immediately providing instructions on what they can do to hekp improve the situation, be it through spreading awareness on social media or avoid heading to Covid-19 clusters to give an example. 

### The idea

Providing an integrated, one-stop platform in the form of a mobile app for citizens to keep up-to-date with important information (such as the Pollution Standard Index, covid-19 clusters etc) can offer much convenience and minimise confusion within the general public. This is critical for communities and nations to be on the same page when identifying and solving issues, improving civil defence and community resilience. Prompting and providing instructions through the app to the users would raise awareness and improve decisiveness, aiding the SCDF in delivering a prompt response to any given situation.  

## Demo video

[![Watch the video](https://github.com/Code-and-Response/Liquid-Prep/blob/master/images/IBM-interview-video-image.png)](https://youtu.be/vOgCOoy_Bx0)

## The architecture

![Video transcription/translation app](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png)

**Curated Content** 
1. The user opens the app and is directed to the dashboard. Multiple sets of content will be displayed with local databases, open-source APIs and Watson discovery as the data source.
2. The user can indicate whether he/she enjoys seeing a specific set of content by pressing the button on the bottom right corner of the content box. Green indicates interest while red indicates non-interest.
3. User preference is fed into AutoAI to predict what content the user enjoys seeing. Curated content will then be output for user to indicate interest again. Cycle continues. 

**Chatbot**
1. User enters in question in chatbox
2. Watson assistant processes question with watson discovery and other APIs as data source. 
3. An answer is output to user. 

**Provision of instructions**
1. Once users tap on the curated content, they will be brought to a page on instructions on how they can help.
2. User will also be prompted to share content through stories on Instagram, or posts on Facebook.
3. If user allows, webhook to social media app will bring user to the app to share said stories/posts.
4. Notifications will be generated to urge users to raise awareness even when app is not in use.

## Long description

[Detailed description of our problem and solution](https://docs.google.com/document/d/1jlnSAGuVTAoucwC5s337T9nCjMMMrKKHBf_vb2qPA18/edit?usp=sharing)

## Getting started
No materials will be needed as we

### Prerequisites

What things you need to install the software and how to install them

```bash
dnf install wget
wget http://www.example.com/install.sh
bash install.sh
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be, for example

```bash
export TOKEN="fffd0923aa667c617a62f5A_fake_token754a2ad06cc9903543f1e85"
export EMAIL="jane@example.com"
dnf install npm
node samplefile.js
Server running at http://127.0.0.1:3000/
```

And repeat

```bash
curl localhost:3000
Thanks for looking at Code-and-Response!
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why, if you were using something like `mocha` for instnance

```bash
npm install mocha --save-dev
vi test/test.js
./node_modules/mocha/bin/mocha
```

### And coding style tests

Explain what these tests test and why, if you chose `eslint` for example

```bash
npm install eslint --save-dev
npx eslint --init
npx eslint sample-file.js
```

## Live demo

[Chatbot](https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=eu-gb&integrationID=e8aee7e8-f058-4974-a57f-1e14bc736b1b&serviceInstanceID=9758eca1-bbf1-410b-bf41-149706ec94d1)


## Built with

* [IBM Cloudant](https://cloud.ibm.com/catalog?search=cloudant#search_results) - The NoSQL database used
* [IBM Cloud Functions](https://cloud.ibm.com/catalog?search=cloud%20functions#search_results) - The compute platform for handing logic
* [Flutter](https://flutter.dev/)- To develop the app

## Acknowledgments

* Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).


