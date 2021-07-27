# Vuetify with WC as build

I am trying to build my project as web component but I can not do it with vuetify.
When I include vuetify I am not getting any of the style. 
I already tried [this link](https://stackoverflow.com/questions/55467240/how-do-you-include-vuetify-inside-web-component)
steps to reproduce install and run wc and I added the ```<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/vuetify/dist/vuetify.min.css">``` inside


## Project setup
```
npm install
```
### Compiles and show the web component with inline configuration
```
npm run wcin
```

### Compiles and show web component
```
npm run wc
```

Also I tried to add import 'vuetify/dist/vuetify.min.css' into plugins/vuetify.js


