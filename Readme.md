 
## Setup

In the project Root folder (frontend)
 


### yarn or yarn install

To install yarn

### yarn add lerna -D or yarn add lerna --dev

To install lerna as a dev dependdency


### yarn lerna bootstrap

to bootstrap the packages in the current repo,install all their dependencies and linking any cross-dependencies.
run this command 

## Running


goto packages/mobileuser folder

### yarn start

Run this command to start the metro bundler(in one terminal)

### yarn android

Run this command to install and launch your app on the device (in other terminal)



### yarn ios

Run this command to install and launch your app on the device

goto packages/webuser folder

### yarn start

Run this command to start web app in development mode

### Misc

 to install any library  to specific package (like ui-components,mobile-screens...etc)
 
 ### yarn lerna add libraryname --scope= packagename
 
 ex:
 
 yarn lerna add react-native-svg --scope = @unoroof/ui-components


