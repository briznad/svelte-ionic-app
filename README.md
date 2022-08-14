
<h1 align="center"> Ionic Svelte Demo </h1> <br>
<p align="center">
  <a href="https://ionicsvelte.firebaseapp.com">
    <img alt="IonicSvelte" title="IonicSvelte" src="https://github.com/Tommertom/svelte-ionic-app/raw/main/src/static/assets/svelte-ionic-logo.png" width="350">
  </a>
  
</p>
<br>
<p align="center">
  A showcase app for all Ionic UI elements. Supercharged by Svelte and Vite.
</p>
<p align="center">
  With handy tool to see the actual code in all popular frameworks - Svelte, Vue, React, Stencil, VanillaJS and even Angular!
</p>
<br>
<p align="center">
  <a href="https://ionicsvelte.firebaseapp.com">
    <img alt="Download as PWA" title="PWA power" src="https://github.com/Tommertom/svelte-ionic-app/raw/main/src/static/assets/img/pwa-download.png" width="140"  target="_blank">
  </a>
</p>
Click the PWA Launch button to see this app live in action - and install as PWA on your desktop or mobile!
<br><br>

[![All Contributors](https://img.shields.io/badge/all_contributors-6-orange.svg?style=flat-square)](./CONTRIBUTORS.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![MIT license](https://img.shields.io/greasyfork/l/407466?style=flat-square)](./LICENSE.md)
[![Forks](https://img.shields.io/badge/forks-35-yellowgreen?style=flat-square)](https://github.com/Tommertom/svelte-ionic-app/fork)
[![Forks](https://img.shields.io/github/stars/tommertom/svelte-ionic-app?style=flat-square)](https://img.shields.io/github/stars/tommertom/svelte-ionic-app?style=flat-square)
[![Forks](https://img.shields.io/badge/watching-15-orange)](https://img.shields.io/badge/watching-15-orange)




<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Introduction](#introduction)
- [Screenshots](#screenshots)
- [All starters - how to get started quickly!](#all-starters---how-to-get-started-quickly)
- [PWA Interface - easing the PWA work in your app](#pwa-interface---easing-the-pwa-work-in-your-app)
- [PLEASE NOTE - MIGRATION PLANNED](#please-note---migration-planned)
- [How I got started with this rebuild: the basic steps performed](#how-i-got-started-with-this-rebuild-the-basic-steps-performed)
- [REPLS](#repls)
- [Todo](#todo)
- [Issues - help needed/workaround provided](#issues---help-neededworkaround-provided)
- [Things to do maybe one day...](#things-to-do-maybe-one-day)
- [Things not being implemented](#things-not-being-implemented)
- [Acknowledgements](#acknowledgements)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Introduction
A showcase app for all Ionic UI elements - up to Ionic 6!!! Use this app to try-out the elements you like for your app, and then navigate directly to the API docs or the source code.

Published as web app: https://ionicsvelte.firebaseapp.com

*Open developer tools to see developer info in the console.log*

Design objectives
- Use all Ionic 6 UI elements
- Fast bundler using VITE
- Ease PWA configuration with good documentation - using zero-config Vite (https://vite-plugin-pwa.netlify.app/)
- Deployable as PWA
- File based router (using Roxy/Routify)
- aligned as much as possible to the Ionic documentation for other integrations
- supporting other framework developers through source-code viewing

As far as I can see now, the current new version is getting there pretty close! 

Hint: try responsive design of the app and ionic UI magic by using various devices or the Chrome developer view: iOS, Android's material design and fullscreen desktop responsiveness guaranteed!

## Screenshots
<table>
  <tr>
    <th>Intro</th>
    <th>Component menu</th>
    <th>Sourcecode</th>
  </tr>
  <tr>
    <td align="center">
<img alt="IonicSvelte" title="IonicSvelte" src="screenshots/localhost_3000_folder_Inbox(iPhone SE).png" width="65%" ></td>
    <td align="center"><img alt="IonicSvelte" title="IonicSvelte" src="screenshots/localhost_3000_folder_Inbox(iPhone SE) (1).png" width="45%"></td>
    <td align="center"><img alt="IonicSvelte" title="IonicSvelte" src="screenshots/localhost_3000_folder_Inbox(iPhone SE) (2).png" width="45%"></td>
    </tr> 
</table>

<table>
  <tr>
<th>Progress bar</th>
<th>Icons</th>
<th>PWA IOS install</th>
  </tr>
  <tr>
       <td align="center"><img alt="IonicSvelte" title="IonicSvelte" src="screenshots/localhost_3000_components_Card(iPhone SE) (1).png" width="45%"></td>
     <td align="center"><img alt="IonicSvelte" title="IonicSvelte" src="screenshots/localhost_3000_components_Card(iPhone SE).png" width="45%"></td>
       <td align="center"><img alt="IonicSvelte" title="IonicSvelte" src="screenshots/localhost_3000_components_Badge(iPhone XR).png" width="45%"></td>
  </tr> 
</table>

More screens: https://ionicsvelte.firebaseapp.com

## All starters - how to get started quickly!
If you want to get started with Ionic, Svelte and Vite, just use one of the starters:

* Blank demo 
  - https://github.com/Tommertom/svelte-ionic-blank-demo
  - `npx degit Tommertom/svelte-ionic-blank-demo svelte-ionic-blank-demo`
  - Online playground - https://codesandbox.io/s/github/Tommertom/svelte-ionic-blank-demo

* Tabs demo 
  - https://github.com/Tommertom/svelte-ionic-tabs-demo
  - `npx degit Tommertom/svelte-ionic-tabs-demo svelte-ionic-tabs-demo`
  - Online playground - https://codesandbox.io/s/github/Tommertom/svelte-ionic-tabs-demo

* Sidemenu demo 
  - https://github.com/Tommertom/svelte-ionic-sidemenu-demo
  - `npx degit Tommertom/svelte-ionic-sidemenu-demo svelte-ionic-sidemenu-demo`
  - Online playground - https://codesandbox.io/s/github/Tommertom/svelte-ionic-sidemenu-demo

* Mystarter demo - taking photo with Capacitor 
  - https://github.com/Tommertom/svelte-ionic-mystarter-demo
  - `npx degit Tommertom/svelte-ionic-mystarter-demo svelte-ionic-mystarter-demo`
  - Online playground - https://codesandbox.io/s/github/Tommertom/svelte-ionic-mystarter-demo

* List demo 
  - https://github.com/Tommertom/svelte-ionic-list-demo
  - `npx degit Tommertom/svelte-ionic-list-demo svelte-ionic-list-demo`
  - Online playground - https://codesandbox.io/s/github/Tommertom/svelte-ionic-list-demo

* Conference demo - (sort of...check its README) 
  - https://github.com/Tommertom/svelte-ionic-conference-demo
  - `npx degit Tommertom/svelte-ionic-conference-demo svelte-ionic-conference-demo`
  - Online playground - https://codesandbox.io/s/github/Tommertom/svelte-ionic-conference-demo

When using the online playground - make sure you pop-out the render window to see the demo in full size.

Would you like to start any of the above in your favorite framework (React, Vue or Angular), just use the Ionic CLI to start the app: `ionic start --type=angular|vue|react`. Ionic CLI is easy to install: `npm i -g @ionic/cli`. https://ionicframework.com/docs/cli/commands/start.

Or clone the repo of the full-demo-app to play with its code:

```bash
npx degit Tommertom/svelte-ionic-app svelte-ionic-app
cd svelte-ionic-app
npm i
npm run dev
```

## PWA Interface - easing the PWA work in your app
To help you managing state of the service worker and the various events, a simple svelte store is provided for (`lib/pwa.ts`). This store wraps the various events of the service worker in a readable store and a number of derived stores so you can easily listen to various events.

The following derived stores are implemented:
- `needRefresh`:`boolean` telling you if there is an update available
- `updateObject`:`undefined|UpdateObject`. When UpdateObject is provided, you can call its `updateSWObject()` method to update the app
- `offlineReady`:`boolean` telling you all offline assets have been loaded
- `registerError`:`any` - the error message when the registration of the service worker failed
- `registration`:`undefined|ServiceWorkerRegistration` - the service worker registration object - when succesfull
- `beforeInstallPrompt` - `undefined|BeforeInstallPromptEvent` - which you can use to fire the `.prompt()` method to invoke the install prompt. N.B. this needs to happen right after an userevent (like button press)!

All these props are also available via the `pwaStatusStream` readable store.

Vite has its own svelte version for integration - https://vite-plugin-pwa.netlify.app/frameworks/svelte.html

## How to contribute?
Would you like to contribute to this project? Great!

What is there to do
- EASY - fix typos (also great for your Github online profile - there are many), add examples for components
- MEDIUM - fix some minor bugs ( e.g. SvelteSpring), improve layout of pages (e.g. SvelteTransition) 
- HARD - look at the open issues below

When you do a PR, make sure you explain what you did and why!

## PLEASE NOTE - MIGRATION PLANNED
I am planning to migrate this project to SvelteKit SPA mode (so no SSR). This I will complete once the big new release of sveltekit is completed: https://github.com/sveltejs/kit/discussions/5748

What does this mean for you if you have existing projects? It depends, as it is perfectly cool to stay on Svelte/Vite/Routify.  And if you are new to this repo - not to worry, you can still do cool coding with this!

So why change? Well, reduce the number of dependencies (Routify) and taking the developer experience closer to all the developments by the Svelte team - as they do see Sveltekit as the way to go. And first tests also show that the build bundling is more spread out to the loading is even a bit faster!

If you want to move your existing project (Vite/Svelte/Routify) to Sveltekit, I recommend scaffolding a clean sveltekit project (this or future version). The steps I had to go through so far:

Configure as SPA only:
  * Static adapter in svelte.config.js, with configuration of a fallback
  * hooks.js - ` return resolve(event, { ssr: false });` as handle function

Path aliases:
* vite.config.js - adding the path aliases (does not work as per tutorials/docs in svelte.config.js)
* tsconfig.json - add path aliases

PWA (untested)
* add vite pwa plugin
* follow the sveltekit workaround on vite site
* fix error in pwa.js: https://github.com/antfu/vite-plugin-pwa/issues/293

Replace Routify with Sveltekit router - in your own components as well as the $ionic/svelte components
* $goto will become goto - second argument is different - check documentation on $app/navigation https://kit.svelte.dev/docs/modules#$app-navigation
* use beforeNavigate hook for ionViewWillLeave event in IonPage. 

Make the app more Ionic
* put stuff into index.html
* put App.svelte stuff into __layout.svelte (ion-app wrapper etc)

The Svelte-Vite-Routify repo will continue to exist as separate branch once the migration is completed. But I don't think I will upgrade things anymore.


## How I got started with this rebuild: the basic steps performed
In pseudo code - this is what I did

Scaffold the Svelte app
- npm create vite@latest (config - Svelte, TS)

Svelte router steps
- install roxy router run-all
- package.json scripts changed to router build scripts
- changes pages folder to routes folder (routify config in package.json) - I like it a bit more

Configuring Svelte workspace to my liking
- remove public folder
- created static folder as static dir
- config vite -> to include static dir for assets etc
- add aliases using $ sign (in vite.config as well as tsconfig) - https://dev.to/danawoodman/how-to-add-module-import-aliases-in-sveltekit-2ck

PWA steps:
Follow the documentation on vite-plugin-pwa.netlify.app!! VERRRRRY easy
Changed some stuff in index.html, including adding base-href and some meta stuff

Ionic related steps
- npm i @ionic/core  sass
- create "ionic/svelte" library (via alias) - so the ionic-integration almost looks like for real
- added initialise function for Ionic UI stuff - (initialiseIonicSvelte)
- main.ts -> refer to initialiseIonicSvelte
- App.svelte -> include ion-app 

Then......
As of this step, the hard work started. Getting all UI components working, aligning with the Ionic documentation... 

Much has been realised and the issue list shows the hard stuff getting the integration almost completely aligned with the docs (or some stuff working at all).

But, the highlights for now:
- This project has all Ionic related stuff in a lib structure - so easy to drop in your own project
- Ionic lifecycle hooks implemented - see Page.svelte and Note.svelte (and IonPage.svelte) - also in onMount/onDestroy style
- modal and popover controllers work via inline and programmatically - was quite a search to get this done!!
- other controllers work perfectly - menu has a minor workaround
- shows source code for all documented APIs - Vue, Angular, Javascript and Stencil. Next to Svelte!!

## REPLS
REPLS available - https://github.com/Tommertom/svelte-ionic-app/blob/main/REPLS.md
These are Ionic 4 components only.

## Todo
- Get many to test and use Svelte, Ionic and Vite :)
- Ionic 6.2 minor changes
- migration to SvelteKit (SPA mode) once the major update is there from their end
- put 	`const createHTMLCompFromSvelte = ( from NavHome` into $ionic/svelte

## Issues - help needed/workaround provided
- IonTabs and IonPage have their own implementation only accessible as Svelte component, not web component. Need to figure out how to wrap them into a webcomponent, without loosing animation stuff. Webcomponent of ion-page gives known issue on transition (https://github.com/Auroratide/svelte-custom-element-transitions). So no webcomponent of ion-page available for now. IonPage does seem to work nicely though. Later I might try wrapping the ion-nav in other element and see if that makes the animation go?

- Ion Back Button - does not show nor work - rebuild using https://github.com/ionic-team/ionic-framework/blob/main/core/src/components/back-button/back-button.tsx - you can also make your own and do a history.back?

- IonTabs needs to manually call the select method of ion-tabs to ensure the selectedTab prop is really acted upon. Issue known: https://github.com/ionic-team/ionic-framework/issues/20060. Gives a brief undesireable view on the wrong tab. Might need to look into the angular/react/vue way as these packages don't have this issue. Probably tabs is wired up in the router. 

- Gestures: Need a timeout to get proper style value even though I am using onMount?? 

- Ion Footer in Modal looks not ok - need to test in inline modal as well. 

- bind:value does not seem to work on input and other form elements, so a click handler is needed - which is cumbersome - https://github.com/sveltejs/svelte/issues/892 - so probably not solvable without support by Ionic or Svelte - or we need to create wrappers for all elements - which is quite some work and you will be required to manually import all elements you use per page (like with Vue and React) - which seems a drag to me?

Please note - if you use a library such as https://svelte-forms-lib-sapper-docs.vercel.app/introduction together with Yup schemas https://github.com/jquense/yup, the bind:value-issue actually becomes less relevant as you will have the library handle the events and you will use the observables to manage validation and final values to use for further processing. See https://blog.logrocket.com/form-validation-in-svelte/ for nice examples.

- Some styles are unused - related to md and ios options for webcomponents? Or need to be discarded. Probably issue with webcomponents and the nature of Ionic being sensitive to md or ios style (as part of its config)

- Add IonPage, IonTabs and IonBackButton are not part of the default export - these are svelte components, so index.ts cannot handle these (?) 

- Ion Icons implementation will not support md and ios specific icons etc (yet) - name prop does not function - also happening in Vue/React.Similar icon issues arise with other component that can digest custom icons (to check) - solution could be to make a svelte IonIcon component, but that will likely import all icons in a non-tree-shakable way?

- Adding custom class to Modal/Popover does not work (using controller) - using inline Modal/Popover is probably better anyway

- In some cases IonPage clips the content enclosed - then you need to remove main tags in IonPage

- Routerlink, href and similar props on components like ion-item do not work properly, but I wonder if support is needed

- Menucontroller does not see the menu by default - you need to register the menu item manually - extra function added to help you with that (`registerMenu(menu-id:string)`) - `<ion-menu {side} content-id="main" menu-id="mainmenu">`see Menu.svelte with working example

- Nav component - works nicely, but implementation might be dirty (leaking DOM elements?). ion-nav-link not implemented.


## Things to do maybe one day...
- make it an npm package - already in a lib style - https://betterprogramming.pub/creating-a-package-for-svelte-f44fccbc886b, https://blog.logrocket.com/build-your-own-component-library-svelte/
- dark mode selector

## Things not being implemented
`ion-router-link`, `ion-router`,`ion-route`, `ion-route-redirect` and `ion-router-outlet` - these are imho obsolete because of usage of the router in this project. But tell me if I am wrong here!

`ion-nav-link` - not sure why not, but haven't used it yet in a project. Maybe my bad. What do you think?

## Acknowledgements
Logo by Brett Peary: https://brettpeary.com/

Ionic UI code: https://github.com/ionic-team/ionic-docs/tree/main/static/demos/api

README inspiration: https://github.com/gitpoint/git-point/blob/master/README.md

PWA logo: https://github.com/webmaxru/progressive-web-apps-logo

Borat logo: https://sapper.svelte.dev/

Roxi Routify router:  https://v3.ci.routify.dev/docs#

Raymondboswel's repo: https://github.com/raymondboswel/ionic-svelte-example

