

# SUJI [![Build Status](https://travis-ci.org/naver-d2-suji/suji.svg)](https://travis-ci.org/naver-d2-suji/suji)
> Web based POS system
![SUJI](https://cloud.githubusercontent.com/assets/7614353/12139794/1329ce44-b4a6-11e5-90a2-dd51d039e01d.png)
- [** Video **](https://youtu.be/0mEFdHfyu00)
&nbsp;

## Development Stack
- Language : Javascript
- Framework : [Node.js](https://nodejs.org/), [Express](http://expressjs.com/)
- Use Modules : async, should, supertest, mocha, crypto, jQuery
- Server : [DigitalOcean](https://www.digitalocean.com/), [nginX](http://nginx.org/)
- Database : MariaDB
- Build & Test Tool : [Grunt](http://gruntjs.com/), [Travis CI](https://travis-ci.com/)


&nbsp;
## Getting Started
### Prerequisites
- `Node.js` and `npm` should be installed
- `Grunt` should be installed
```shell
npm install --global grunt
```
- MariaDB should be installed(v10 or more recent). If not pre-installed, check the following instrution here : [Install MariaDB](https://www.vultr.com/docs/install-mariadb-on-ubuntu-14-04)

### Quick Start
- [Download the latest version](https://github.com/naver-d2-suji/suji/archive/develop.zip)
- Install with npm :
```shell
 npm install
```
- Run the program :
```shell
 grunt serve
```

&nbsp;
## REST API
> REST API Definition

| Feature |	Method	| Request URL | Todo Status |
| :------------ |	:-------:	| :-----------------| :--------: |
| Register |	POST	| /api/v1.1/user/register | complete |
| Login |	GET	| /api/v1.1/user/login | complete |
| Category List |	GET	| /api/v1.1/category | complete |
| Category Add |	POST	| /api/v1.1/category/insert | complete |
| Menu list by Category |	GET	| /api/v1.1/menu/:category | complete |
| Menu List |	GET	| /api/v1.1/menu | complete |
| Add Menu|	POST	| /api/v1.1/menu/insert | complete |
| Delete Menu |	POST	| /api/v1.1/menu/delete | complete |
| Purchase List |	GET	| /api/v1.1/purchase | complete |
| Add Purchase |	POST	| /api/v1.1/purchase/add | complete |
| Delete Purchase |	POST	| /api/v1.1/purchase/delete | complete |