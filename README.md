# vueplayground

## Got here by

```
npm install -g @vue/cli
npm install -g serve
vue create vueplayground
```

## Test cache busting

Open tab localhost:5000

Edit `msg` in `App.vue`

Close all localhost:5000 tabs

run

```
npm run build
serve dist
```

first load will update the service worker - and give an option to reload or prompt the user to reload
second load will update the page

## Remove cache busting

Delete `vue.config.js`