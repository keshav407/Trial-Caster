# Caster-Web-Application

[![Build Status](https://api.travis-ci.com/mckinley-and-rice/seers-node-api.svg?token=zpzxpp5sTyrL2Zc9qQ6m&branch=master)](https://travis-ci.org/mckinley-and-rice/Seers-api.)

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier) [![Greenkeeper badge](https://badges.greenkeeper.io/mckinley-and-rice/mcrice-ems-api.svg?token=e1c88747bafbd4d8bf95cba8d7204f564832677ebd6ed374e99a2805dc0fafb1&ts=1577115667617)](https://greenkeeper.io/)

## Introduction

**![alt text](https://caster.so/static/images/logo.svg)**

**[Caster](https://caster.so) Is A Web Based Quiz application available on ios and android it consists**
```sh
[Caster] (https://caster.so) Is A Web Based Quiz application available on ios and android it consists
of 4 different casts which depict a certain type of quiz having one right answer choice, which are as follow
+---2-Choiced
|   |       ox
|
+---3-Choiced
|   |       3-choiced
|
+---4-choiced
|   |       4-choiced with text
|   |       4-choiced without text
|
The categories of a cast are as follow
|   |       fun
|   |       popular
|   |       entertainment
|   |       music
|   |       web_series
|   |       sports
|   |       beauty
|   |       events
|
The timeline of a cast states is as follow
|   |       ready
|   |       in-progress
|   |       closed
|   |       result-announced
|
The users compete among themselves by registering on the platform and by playing/answering in a in-progress (ongoing) cast by bidding certain mic points and would be rewarded the double of the points invested, if they get the answer right
which is annoucned when the cast reaches a result-announced state

Stories are created by the caster admin, which talk about a certain trending topic, each story consists of a title and describes the purpose of it
Moreover all stories consist of related casts and stories, so if a user finds a certain story interesting they could participate in its relevant cast or
read up on the related stories
```

## Installation
**With [next](https://nextjs.org) [installed](https://nextjs.org/learn/basics/getting-started/setup):**


```sh
$ npm install
$ npm run dev
```

## File Structure

```sh
|   .next
|   .vscode
|   apk
|   caster-android
|   node_modules
|   .eslintrc
|   .gitignore
|   manifest.webmanifest
|   next-seo.config.js
|   next.config.js
|   package-lock.json
|   package.json
|   README.md
|   store.js
|
+---actions
|   |      actionTypes.js
|   |      index.js
|
+---components
|   +---Banner
|   |      Banner.css
|   |      Banner.js
|   +---BetSlider
|   |      BetSlider.css
|   |      BetSlider.js
|   +---CardFullWidth
|   |      CardFullWidth.css
|   |      CardFullWidth.js
|   |       :
|   +---Story
|   |      Story.css
|   |      Story.js
|   +---StoryDetails
|   |      StoryDetails.css
|   |      StoryDetails.js
|   +---Wrapper
|   |      Wrapper.css
|   |      Wrapper.js
|
+---lib
|   |       constants.js
|   |       helpers.js
|   |       http-calls.js
|   |       with-redux-store.js
|
+---pages
|   +---cast-listing
|   |   +---state
|   |   |   |       [link].js
|   |       [link].js
|   +---cast-quiz
|   |      [id].js
|   +---story-page
|   |      [link].js
|   |       :
|   |       welcome-quiz.js
|   |       welcome.js
|   |       wish-list.js
|   |
|   +---public\static
|   |       fonts
|   |       images
|   |       favicon.js
|   |       manifest.json
|   |       robots.txt
|   |
|   +---reducers
|   |       castReducer.js
|   |       faqReducer.js
|   |       index.js
|   |       :
|   |       storyReducer.js
|   |       transactionReducer.js
|   |       userReducer.js
|   |
|   +---styles
|   |       leaderboard.css
|   |       main.css
|   |       my-comments.css
|   |       my-page.css
|   |       sharemedia.css
|   |       storyview.css
|   |       welcome.css
```
