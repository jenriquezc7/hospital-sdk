initials commands
```shell
$ lerna init && npm i
```

create modules
```shell
$ lerna create <module>
```

login on npm
```shell
$ npm login --scope=hospital-sdk
```

script public package 
```json
{
 "scripts": {
   "publish": "lerna run tsc && lerna publish"
 }
}
```

publish package
```shell
$ npm run publish
```

Adds npm dependency to all or specific package within a project
```shell
$ lerna add <dependency>
```
Install all dependency from all packages within a project
```shell
$ lerna bootstrap
```