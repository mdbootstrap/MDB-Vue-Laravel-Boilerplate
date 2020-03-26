# MDB Vue + Laravel

<div align="center">
<br>
<img width="300" src="./public/images/logo.png" alt="mdbvue-nuxt">
<br>
<br>
</div>

- Laravel/Framework **7.0.0**
- MDB Vue **6.5.1**

## Build Setup

```bash
# install dependencies
$ composer install
$ npm install

# serve with hot reload at localhost:8000
$ npm run dev
$ php artisan serve

```

## MDB Pro 

Are you a MDB **Pro** user with Gitlab access?

You can easily upgrade **mdbvue** dependency:

1. Generate a Gitlab access token. Not sure how to do that? Learn more [here](https://mdbootstrap.com/docs/vue/getting-started/quick-start/#token)

2. Open **package.json** file

3. Replace the following line: 

```json
"mdbvue": "^version"
```
 with 

 ```json
 "mdbvue": "git+https://oauth2:YOUR_TOKEN@git.mdbootstrap.com/mdb/vue/vu-pro.git"
 ```
4.
```bash
 $ npm install

```

## Learn more about MDB Vue:

To learn more about MDB Vue components, visit [MDBootstrap Vue docs](https://mdbootstrap.com/docs/vue/).

