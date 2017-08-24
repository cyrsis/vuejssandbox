# vuejssandbox

> A Vue.js Sandbox project

> Reference From https://github.com/ecofic/course-vue-getting-started/tree/master/src
## Install Chrome Dev tools

Install vue-devtools

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


## Create new project with vue-cli
``` bash
npm install -g vue-cli
```

## Data Class Props

You can only modify properties
You can’t add properties at runtime You can’t remove properties at runtime

Note:Use  Primitive values for Props: 
      123, “abc”, “2017-02-14”, [1, 2, 3]

Note: Do not use ES6 synntax

# 1- Binding for Display
Binding Text
1. Semantic syntax -> {{}} -> Doesnt work too well
2. Declarative syntax ->v-???? -> Much better to work with 
3.  One-time bindings -> use it as speed performance

# 2- Way binding for collect data in View
1. V-model sound good
   Text fields
      input, textarea
   CheckBox
   Radio Button
   Drop Down lists

## Something new in Vue
# Watches
  Ideal for async operation
  
# Filter (easier to read)
(Great way to handle BASIC text element)
 -- Using Methods
<div> {{ toUpperCase(removePeriods(result.ibu))}} </div>
 -- Using Filter
<div>{{ result.ibu |removePeriods|toUpperCase}} </div>

# Computed properties (For more compelex transformation)
# Compare those three things

|                                | Filter | Computed Properties | Methods  | Watchers |
|--------------------------------|--------|---------------------|----------|----------|
| React to data changes          | Yes    | Yes                 | No       | Yes      |
| Resuable across apps           | Yes    | No                  | No       | No       |
| Cached based on dependencies   | No     | Yes                 | No       | No       |
| Apprpriate for async operation | No     | No                  | Yes      | Yes      |
| Accepts Parameters             | Yes    | No                  | Yes      | No       |
| Fires After creation           | Yes    | Yes                 | Possible | No       |
## Working with Events
Bubble Up (Parent -> Grand Parent) Microsoft idea again , most common
Capture Down (Grand Parent -> Parent) -> Maybe with 3rd party component 


## To do Soon
Axios 
Components
Transitions
Routing
Statment management 
Server-Side Rendering
