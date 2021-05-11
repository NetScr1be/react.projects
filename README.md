# react.projects
Projects from Tutorials

# react.projects
Projects from Tutorials

## Project 01  
1. Create React App  
   1.1 Source: https://reactjs.org/docs/create-a-new-react-app.html#create-react-app  
2. Requires:  
   2.1 **Node \>= 10.16**  
    2.1.a  `patrick@kali:~/Projects/React$ node --version`  
    2.1.b  *v14.7.0*  
   2.2 **npm >= 5.6**  
    2.2.a `patrick@kali:~/Projects/React$ npm --version`  
    2.2.b _6.14.7_  
3. Create app environment  
 3.1 `patrick@kali:~/Projects/React$ npx create-react-app tictactoe`

> npx: installed 67 in 4.76s  

> Creating a new React app in /home/patrick/Projects/React/tictactoe.  

> Installing packages. This might take a couple of minutes.  
Installing react, react-dom, and react-scripts with cra-template...  

> yarn add v1.22.10  
[1/4] Resolving packages...  
[2/4] Fetching packages...  
info fsevents@1.2.13: The platform "linux" is incompatible with this module.  
info "fsevents@1.2.13" is an optional dependency and failed compatibility check. Excluding it from installation.  
info fsevents@2.3.2: The platform "linux" is incompatible with this module.  
info "fsevents@2.3.2" is an optional dependency and failed compatibility check. Excluding it from installation.  
[3/4] Linking dependencies...  
warning "react-scripts > @typescript-eslint/eslint-plugin > tsutils@3.20.0" has unmet peer dependency "typescript@>=2.8.0 || >= 3.2.0-dev || >= 3.3.0-dev || >= 3.4.0-dev || >= 3.5.0-dev || >= 3.6.0-dev || >= 3.6.0-beta || >= 3.7.0-dev || >= 3.7.0-beta".  
[4/4] Building fresh packages...  
success Saved lockfile.  
success Saved 7 new dependencies.  
info Direct dependencies  
├─ cra-template@1.1.2  
├─ react-dom@17.0.2  
├─ react-scripts@4.0.3  
└─ react@17.0.2  
info All dependencies  
├─ cra-template@1.1.2  
├─ immer@8.0.1  
├─ react-dev-utils@11.0.4  
├─ react-dom@17.0.2  
├─ react-scripts@4.0.3  
├─ react@17.0.2  
└─ scheduler@0.20.2  
Done in 44.49s.  

> Initialized a git repository.  

> Installing template dependencies using yarnpkg...  
yarn add v1.22.10  
[1/4] Resolving packages...  
[2/4] Fetching packages...  
info fsevents@2.3.2: The platform "linux" is incompatible with this module.  
info "fsevents@2.3.2" is an optional dependency and failed compatibility check. Excluding it from installation.  
info fsevents@1.2.13: The platform "linux" is incompatible with this module.  
info "fsevents@1.2.13" is an optional dependency and failed compatibility check. Excluding it from installation.  
[3/4] Linking dependencies...  
warning "react-scripts > @typescript-eslint/eslint-plugin > tsutils@3.20.0" has unmet peer dependency "typescript@>=2.8.0 || >= 3.2.0-dev || >= 3.3.0-dev || >= 3.4.0-dev || >= 3.5.0-dev || >= 3.6.0-dev || >= 3.6.0-beta || >= 3.7.0-dev || >= 3.7.0-beta".  
warning " > @testing-library/user-event@12.8.3" has unmet peer dependency "@testing-library/dom@>=7.21.4".  
[4/4] Building fresh packages...  
success Saved lockfile.  
success Saved 17 new dependencies.  
info Direct dependencies  
├─ @testing-library/jest-dom@5.11.10  
├─ @testing-library/react@11.2.6  
├─ @testing-library/user-event@12.8.3  
├─ react-dom@17.0.2  
├─ react@17.0.2  
└─ web-vitals@1.1.1  
info All dependencies  
├─ @testing-library/dom@7.30.3  
├─ @testing-library/jest-dom@5.11.10  
├─ @testing-library/react@11.2.6  
├─ @testing-library/user-event@12.8.3  
├─ @types/aria-query@4.2.1  
├─ @types/jest@26.0.22  
├─ @types/testing-library__jest-dom@5.9.5  
├─ css.escape@1.5.1  
├─ css@3.0.0  
├─ dom-accessibility-api@0.5.4  
├─ lz-string@1.4.4  
├─ min-indent@1.0.1  
├─ react-dom@17.0.2  
├─ react@17.0.2  
├─ redent@3.0.0  
├─ strip-indent@3.0.0  
└─ web-vitals@1.1.1  
Done in 9.61s.  
Removing template package using yarnpkg...  

> yarn remove v1.22.10  
[1/2] Removing module cra-template...  
[2/2] Regenerating lockfile and installing missing dependencies...  
info fsevents@2.3.2: The platform "linux" is incompatible with this module.  
info "fsevents@2.3.2" is an optional dependency and failed compatibility check. Excluding it from installation.  
info fsevents@1.2.13: The platform "linux" is incompatible with this module.  
info "fsevents@1.2.13" is an optional dependency and failed compatibility check. Excluding it from installation.  
warning " > @testing-library/user-event@12.8.3" has unmet peer dependency "@testing-library/dom@>=7.21.4".  
warning "react-scripts > @typescript-eslint/eslint-plugin > tsutils@3.20.0" has unmet peer dependency "typescript@>=2.8.0 || >= 3.2.0-dev || >= 3.3.0-dev || >= 3.4.0-dev || >= 3.5.0-dev || >= 3.6.0-dev || >= 3.6.0-beta || >= 3.7.0-dev || >= 3.7.0-beta".  
success Uninstalled packages.  
Done in 7.28s.  

> Created git commit.  

> Success! Created tictactoe at /home/patrick/Projects/React/tictactoe  
Inside that directory, you can run several commands:  

>   yarn start  
    Starts the development server.  

>   yarn build  
    Bundles the app into static files for production.  

>   yarn test  
    Starts the test runner.  

>   yarn eject  
    Removes this tool and copies build dependencies, configuration files  
    and scripts into the app directory. If you do this, you can’t go back!  

> We suggest that you begin by typing:  

>   cd tictactoe  
>   yarn start  

> Happy hacking!  

`patrick@kali:~/Projects/React$ cd tictactoe/`

`patrick@kali:~/Projects/React/tictactoe$ ls -al`

>total 564  
drwxr-xr-x    6 patrick patrick   4096 Apr 16 15:59 .  
drwxr-xr-x    3 patrick patrick   4096 Apr 16 11:07 ..  
drwxr-xr-x    8 patrick patrick   4096 Apr 16 15:59 .git  
-rw-r--r--    1 patrick patrick    310 Apr 16 15:59 .gitignore  
drwxr-xr-x 1047 patrick patrick  36864 Apr 16 15:59 node_modules  
-rw-r--r--    1 patrick patrick    813 Apr 16 15:59 package.json  
drwxr-xr-x    2 patrick patrick   4096 Apr 16 15:59 public  
-rw-r--r--    1 patrick patrick   3362 Apr 16 15:59 README.md  
drwxr-xr-x    2 patrick patrick   4096 Apr 16 15:59 src  
-rw-r--r--    1 patrick patrick 507434 Apr 16 15:59 yarn.lock  

** Delete all files in the src/ folder of the new project  **

_Note:_

_Don’t delete the entire src folder, just the original source files inside it. We’ll replace the default source files with examples for this project in the next step._


