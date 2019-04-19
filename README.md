# Weather-api-
nodeJS and angular

# Steps to install nodejs in your machine

Your environment has been set up for using Node.js 10.15.1 (x64) and npm.

 

#Check if nodejs is already installed 
C:\Windows\System32>npn yarn -g

'npn' is not recognized as an internal or external command,

operable program or batch file.


# If the above message is displayed install it using the following command 

C:\Windows\System32>npm install -g yarn

C:\Users\jvelpula\AppData\Roaming\npm\yarnpkg -> C:\Users\jvelpula\AppData\Roaming\npm\node_modules\yarn\bin\yarn.js

C:\Users\jvelpula\AppData\Roaming\npm\yarn -> C:\Users\jvelpula\AppData\Roaming\npm\node_modules\yarn\bin\yarn.js

+ yarn@1.13.0

added 1 package in 1.853s

# Navigate to the path of the project

C:\Windows\System32>cd

C:\Windows\System32

 

C:\Windows\System32>cd\

 

C:\>cd\

 

C:\>cd C:\Angular\weather-api

 
# Give the following command in the project directory

C:\Angular\weather-api>yarn install

yarn install v1.13.0

[1/4] Resolving packages...

[2/4] Fetching packages...

info There appears to be trouble with your network connection. Retrying...

info There appears to be trouble with your network connection. Retrying...

info There appears to be trouble with your network connection. Retrying...

info There appears to be trouble with your network connection. Retrying...

info There appears to be trouble with your network connection. Retrying...

 

C:\Angular\weather-api>yarn install

yarn install v1.13.0

[1/4] Resolving packages...

[2/4] Fetching packages...

info There appears to be trouble with your network connection. Retrying...

info There appears to be trouble with your network connection. Retrying...

info There appears to be trouble with your network connection. Retrying...

info There appears to be trouble with your network connection. Retrying...

error An unexpected error occurred: "http://artifactory.factset.com/artifactory/api/npm/npm/babel-preset-es2015/-/babel-preset-es2015-6.24.1.tgz: getaddrinfo ENOTFOUND artifactory.factset.com artifactory.factset.com:80".

info If you think this is a bug, please open a bug report with the information provided in "C:\\Angular\\weather-api\\yarn-error.log".

info Visit https://yarnpkg.com/en/docs/cli/install for documentation about this command.


# If the above message comes it means that you have to delete the lockfile in the project directory

C:\Angular\weather-api>yarn install

yarn install v1.13.0

info No lockfile found.

[1/4] Resolving packages...

warning angular-ui-router@0.4.3: This npm package 'angular-ui-router' has been renamed to '@uirouter/angularjs'. Please update your package.json. See https://ui-router.github.io/blog/uirouter-scoped-packages/

warning babel-preset-es2015@6.24.1: 🙌  Thanks for using Babel: we recommend using babel-preset-env now: please read babeljs.io/env to update!

warning gulp > gulp-util@3.0.8: gulp-util is deprecated - replace it, following the guidelines at https://medium.com/gulpjs/gulp-util-ca3b1f9f9ac5

warning gulp > vinyl-fs > graceful-fs@3.0.11: please upgrade to graceful-fs 4 for compatibility with current and future versions of Node.js

warning gulp > vinyl-fs > glob-stream > minimatch@2.0.10: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue

warning gulp > vinyl-fs > glob-stream > glob > minimatch@2.0.10: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue

warning gulp > vinyl-fs > glob-watcher > gaze > globule > minimatch@0.2.14: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue

warning gulp > vinyl-fs > glob-watcher > gaze > globule > glob > minimatch@0.2.14: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue

warning gulp > vinyl-fs > glob-watcher > gaze > globule > glob > graceful-fs@1.2.3: please upgrade to graceful-fs 4 for compatibility with current and future versions of Node.js

warning gulp-angular-templatecache > gulp-util@3.0.7: gulp-util is deprecated - replace it, following the guidelines at https://medium.com/gulpjs/gulp-util-ca3b1f9f9ac5

warning gulp-angular-templatecache > gulp-concat > gulp-util@3.0.8: gulp-util is deprecated - replace it, following the guidelines at https://medium.com/gulpjs/gulp-util-ca3b1f9f9ac5

warning gulp-angular-templatecache > gulp-footer@1.0.5: Security vulnerability surrounding event-stream, do *NOT* use.

warning gulp-angular-templatecache > gulp-footer > gulp-util@3.0.8: gulp-util is deprecated - replace it, following the guidelines at https://medium.com/gulpjs/gulp-util-ca3b1f9f9ac5

warning gulp-angular-templatecache > gulp-header@1.8.2: Removed event-stream from gulp-header

warning gulp-angular-templatecache > gulp-header > gulp-util@3.0.8: gulp-util is deprecated - replace it, following the guidelines at https://medium.com/gulpjs/gulp-util-ca3b1f9f9ac5

warning gulp-notify > gulp-util@3.0.8: gulp-util is deprecated - replace it, following the guidelines at https://medium.com/gulpjs/gulp-util-ca3b1f9f9ac5

warning gulp-uglify > gulp-util@3.0.8: gulp-util is deprecated - replace it, following the guidelines at https://medium.com/gulpjs/gulp-util-ca3b1f9f9ac5

warning gulp-util@3.0.8: gulp-util is deprecated - replace it, following the guidelines at https://medium.com/gulpjs/gulp-util-ca3b1f9f9ac5

[2/4] Fetching packages...

info fsevents@1.2.7: The platform "win32" is incompatible with this module.

info "fsevents@1.2.7" is an optional dependency and failed compatibility check. Excluding it from installation.

[3/4] Linking dependencies...

[4/4] Building fresh packages...

success Saved lockfile.

Done in 62.89s.


# Give the following command, if the warning message comes, go to the next step

C:\Angular\weather-api>gulp

'gulp' is not recognized as an internal or external command,

operable program or batch file.

 
# Installit using the following command 

C:\Angular\weather-api>npm install -g gulp

C:\Users\jvelpula\AppData\Roaming\npm\gulp -> C:\Users\jvelpula\AppData\Roaming\npm\node_modules\gulp\bin\gulp.js

npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.7 (node_modules\gulp\node_modules\fsevents):

npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.7: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

 

+ gulp@4.0.0

added 316 packages from 216 contributors in 26.946s

 

C:\Angular\weather-api>gulp

[21:56:55] Using gulpfile C:\Angular\weather-api\gulpfile.js

[21:56:55] Starting 'html'...

[21:56:55] Starting 'views'...

[21:56:55] Finished 'html' after 84 ms

[21:56:55] Finished 'views' after 106 ms

[21:56:55] Starting 'browserify'...

[21:56:57] Finished 'browserify' after 2.05 s

[21:56:57] Starting 'default'...

[21:56:57] Finished 'default' after 137 ms

[Browsersync] Access URLs:

 --------------------------------------

       Local: http://localhost:4000

    External: http://172.20.77.177:4000

 --------------------------------------

          UI: http://localhost:4001

 UI External: http://localhost:4001

 --------------------------------------

[Browsersync] Serving files from: ./build

[Browsersync] Watching files...




