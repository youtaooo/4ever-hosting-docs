# Connect to Github

This document will introduce how to log in to 4ever-hosting through a Github account. Before starting, please make sure that you have a Github account and have logged in.

## Step1: Login via github

In many places on 4everland, you can find the login entrance. A 4ever-hosting account will be easily created when you click on login, then authorize.

<img style="margin-top:15px;box-shadow:0 30px 60px rgba(0,0,0,0.12);" src="../assets/screenshots/github_login@2x.png"/>

## Step2: New Project

Click on [New Project](https://hosting.4everland.org/#/new) to start a new deployment, for the first of time you may need to buy or claim resources(Storage and Network).
<img style="margin-top:15px;box-shadow:0 30px 60px rgba(0,0,0,0.12);" src="../assets/screenshots/new_project@2x.png"/>

## Step3: Import git repos

Click on "Select Git" to import your git repositories.

<img style="margin-top:15px;box-shadow:0 30px 60px rgba(0,0,0,0.12);" src="../assets/screenshots/import_git.gif"/>

Since then, you have completed 4ever-hosting account creation and connected to your github account. Congratulations, we are ready to the [next step](./build.md).
14:30:13.911 start clone: https://github.com/youtaooo/youtao888888.git

14:30:15.178 clone success with 1.266795456s

14:30:18.487 build starting...

14:30:55.203 yarn install v1.22.5
14:30:55.318 [1/4] Resolving packages...
14:30:55.512 [2/4] Fetching packages...
14:31:02.706 info fsevents@2.3.2: The platform "linux" is incompatible with this module.
14:31:02.706 info "fsevents@2.3.2" is an optional dependency and failed compatibility check. Excluding it from installation.
14:31:02.710 [3/4] Linking dependencies...
14:31:04.473 [4/4] Building fresh packages...
14:31:04.486 Done in 9.29s.
14:31:05.373 
14:31:05.373 > nextjs@0.1.0 build /ws/6142e4749431400001eb7774/4471f54b0b7347789a78f3ea7846113e
14:31:05.373 > next build && next export
14:31:05.373 
14:31:06.147 info  - Using webpack 4. Reason: future.webpack5 option not enabled https://nextjs.org/docs/messages/webpack5
14:31:06.503 info  - Checking validity of types...
14:31:06.842 Attention: Next.js now collects completely anonymous telemetry regarding usage.
14:31:06.842 This information is used to shape Next.js' roadmap and prioritize features.
14:31:06.842 You can learn more, including how to opt-out if you'd not like to participate in this anonymous program, by visiting the following URL:
14:31:06.842 https://nextjs.org/telemetry
14:31:06.842 
14:31:07.534 info  - Creating an optimized production build...
14:31:18.740 info  - Compiled successfully
14:31:18.740 info  - Collecting page data...
14:31:19.239 info  - Generating static pages (0/3)
14:31:19.831 info  - Generating static pages (3/3)
14:31:19.845 info  - Finalizing page optimization...
14:31:19.936 
14:31:20.17 Page                                                           Size     First Load JS
14:31:20.17 ┌ ○ /                                                          3.29 kB        66.8 kB
14:31:20.18 ├   └ css/9c4381274c2a4fd9d205.css                             669 B
14:31:20.18 ├   /_app                                                      0 B            63.5 kB
14:31:20.18 ├ ○ /404                                                       3.46 kB          67 kB
14:31:20.18 └ λ /api/hello                                                 0 B            63.5 kB
14:31:20.18 + First Load JS shared by all                                  63.5 kB
14:31:20.18   ├ chunks/f6078781a05fe1bcb0902d23dbbb2662c8d200b3.d7f870.js  13.4 kB
14:31:20.18   ├ chunks/framework.4b1bec.js                                 41.8 kB
14:31:20.18   ├ chunks/main.158966.js                                      7.12 kB
14:31:20.18   ├ chunks/pages/_app.9fce70.js                                529 B
14:31:20.18   ├ chunks/webpack.50bee0.js                                   751 B
14:31:20.18   └ css/381f5b9c92d1673af027.css                               203 B
14:31:20.18 
14:31:20.18 λ  (Server)  server-side renders at runtime (uses getInitialProps or getServerSideProps)
14:31:20.18 ○  (Static)  automatically rendered as static HTML (uses no initial props)
14:31:20.18 ●  (SSG)     automatically generated as static HTML + JSON (uses getStaticProps)
14:31:20.18    (ISR)     incremental static regeneration (uses revalidate in getStaticProps)
14:31:20.18 
14:31:20.583 info  - Using webpack 4. Reason: future.webpack5 option not enabled https://nextjs.org/docs/messages/webpack5
14:31:21.139 info  - using build directory: /ws/6142e4749431400001eb7774/4471f54b0b7347789a78f3ea7846113e/.next
14:31:21.144 info  - Copying "static build" directory
14:31:21.151 info  - No "exportPathMap" found in "next.config.js". Generating map from "./pages"
14:31:21.152 info  - Launching 7 workers
14:31:21.153 warn  - Statically exporting a Next.js application via `next export` disables API routes.
14:31:21.153 This command is meant for static-only hosts, and is not necessary to make your application static.
14:31:21.153 Pages in your application without server-side data dependencies will be automatically statically exported by `next build`, including pages powered by `getStaticProps`.
14:31:21.153 Learn more: https://nextjs.org/docs/messages/api-routes-static-export
14:31:21.153 info  - Exporting (0/2)
14:31:21.153 info  - Copying "public" directory
14:31:21.677 info  - Exporting (2/2)
14:31:21.683 Export successful. Files written to /ws/6142e4749431400001eb7774/4471f54b0b7347789a78f3ea7846113e/out
14:31:24.119 deploy site success: QmV3tojd5qNmTtov6cJRzyZVKh5AQqyDY99g8JP7qBVCNJ
