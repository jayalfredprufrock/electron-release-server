# API

A debug API is available to access more infos about releases.

There is also a more extensive REST api generated by [Sails](http://sailsjs.org) for managing releases.
This private api is used by the Admin UI & is authenticated through LDAP by default, but you can customize this for your own use without too much difficulty!

#### List versions:

```
GET http://download.myapp.com/api/versions
```

#### Get details about specific version:

```
GET http://download.myapp.com/api/version/1.1.0
```

#### Resolve a version:

```
GET http://download.myapp.com/api/resolve?platform=osx&channel=alpha
```

#### List channels:

```
GET http://download.myapp.com/api/channels
```
