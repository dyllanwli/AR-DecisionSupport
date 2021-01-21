# quick start

installation
```
./scripts/init.sh
npm run dev
```

# Notes
+ custom element loaded via `compoment/somejs.js` as `CompomentName` and be added to someVue.vue as `compoment-name`

# changelog

+ remove header on App.vue, app.js
+ get menu done from store/modules/app-ui.js; src/main.js
    - menu config can be found on app-config.js and the menu is loaded via app-loader.js's fetchMainMenu from app-ui.js, where MainMenu is definied at @/common/main-menu