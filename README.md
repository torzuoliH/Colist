# Colist
Collaborative list built with Angular / Onsen

## Installation

`$ npm install`

`$ mv conf/firebase.sample.js conf/firebase.js`

Edit Firebase following your Firebase setup

## Firebase Setup

**Rules**

`{
  "rules": {
    ".read": true,
    ".write": true
  }
}`

**Data**

`{
  "notes" : {}
}`