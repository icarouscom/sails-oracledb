# sails-oracledb

## About

The sails-oracledb is a fork of sails-oracle-sp https://github.com/Buto/sails-oracledb-sp
It´s a adapter provides easy access to Oracle stored procedures for sails models.


```

### Usage

The input parameters are provided by the controller to the model and then to this adapter.

#### Sails connection

Specify the credential details needed to connect your Oracle instance in config/connections.js

##### Example connection named oraclehr

```javascript
  oraclehr: {
    adapter: 'sails-oracle-sp',
    user: 'hr',
    password: 'welcome',
    package: 'HR',
    cursorName: 'DETAILS',
    connectString: 'localhost/xe'
  }
```

* package is the name of the PL/SQL Package
* cursorName is the name of the PL/SQL ref cursor to return results



### License

**[MIT](./LICENSE)**
&copy; 2014


