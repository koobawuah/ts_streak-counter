# `@koobawuah/ts_streak-counter` - a basic streak counter 

A streak counter for the browser, inspired by Duolingo - written in TypeScript and meant for the browser (uses 'localStorage').

## Install 

```shell
npm install @koobawuah/ts_streak-counter
```

## Usage 

```
import {streakCounter} from '@koobawuah/ts_streak-counter'

const today = new Date() 
const streak - streakCounter(localStorage, today)
// streak returns an object:
// {
//      currentCount: 1,
//      lastLoginDate: "11/11/2022",
//      startDate: "11/11/2022",
// }
```
