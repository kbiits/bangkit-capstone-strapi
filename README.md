# Bangkit Capstone Backend - Team C23-PS072

## Steps to Install

### Requirements
- node.js 18.x
- postgresql 13.x
- npm / yarn

### Install
- Clone this repo
```bash
git clone https://github.com/kbiits/bangkit-capstone-strapi.git
```
- Modify .env
```bash
cp .env.example .env
```
Adjust the .env file contents
Ex:
```env
HOST=0.0.0.0
PORT=1337
APP_KEYS="base64_strings_1,base64_strings_2,base64_strings_3"
API_TOKEN_SALT=BASE64_STRONG_API_TOKEN_SALT_STRING
ADMIN_JWT_SECRET=BASE64_MYADMINJWT_SECRET
JWT_SECRET=BASE64_MYJWT_SECRET
TRANSFER_TOKEN_SALT=BASE64_STRONG_TRANSFER_TOKEN_SALT_STRING
DATABASE_CLIENT=postgres
DATABASE_HOST=127.0.0.1
DATABASE_PORT=5432
DATABASE_NAME=mydb
DATABASE_USERNAME=root
DATABASE_PASSWORD=root
DATABASE_SSL=false
```
- Install dependencies
```
npm install
```
- Start the app
```bash
npm run start
```
or if you want to run in development mode
```bash
npm run develop
```

## Architecture

### Backend Infrastructure
![Backend Infrastructure design](https://raw.githubusercontent.com/kbiits/bangkit-capstone-strapi/master/Backend.jpg "Backend Infrastructure design")


### Database Design
![Database design](https://raw.githubusercontent.com/kbiits/bangkit-capstone-strapi/master/bangkit_capstone%20-%20public.png "Database design")
