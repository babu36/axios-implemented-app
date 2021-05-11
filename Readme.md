## Setup

### step 1: install yarn  
'yarn or yarn install'

To install lerna as a dev dependdency

### step 2: install lerna as a dev dependdency
 

'yarn add lerna -D or yarn add lerna --dev'

### step 3:bootstrap the packages in the current repo,install all their dependencies and linking any cross-dependencies.
 
 ' yarn lerna bootstrap'

## Running


goto packages/mobileuser folder

###  To start the metro bundler(in one terminal)

'yarn start'

Run this command 

###  To install and launch your app on android device (in other terminal)
'yarn android'


### To install and launch your app on the ios device

'yarn ios' 

goto packages/webuser folder

### To start web app in development mode
'yarn start'

 

### Misc

 To install any library  to specific package (like ui-components,mobile-screens...etc)
 
 yarn lerna add libraryname --scope= packagename
 
 ex:
 
 yarn lerna add react-native-svg --scope = @unoroof/ui-components


