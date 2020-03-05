# Yarn
My works related to Yarn JavaScript Package Manager.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [GitHub notes.](#github)
4. [GitHub repository calculation.](#calculation)

<a name="introduction"></a>
## 1. Introduction.
<img src="yarn.jpg" height="150"> 
Yarn is a JavaScript Package Manager, a direct competitor of npm, and it’s one of the Facebook Open Source projects. It is compatible with npm packages, so it has the great advantage of being a drop-in replacement for npm.
<br /><br />
Yarn is a new package manager that replaces the existing workflow for the npm client or other package managers while remaining compatible with the npm registry. It has the same feature set as existing workflows while operating faster, more securely, and more reliably.
<br /><br />
The primary function of any package manager is to install some package — a piece of code that serves a particular purpose — from a global registry into an engineer's local environment. Each package may or may not depend on other packages. A typical project could have tens, hundreds, or even thousands of packages within its tree of dependencies.
<br /><br />
These dependencies are versioned and installed based on semantic versioning (semver). Semver defines a versioning scheme that reflects the types of changes in each new version, whether a change breaks an API, adds a new feature, or fixes a bug. However, semver relies on package developers not making mistakes — breaking changes or new bugs may find their way into installed dependencies if the dependencies are not locked down.

<a name="references"></a>
## 2. Official references websites. <br />
Yarn official website : https://yarnpkg.com <br />
Yarn installation page : https://classic.yarnpkg.com/en/docs/install <br />
Yarn official documentation : https://classic.yarnpkg.com/en/docs <br />
Yarn by Facebook Engineering : https://engineering.fb.com/web/yarn-a-new-package-manager-for-javascript/ <br />

**_Yarn documentation by classic.yarnpkg.com_** <br />
yarn upgrade by classic.yarnpkg.com : https://classic.yarnpkg.com/en/docs/cli/upgrade/ <br />
yarn add by classic.yarnpkg.com :  https://classic.yarnpkg.com/en/docs/cli/add <br />
yarn outdated by classic.yarnpkg.com : https://classic.yarnpkg.com/en/docs/cli/outdated <br />
yarn init by classic.yarnpkg.com : https://classic.yarnpkg.com/en/docs/cli/init <br />
yarn global by classic.yarnpkg.com : https://classic.yarnpkg.com/en/docs/cli/global <br />
yarn list by classic.yarnpkg.com : https://classic.yarnpkg.com/en/docs/cli/list <br />
yarn check by classic.yarnpkg.com : https://classic.yarnpkg.com/en/docs/cli/check <br />
yarn import by classic.yarnpkg.com : https://classic.yarnpkg.com/en/docs/cli/import <br />
yarn run by classic.yarnpkg.com : https://classic.yarnpkg.com/en/docs/cli/run <br />
yarn licenses by classic.yarnpkg.com : https://classic.yarnpkg.com/en/docs/cli/licenses <br />
yarn pack by classic.yarnpkg.com : https://classic.yarnpkg.com/en/docs/package-json <br />
yarn cache by classic.yarnpkg.com : https://classic.yarnpkg.com/en/docs/cli/cache <br />

**_Yarn related articles_** <br />
Yarn - There appears to be trouble with your network connection. Retrying by Stack Overflow : https://stackoverflow.com/questions/51508364/yarn-there-appears-to-be-trouble-with-your-network-connection-retrying <br />
How Do I Uninstall Yarn by Stack Overflow : https://stackoverflow.com/questions/42334978/how-do-i-uninstall-yarn

<a name="github"></a>
## 3. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/Yarn.git
$ cd Yarn/
$ git remote -v
$ git status
```

<a name="calculation"></a>
## 4. GitHub repository calculation.
```
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
JavaScript                    1617          11575          28398          86953
Markdown                       124           4794              0          10167
JSON                           113              0              0           5397
TypeScript                       9            190            333            780
Bourne Shell                    13             26              0            169
DOS Batch                       13              0              0             91
YAML                             7              3              0             68
make                             1             14              4             32
-------------------------------------------------------------------------------
SUM:                          1897          16602          28735         103657
-------------------------------------------------------------------------------
```
Refer to : https://github.com/syakirharis25/cloc
