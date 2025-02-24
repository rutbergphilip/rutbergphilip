```console
philiprutberg@MacBook-Pro ~ $
philiprutberg@MacBook-Pro ~ $ ls -l
-rw-r--r--  1 philiprutberg  staff   512 Feb 23 2025 about-me.txt
drwxr-xr-x  4 philiprutberg  staff   160 Jun 06 2024 Portfolio
drwxr-xr-x  7 philiprutberg  staff   224 Feb 10 2025 Projects
drwxr-xr-x  7 philiprutberg  staff    96 Dec 15 2024 Experience
drwxr-xr-x  5 philiprutberg  staff    64 Dec 12 2024 Education

philiprutberg@MacBook-Pro ~ $ cat about-me.txt
Hello, I'm Philip Rutberg.

A Software Engineer who enjoys working across the entire stack,
solving complex challenges and building scalable systems with modern technologies.

My main interest lies in Identity and Access Management (IAM), where I design secure authentication,
authorization, and access control solutions while continually expanding my expertise.

Learn more at: https://philiprutberg.com/

philiprutberg@MacBook-Pro ~ $ cd Projects
philiprutberg@MacBook-Pro ~/Projects$ ls
ProjectFoxxy    RedisRacer    WoWCollector    BloodlustBoosting    blocket.js

philiprutberg@MacBook-Pro ~/Projects$ echo "Let's take a look at some notable projects of mine :)"
Let's take a look at some notable projects of mine :)

philiprutberg@MacBook-Pro ~/Projects$ tree -L 2
zsh: command not found: tree

philiprutberg@MacBook-Pro ~/Projects$ brew install tree
############ 12.0%
==> Fetching tree
==> Downloading https://ghcr.io/v2/homebrew/core/tree/blobs/sha256:ccfac896234e1c63841b421873387c407f375af7e6db54abea549d24e3c69589
#################################################################################################################################################################################### 100.0%

philiprutberg@MacBook-Pro ~/Projects$ tree -L 2
.
├── ProjectFoxxy
│   ├── server
│   ├── src
│   ├── README.md
│   ├── nuxt.config.ts
│   ├── package.json
│   └── tsconfig.json
├── RedisRacer
│   ├── src
│   ├── LICENSE
│   ├── README.md
│   ├── docker-compose.yml
│   └── package.json
├── WoWCollector
│   ├── .github/workflows
│   ├── back-end
│   ├── development
│   ├── docs
│   ├── front-end
│   ├── integration
│   ├── scripts
│   ├── README.md
│   └── version.txt
├── BloodlustBoosting
│   ├── events
│   ├── interactions
│   ├── src
│   ├── utils
│   ├── README.md
│   ├── index.js
│   ├── package.json
└── blocket.js
    ├── .github/workflows
    ├── lib
    ├── LICENSE
    ├── README.md
    └── package.json

philiprutberg@MacBook-Pro ~/Projects$ cat ProjectFoxxy/README.md
# Project Foxxy

A custom built scheduling solution with an admin dashboard for raid management and discord bot for user signups.
See: https://projectfoxxy.eu/

philiprutberg@MacBook-Pro ~/Projects$ cat RedisRacer/README.md
# RedisRacer

A benchmarking tool to test the performance between the two most popular Node.js Redis libraries.
Learn more: https://github.com/rutbergphilip/RedisRacer

philiprutberg@MacBook-Pro ~/Projects$ cat WoWCollector/README.md
# WoW Collector

A tracking tool for World of Warcraft collectables.
Learn more: https://philiprutberg.com/projects

philiprutberg@MacBook-Pro ~/Projects$ cat BloodlustBoosting/README.md
# Bloodlust Boosting

Scandinavia's former largest World of Warcraft boosting community.
Discontinued as of 2022.
Learn more: https://philiprutberg.com/projects

philiprutberg@MacBook-Pro ~/Projects$ cat blocket.js/README.md
# blocket.js

A NodeJS API wrapper for Blocket.se's unofficial API,
fetching and processing data from Sweden's leading marketplace.
Learn more: https://github.com/rutbergphilip/blocket.js

philiprutberg@MacBook-Pro ~/Projects/blocket.js$ cd ... && ls
Portfolio    Project    Experience    Education

philiprutberg@MacBook-Pro ~ $ nvim connect.md
# Let's connect! 🚀

Whether you want to collaborate, share knowledge, or just have a chat, I'm always happy to connect!

Find me here:
🔗 [LinkedIn](https://linkedin.com/in/philiprutberg/)
📸 [Instagram](https://instagram.com/rutbergphilip/)
💡 [LeetCode](https://leetcode.com/rutbergphilip/)
.
.
.
.
.
.
:wq

philiprutberg@MacBook-Pro ~ $ echo "Thanks for stopping by!"
Thanks for stopping by!

philiprutberg@MacBook-Pro ~ $ exit
logout
```
