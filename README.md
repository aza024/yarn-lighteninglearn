# Yarn

 *"Yarn is a package manager for your code. It allows you to use and share code with other developers from around the world. 
Yarn does this quickly, securely, and reliably so you don’t ever have to worry."*

In October 2016, Facebook and Google decided to team up and make a better Javascript package manager called Yarn. 
Yarn is an alterative to npm and is faster, more stable, and more secure and fixes npm glitches.
Yarn doesn't intend to replace npm, but does intend to improve it's current functionallity.

## Offline Development and Version Control
Yarn allows for use of  other developers solutions, and allows users to edit in offline mode - so you don't have to install software in a specific
order, users can install packages in whichever order they'd like. 

Yarn allows develop offline because it caches everything to avoid any possible problems related to different versions of node.js system modules.

## Speed
The speed of installing modules is faster which is significant for large projects with more dependencies because users don't have to configure yarn on their end. After every install, upgrade or removal, yarn updates a yarn.lock file which keeps track of the exact package version installed in node_modules directory.

It's 2-7X faster than npm. Yarn provides cleaner output than it's more verbose predecessor npm providing less information sprinkled with approriate emojis. It recursively lists all installed packages when running ```npm install <package>```. Instead of pulling a new copy from the NPM registry, Yarn would first check to see if you had already downloaded it in the past. If you had, it would skip the download process and instead just copy the package from the local cache into your project folder. If other environments pull from repo - they'll get the exact same verisons which helps with application stablity.

## Installation 

If node is installed: ```brew install yarn```

Get package installed: ```yarn init```

Install Yarn: ```yarn install```

To remove unnecessary pacakges, run ```yarn clean```

# Caveats: 

* Yarn has been developed just recently.
* Yarn won’t work on node.js version 5.10.1 - apps must use version 6.3.1
* Problems with installing native modules

# Comments: 

We would reccommend using Yarn as an alternative to npm because it would save time, allow for offline development, and be
more stable. Using Yarn would not increase our skillset, however, it would improve our development experience by helping
avoid unnecessary errors related to version control.

## Resources: 
* https://yarnpkg.com/en/
* https://yarnpkg.com/blog/2016/11/24/offline-mirror/
* https://www.youtube.com/watch?v=OCW3Jz6F8Ek
* https://scotch.io/tutorials/yarn-package-manager-an-improvement-over-npm
* https://www.atatus.com/blog/everything-you-wanted-to-know-about-yarn-package-manager/
* http://andrewconnell.com/blog/npm-yarn-pnpm-which-package-manager-should-you-use-for-sharepoint-framework-projects

### Authors: 

Andrea Piazza and Yi Liu
