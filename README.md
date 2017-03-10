
# סטאק ג'אווה סקריפט מאפס

[![Build Status](https://travis-ci.org/verekia/js-stack-from-scratch.svg?branch=master)](https://travis-ci.org/verekia/js-stack-from-scratch)
[![Release](https://img.shields.io/github/release/verekia/js-stack-from-scratch.svg?style=flat-square)](https://github.com/verekia/js-stack-from-scratch/releases)
[![Dependencies](https://img.shields.io/david/verekia/js-stack-boilerplate.svg?style=flat-square)](https://david-dm.org/verekia/js-stack-boilerplate)
[![Dev Dependencies](https://img.shields.io/david/dev/verekia/js-stack-boilerplate.svg?style=flat-square)](https://david-dm.org/verekia/js-stack-boilerplate?type=dev)
[![Join the chat at https://gitter.im/js-stack-from-scratch/Lobby](https://badges.gitter.im/js-stack-from-scratch/Lobby.svg)](https://gitter.im/js-stack-from-scratch/Lobby)

[![ריאקט](/img/react-padded-90.png)](https://facebook.github.io/react/)
[![רידאקס](/img/redux-padded-90.png)](http://redux.js.org/)
[![ריאקט ראוטר](/img/react-router-padded-90.png)](https://github.com/ReactTraining/react-router)
[![פלו](/img/flow-padded-90.png)](https://flowtype.org/)
[![ESLint](/img/eslint-padded-90.png)](http://eslint.org/)
[![גסט](/img/jest-padded-90.png)](https://facebook.github.io/jest/)
[![יארן](/img/yarn-padded-90.png)](https://yarnpkg.com/)
[![וובפאק](/img/webpack-padded-90.png)](https://webpack.github.io/)
[![בוטסראפ](/img/bootstrap-padded-90.png)](http://getbootstrap.com/)

ברוכים הבאים למדריך המודרני שלי לבניית סטאק ג'אווה סקריפט:  **סטאק ג'אווה סקריפט מאפס**

> 🎉 **זו גרסה 2 של המדריך, קיימים שינויים משמעותיים מאז גרסת 2016 [שינויים](/CHANGELOG.md)**

זה מדריך ישר ולעניין להרכבת סטאק ג'אווה סקריפט. המדריך דורש ידע כללי בתכנות, וידע בסיסי בג'אווה סקריפט. **המדריך מתמקד בחיבור של כלים ביחד** ביחד עם **הדוגמה הפשוטה ביותר** לכל כלי. אפשר לחשוב על המדריך הזה כ*דרך לכתיבת בוילרפלייט משלכם מאפס*. מכיוון שמטרתה של המדריך הוא הרכבה של כמה וכמה כלים שונים, אני לא יכנס לפרטי פרטים לגבי איך שכל כלי עובד בפני עצמו. נע לגשת לדוקומנטציה ש כל כלי או להסתכת על מדריכים אחרים בשביל לקבל ידע נרחב יותר עליהם.

כמובן שאינכם צריכים להשתמש בכל הסטאק הזה בשביל לבנות אתר ווב פשוט עם קצת ג'אווה סקריפט (שילוב של ברווסרייי או וובפאק + בבל + גייקויירי זה פספיק בשביל לכתוב ES6 בקבצים שונים) אבל אם אתם רוצים לבנות אפליקציית ווב סקיילבילית, וצריכים קצת עזרה בהרכבתה, אז המדריך הזה יעשה את העבודה מעולה בשבילכם.

A big chunk of the stack described in this tutorial uses React. If you are beginning and just want to learn React, [create-react-app](https://github.com/facebookincubator/create-react-app) will get you up and running with a React environment very quickly with a pre-made configuration. I would for instance recommend this approach to someone who arrives in a team that's using React and needs to catch up with a learning playground. In this tutorial you won't use a pre-made configuration, because I want you to understand everything that's happening under the hood.

Code examples are available for each chapter, and you can run them all with `yarn && yarn start`. I recommend writing everything from scratch yourself by following the **step-by-step instructions** though.

Final code available in the [JS-Stack-Boilerplate repository](https://github.com/verekia/js-stack-boilerplate), and in the [releases](https://github.com/verekia/js-stack-from-scratch/releases).

Works on Linux, macOS, and Windows.

## Table of contents

[01 - Node, Yarn, `package.json`](/tutorial/01-node-yarn-package-json.md#readme)

[02 - Babel, ES6, ESLint, Flow, Jest, Husky](/tutorial/02-babel-es6-eslint-flow-jest-husky.md#readme)

[03 - Express, Nodemon, PM2](/tutorial/03-express-nodemon-pm2.md#readme)

[04 - Webpack, React, HMR](/tutorial/04-webpack-react-hmr.md#readme)

[05 - Redux, Immutable, Fetch](/tutorial/05-redux-immutable-fetch.md#readme)

[06 - React Router, Server-Side Rendering, Helmet](/tutorial/06-react-router-ssr-helmet.md#readme)

[07 - Socket.IO](/tutorial/07-socket-io.md#readme)

[08 - Bootstrap, JSS](/tutorial/08-bootstrap-jss.md#readme)

[09 - Travis, Coveralls, Heroku](/tutorial/09-travis-coveralls-heroku.md#readme)

## Coming up next

Setting up your editor (Atom first), MongoDB, Progressive Web App.

## Translations

If you want to add your translation, please read the [translation recommendations](/how-to-translate.md) to get started!

### V2

Your link here soon ;)

Check out the [ongoing translations](https://github.com/verekia/js-stack-from-scratch/issues/147).

### V1

- [中文](https://github.com/pd4d10/js-stack-from-scratch) by [@pd4d10](http://github.com/pd4d10)
- [Italiano](https://github.com/fbertone/js-stack-from-scratch) by [Fabrizio Bertone](https://github.com/fbertone)
- [日本語](https://github.com/takahashim/js-stack-from-scratch) by [@takahashim](https://github.com/takahashim)
- [Русский](https://github.com/UsulPro/js-stack-from-scratch) by [React Theming](https://github.com/sm-react/react-theming)
- [ไทย](https://github.com/MicroBenz/js-stack-from-scratch) by [MicroBenz](https://github.com/MicroBenz)

## Credits

Created by [@verekia](https://twitter.com/verekia) – [verekia.com](http://verekia.com/).

License: MIT
