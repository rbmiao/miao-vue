# miao-vue project:

See my gmail: Vue tutorial on Mac - for details

## Brief steps

* clone this repository to local:
```
git clone ...
```
* Delete .git directory, since this folder will update to Heroku. Point to remote repo to Heroku
```
rm -rf .git
git init
heroku git:remote -a miao-vue
git commit ..
git push ..
```

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Verify Heroku build:
https://miao-vue.herokuapp.com/
