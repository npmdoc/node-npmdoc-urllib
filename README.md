# api documentation for  [urllib (v2.21.2)](http://github.com/node-modules/urllib)  [![npm package](https://img.shields.io/npm/v/npmdoc-urllib.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-urllib) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-urllib.svg)](https://travis-ci.org/npmdoc/node-npmdoc-urllib)
#### Help in opening URLs (mostly HTTP) in a complex world — basic and digest authentication, redirections, cookies and more.

[![NPM](https://nodei.co/npm/urllib.png?downloads=true)](https://www.npmjs.com/package/urllib)

[![apidoc](https://npmdoc.github.io/node-npmdoc-urllib/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-urllib%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-urllib/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-urllib/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-urllib/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "fengmk2",
        "email": "fengmk2@gmail.com",
        "url": "https://fengmk2.com"
    },
    "bugs": {
        "url": "https://github.com/node-modules/urllib/issues"
    },
    "contributors": [
        {
            "name": "fengmk2",
            "email": "fengmk2@gmail.com",
            "url": "http://fengmk2.com"
        },
        {
            "name": "aleafs",
            "email": "zhangxc83@gmail.com",
            "url": "https://github.com/aleafs"
        },
        {
            "name": "Jackson Tian",
            "email": "shyvo1987@gmail.com",
            "url": "https://github.com/JacksonTian"
        },
        {
            "name": "ibigbug",
            "email": "x1aoba@icloud.com",
            "url": "https://github.com/ibigbug"
        },
        {
            "name": "XiNGRZ",
            "email": "chenxingyu92@gmail.com",
            "url": "https://github.com/XiNGRZ"
        },
        {
            "name": "dead_horse",
            "email": "dead_horse@qq.com",
            "url": "http://deadhorse.me/"
        },
        {
            "name": "coderhaoxin",
            "email": "coderhaoxin@outlook.com",
            "url": "https://github.com/coderhaoxin"
        },
        {
            "name": "alsotang",
            "email": "alsotang@gmail.com",
            "url": "https://github.com/alsotang"
        },
        {
            "name": "Jonathan Dahan",
            "email": "jonathan@jedahan.com",
            "url": "https://github.com/jedahan"
        },
        {
            "name": "popomore",
            "email": "sakura9515@gmail.com",
            "url": "https://github.com/popomore"
        },
        {
            "name": "fishbar",
            "email": "zhengxinlin@gmail.com",
            "url": "https://github.com/fishbar"
        },
        {
            "name": "coolme200",
            "email": "tangyao@taobao.com",
            "url": "https://github.com/coolme200"
        },
        {
            "name": "amunu",
            "email": "panyilinlove@qq.com",
            "url": "https://github.com/Amunu"
        },
        {
            "name": "Yuwei Ba",
            "email": "xiaobayuwei@gmail.com",
            "url": "https://github.com/ibigbug"
        }
    ],
    "dependencies": {
        "any-promise": "^1.3.0",
        "content-type": "^1.0.2",
        "debug": "^2.6.0",
        "default-user-agent": "^1.0.0",
        "digest-header": "^0.0.1",
        "ee-first": "~1.1.1",
        "humanize-ms": "^1.2.0",
        "iconv-lite": "^0.4.15",
        "statuses": "^1.3.1"
    },
    "description": "Help in opening URLs (mostly HTTP) in a complex world — basic and digest authentication, redirections, cookies and more.",
    "devDependencies": {
        "agentkeepalive": "^2.2.0",
        "autod": "*",
        "bluebird": "*",
        "busboy": "^0.2.14",
        "co": "*",
        "coffee": "1",
        "formstream": "^1.1.0",
        "intelli-espower-loader": "^1.0.1",
        "istanbul": "*",
        "jshint": "*",
        "mocha": "*",
        "muk": "^0.4.0",
        "pedding": "^1.1.0",
        "power-assert": "^1.4.2",
        "semver": "5",
        "tar": "^2.2.1",
        "through2": "^2.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "ecd7306224aae99fab3744fab707a43417f8abc5",
        "tarball": "https://registry.npmjs.org/urllib/-/urllib-2.21.2.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "lib"
    ],
    "gitHead": "2aceabdae24c2a1aca67e9485c3e6b684eaa81f8",
    "homepage": "http://github.com/node-modules/urllib",
    "keywords": [
        "urllib",
        "http",
        "urlopen",
        "curl",
        "wget",
        "request",
        "https"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "fengmk2",
            "email": "fengmk2@gmail.com"
        },
        {
            "name": "dead_horse",
            "email": "dead_horse@qq.com"
        }
    ],
    "name": "urllib",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/node-modules/urllib.git"
    },
    "scripts": {
        "autod": "autod -w --prefix '^' -t test -e examples",
        "ci": "npm run lint && npm run test-cov",
        "lint": "jshint .",
        "test": "npm run lint && mocha -R spec -t 30000 -r intelli-espower-loader test/*.test.js",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- -t 30000 -r intelli-espower-loader test/*.test.js"
    },
    "version": "2.21.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module urllib](#apidoc.module.urllib)
1.  [function <span class="apidocSignatureSpan">urllib.</span>HttpClient (options)](#apidoc.element.urllib.HttpClient)
1.  [function <span class="apidocSignatureSpan">urllib.</span>HttpClient2 (options)](#apidoc.element.urllib.HttpClient2)
1.  [function <span class="apidocSignatureSpan">urllib.</span>create (options)](#apidoc.element.urllib.create)
1.  [function <span class="apidocSignatureSpan">urllib.</span>curl (url, args, callback)](#apidoc.element.urllib.curl)
1.  [function <span class="apidocSignatureSpan">urllib.</span>request (url, args, callback)](#apidoc.element.urllib.request)
1.  [function <span class="apidocSignatureSpan">urllib.</span>requestThunk (url, args)](#apidoc.element.urllib.requestThunk)
1.  [function <span class="apidocSignatureSpan">urllib.</span>requestWithCallback (url, args, callback)](#apidoc.element.urllib.requestWithCallback)
1.  number <span class="apidocSignatureSpan">urllib.</span>TIMEOUT
1.  object <span class="apidocSignatureSpan">urllib.</span>HttpClient.prototype
1.  object <span class="apidocSignatureSpan">urllib.</span>HttpClient2.prototype
1.  object <span class="apidocSignatureSpan">urllib.</span>TIMEOUTS
1.  object <span class="apidocSignatureSpan">urllib.</span>agent
1.  object <span class="apidocSignatureSpan">urllib.</span>httpsAgent
1.  object <span class="apidocSignatureSpan">urllib.</span>urljs
1.  string <span class="apidocSignatureSpan">urllib.</span>USER_AGENT

#### [module urllib.HttpClient](#apidoc.module.urllib.HttpClient)
1.  [function <span class="apidocSignatureSpan">urllib.</span>HttpClient (options)](#apidoc.element.urllib.HttpClient.HttpClient)
1.  [function <span class="apidocSignatureSpan">urllib.HttpClient.</span>super_ ()](#apidoc.element.urllib.HttpClient.super_)

#### [module urllib.HttpClient.prototype](#apidoc.module.urllib.HttpClient.prototype)
1.  [function <span class="apidocSignatureSpan">urllib.HttpClient.prototype.</span>curl (url, args, callback)](#apidoc.element.urllib.HttpClient.prototype.curl)
1.  [function <span class="apidocSignatureSpan">urllib.HttpClient.prototype.</span>request (url, args, callback)](#apidoc.element.urllib.HttpClient.prototype.request)
1.  [function <span class="apidocSignatureSpan">urllib.HttpClient.prototype.</span>requestThunk (url, args)](#apidoc.element.urllib.HttpClient.prototype.requestThunk)

#### [module urllib.HttpClient2](#apidoc.module.urllib.HttpClient2)
1.  [function <span class="apidocSignatureSpan">urllib.</span>HttpClient2 (options)](#apidoc.element.urllib.HttpClient2.HttpClient2)
1.  [function <span class="apidocSignatureSpan">urllib.HttpClient2.</span>super_ (options)](#apidoc.element.urllib.HttpClient2.super_)

#### [module urllib.HttpClient2.prototype](#apidoc.module.urllib.HttpClient2.prototype)
1.  [function <span class="apidocSignatureSpan">urllib.HttpClient2.prototype.</span>curl (url, args)](#apidoc.element.urllib.HttpClient2.prototype.curl)
1.  [function <span class="apidocSignatureSpan">urllib.HttpClient2.prototype.</span>request (url, args)](#apidoc.element.urllib.HttpClient2.prototype.request)
1.  [function <span class="apidocSignatureSpan">urllib.HttpClient2.prototype.</span>requestThunk (url, args)](#apidoc.element.urllib.HttpClient2.prototype.requestThunk)

#### [module urllib.urljs](#apidoc.module.urllib.urljs)
1.  [function <span class="apidocSignatureSpan">urllib.urljs.</span>curl (url, args, callback)](#apidoc.element.urllib.urljs.curl)
1.  [function <span class="apidocSignatureSpan">urllib.urljs.</span>request (url, args, callback)](#apidoc.element.urllib.urljs.request)
1.  [function <span class="apidocSignatureSpan">urllib.urljs.</span>requestThunk (url, args)](#apidoc.element.urllib.urljs.requestThunk)
1.  [function <span class="apidocSignatureSpan">urllib.urljs.</span>requestWithCallback (url, args, callback)](#apidoc.element.urllib.urljs.requestWithCallback)
1.  number <span class="apidocSignatureSpan">urllib.urljs.</span>TIMEOUT
1.  object <span class="apidocSignatureSpan">urllib.urljs.</span>TIMEOUTS
1.  object <span class="apidocSignatureSpan">urllib.urljs.</span>agent
1.  object <span class="apidocSignatureSpan">urllib.urljs.</span>httpsAgent
1.  string <span class="apidocSignatureSpan">urllib.urljs.</span>USER_AGENT



# <a name="apidoc.module.urllib"></a>[module urllib](#apidoc.module.urllib)

#### <a name="apidoc.element.urllib.HttpClient"></a>[function <span class="apidocSignatureSpan">urllib.</span>HttpClient (options)](#apidoc.element.urllib.HttpClient)
- description and source-code
```javascript
function HttpClient(options) {
  EventEmitter.call(this);
  options = options || {};

  if (options.agent !== undefined) {
    this.agent = options.agent;
    this.hasCustomAgent = true;
  } else {
    this.agent = urllib.agent;
    this.hasCustomAgent = false;
  }

  if (options.httpsAgent !== undefined) {
    this.httpsAgent = options.httpsAgent;
    this.hasCustomHttpsAgent = true;
  } else {
    this.httpsAgent = urllib.httpsAgent;
    this.hasCustomHttpsAgent = false;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.urllib.HttpClient2"></a>[function <span class="apidocSignatureSpan">urllib.</span>HttpClient2 (options)](#apidoc.element.urllib.HttpClient2)
- description and source-code
```javascript
function HttpClient2(options) {
  HttpClient.call(this, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.urllib.create"></a>[function <span class="apidocSignatureSpan">urllib.</span>create (options)](#apidoc.element.urllib.create)
- description and source-code
```javascript
create = function (options) {
  return new exports.HttpClient(options);
}
```
- example usage
```shell
...
'''

## Global 'response' event

You should create a urllib instance first.

'''js
var httpclient = require('urllib').create();

httpclient.on('response', function (info) {
error: err,
ctx: args.ctx,
req: {
  url: url,
  options: options,
...
```

#### <a name="apidoc.element.urllib.curl"></a>[function <span class="apidocSignatureSpan">urllib.</span>curl (url, args, callback)](#apidoc.element.urllib.curl)
- description and source-code
```javascript
function request(url, args, callback) {
  // request(url, callback)
  if (arguments.length === 2 && typeof args === 'function') {
    callback = args;
    args = null;
  }
  if (typeof callback === 'function') {
    return exports.requestWithCallback(url, args, callback);
  }

  // Promise
  if (!_Promise) {
    _Promise = require('any-promise');
  }
  return new _Promise(function (resolve, reject) {
    exports.requestWithCallback(url, args, makeCallback(resolve, reject));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.urllib.request"></a>[function <span class="apidocSignatureSpan">urllib.</span>request (url, args, callback)](#apidoc.element.urllib.request)
- description and source-code
```javascript
function request(url, args, callback) {
  // request(url, callback)
  if (arguments.length === 2 && typeof args === 'function') {
    callback = args;
    args = null;
  }
  if (typeof callback === 'function') {
    return exports.requestWithCallback(url, args, callback);
  }

  // Promise
  if (!_Promise) {
    _Promise = require('any-promise');
  }
  return new _Promise(function (resolve, reject) {
    exports.requestWithCallback(url, args, makeCallback(resolve, reject));
  });
}
```
- example usage
```shell
...
## Usage

### callback

'''js
var urllib = require('urllib');

urllib.request('http://cnodejs.org/', function (err, data, res) {
if (err) {
  throw err; // you need to handle error
}
console.log(res.statusCode);
console.log(res.headers);
// data is Buffer instance
console.log(data.toString());
...
```

#### <a name="apidoc.element.urllib.requestThunk"></a>[function <span class="apidocSignatureSpan">urllib.</span>requestThunk (url, args)](#apidoc.element.urllib.requestThunk)
- description and source-code
```javascript
function requestThunk(url, args) {
  return function (callback) {
    exports.requestWithCallback(url, args, function (err, data, res) {
      if (err) {
        return callback(err);
      }
      callback(null, {
        data: data,
        status: res.statusCode,
        headers: res.headers,
        res: res
      });
    });
  };
}
```
- example usage
```shell
...
If you are using [co](https://github.com/visionmedia/co) or [koa](https://github.com/koajs/koa):

'''js
var co = require('co');
var urllib = require('urllib');

co(function* () {
  var result = yield urllib.requestThunk('http://nodejs.org');
  console.log('status: %s, body size: %d, headers: %j',
    result.status, result.data.length, result.headers);
})();
'''

## Global 'response' event
...
```

#### <a name="apidoc.element.urllib.requestWithCallback"></a>[function <span class="apidocSignatureSpan">urllib.</span>requestWithCallback (url, args, callback)](#apidoc.element.urllib.requestWithCallback)
- description and source-code
```javascript
function requestWithCallback(url, args, callback) {
  // requestWithCallback(url, callback)
  if (!url || (typeof url !== 'string' && typeof url !== 'object')) {
    var msg = util.format('expect request url to be a string or a http request options, but got %j', url);
    throw new Error(msg);
  }

  if (arguments.length === 2 && typeof args === 'function') {
    callback = args;
    args = null;
  }

  args = args || {};
  if (REQUEST_ID >= MAX_VALUE) {
    REQUEST_ID = 0;
  }
  var reqId = ++REQUEST_ID;

  args.requestUrls = args.requestUrls || [];

  var reqMeta = {
    requestId: reqId,
    url: url,
    args: args,
    ctx: args.ctx,
  };
  if (args.emitter) {
    args.emitter.emit('request', reqMeta);
  }

  args.timeout = args.timeout || exports.TIMEOUTS;
  args.maxRedirects = args.maxRedirects || 10;
  args.streaming = args.streaming || args.customResponse;
  var requestStartTime = Date.now();
  var parsedUrl;

  if (typeof url === 'string') {
    if (!PROTO_RE.test(url)) {
      // Support 'request('www.server.com')'
      url = 'http://' + url;
    }
    parsedUrl = urlutil.parse(url);
  } else {
    parsedUrl = url;
  }

  var method = (args.type || args.method || parsedUrl.method || 'GET').toUpperCase();
  var port = parsedUrl.port || 80;
  var httplib = http;
  var agent = getAgent(args.agent, exports.agent);
  var fixJSONCtlChars = !!args.fixJSONCtlChars;

  if (parsedUrl.protocol === 'https:') {
    httplib = https;
    agent = getAgent(args.httpsAgent, exports.httpsAgent);

    if (!parsedUrl.port) {
      port = 443;
    }
  }

  var options = {
    host: parsedUrl.hostname || parsedUrl.host || 'localhost',
    path: parsedUrl.path || '/',
    method: method,
    port: port,
    agent: agent,
    headers: args.headers || {},
    // default is dns.lookup
    // https://github.com/nodejs/node/blob/master/lib/net.js#L986
    // custom dnslookup require node >= 4.0.0
    // https://github.com/nodejs/node/blob/archived-io.js-v0.12/lib/net.js#L952
    lookup: args.lookup,
  };

  var sslNames = [
    'pfx',
    'key',
    'passphrase',
    'cert',
    'ca',
    'ciphers',
    'rejectUnauthorized',
    'secureProtocol',
    'secureOptions',
  ];
  for (var i = 0; i < sslNames.length; i++) {
    var name = sslNames[i];
    if (args.hasOwnProperty(name)) {
      options[name] = args[name];
    }
  }

  // don't check ssl
  if (options.rejectUnauthorized === false && !options.hasOwnProperty('secureOptions')) {
    options.secureOptions = require('constants').SSL_OP_NO_TLSv1_2;
  }

  var auth = args.auth || parsedUrl.auth;
  if (auth) {
    options.auth = auth;
  }

  var body = args.content || args.data;
  var dataAsQueryString = method === 'GET' || method === 'HEAD' || args.dataAsQueryString;
  if (!args.content) {
    if (body && !(typeof body === 'string' || Buffer.isBuffer(body))) {
      if (dataAsQueryString) {
        // read: GET, HEAD, use query string
        body = qs.stringify(body);
      } else {
        var contentType = options.headers['Content-Type'] || options.headers['content-type'];
        // auto add application/x-www-form-urlencoded when using urlencode form request
        if (!contentType) {
          if (args.contentType === 'json') {
            contentType = 'application/json';
          } else {
            contentType = 'application/x-www-form-urlencoded';
          }
          options.headers['Content-Type'] = contentType;
        }

        if (parseContentType(contentType).type === 'application/json') {
          body = JSON.stringify(body);
        } else {
          // 'application/x-www-form-urlencoded'
          body = qs.stringify(body);
        }
      }
    }
  }

  // if it's a GET or HEAD request, data should be sent as query string
  if (dataAsQueryString && body) {
    options.path += (parsedUrl.query ? '&' : '?') + body;
    body = null;
  }

  var requestSize = 0;
  if (body) {
    var length = body.length;
    if (!Buffer.isBuffer(body)) {
      length = Buffer.byteLength(body);
    }
    requestSize = options.headers['Content-Length'] = length;
  }

  if (args.dataT ...
```
- example usage
```shell
...
exports.request = function request(url, args, callback) {
// request(url, callback)
if (arguments.length === 2 && typeof args === 'function') {
  callback = args;
  args = null;
}
if (typeof callback === 'function') {
  return exports.requestWithCallback(url, args, callback);
}

// Promise
if (!_Promise) {
  _Promise = require('any-promise');
}
return new _Promise(function (resolve, reject) {
...
```



# <a name="apidoc.module.urllib.HttpClient"></a>[module urllib.HttpClient](#apidoc.module.urllib.HttpClient)

#### <a name="apidoc.element.urllib.HttpClient.HttpClient"></a>[function <span class="apidocSignatureSpan">urllib.</span>HttpClient (options)](#apidoc.element.urllib.HttpClient.HttpClient)
- description and source-code
```javascript
function HttpClient(options) {
  EventEmitter.call(this);
  options = options || {};

  if (options.agent !== undefined) {
    this.agent = options.agent;
    this.hasCustomAgent = true;
  } else {
    this.agent = urllib.agent;
    this.hasCustomAgent = false;
  }

  if (options.httpsAgent !== undefined) {
    this.httpsAgent = options.httpsAgent;
    this.hasCustomHttpsAgent = true;
  } else {
    this.httpsAgent = urllib.httpsAgent;
    this.hasCustomHttpsAgent = false;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.urllib.HttpClient.super_"></a>[function <span class="apidocSignatureSpan">urllib.HttpClient.</span>super_ ()](#apidoc.element.urllib.HttpClient.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.urllib.HttpClient.prototype"></a>[module urllib.HttpClient.prototype](#apidoc.module.urllib.HttpClient.prototype)

#### <a name="apidoc.element.urllib.HttpClient.prototype.curl"></a>[function <span class="apidocSignatureSpan">urllib.HttpClient.prototype.</span>curl (url, args, callback)](#apidoc.element.urllib.HttpClient.prototype.curl)
- description and source-code
```javascript
curl = function (url, args, callback) {
  if (typeof args === 'function') {
    callback = args;
    args = null;
  }
  args = args || {};
  args.emitter = this;
  args.agent = getAgent(args.agent, this.agent);
  args.httpsAgent = getAgent(args.httpsAgent, this.httpsAgent);
  return urllib.request(url, args, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.urllib.HttpClient.prototype.request"></a>[function <span class="apidocSignatureSpan">urllib.HttpClient.prototype.</span>request (url, args, callback)](#apidoc.element.urllib.HttpClient.prototype.request)
- description and source-code
```javascript
request = function (url, args, callback) {
  if (typeof args === 'function') {
    callback = args;
    args = null;
  }
  args = args || {};
  args.emitter = this;
  args.agent = getAgent(args.agent, this.agent);
  args.httpsAgent = getAgent(args.httpsAgent, this.httpsAgent);
  return urllib.request(url, args, callback);
}
```
- example usage
```shell
...
## Usage

### callback

'''js
var urllib = require('urllib');

urllib.request('http://cnodejs.org/', function (err, data, res) {
if (err) {
  throw err; // you need to handle error
}
console.log(res.statusCode);
console.log(res.headers);
// data is Buffer instance
console.log(data.toString());
...
```

#### <a name="apidoc.element.urllib.HttpClient.prototype.requestThunk"></a>[function <span class="apidocSignatureSpan">urllib.HttpClient.prototype.</span>requestThunk (url, args)](#apidoc.element.urllib.HttpClient.prototype.requestThunk)
- description and source-code
```javascript
requestThunk = function (url, args) {
  args = args || {};
  args.emitter = this;
  args.agent = getAgent(args.agent, this.agent);
  args.httpsAgent = getAgent(args.httpsAgent, this.httpsAgent);
  return urllib.requestThunk(url, args);
}
```
- example usage
```shell
...
If you are using [co](https://github.com/visionmedia/co) or [koa](https://github.com/koajs/koa):

'''js
var co = require('co');
var urllib = require('urllib');

co(function* () {
  var result = yield urllib.requestThunk('http://nodejs.org');
  console.log('status: %s, body size: %d, headers: %j',
    result.status, result.data.length, result.headers);
})();
'''

## Global 'response' event
...
```



# <a name="apidoc.module.urllib.HttpClient2"></a>[module urllib.HttpClient2](#apidoc.module.urllib.HttpClient2)

#### <a name="apidoc.element.urllib.HttpClient2.HttpClient2"></a>[function <span class="apidocSignatureSpan">urllib.</span>HttpClient2 (options)](#apidoc.element.urllib.HttpClient2.HttpClient2)
- description and source-code
```javascript
function HttpClient2(options) {
  HttpClient.call(this, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.urllib.HttpClient2.super_"></a>[function <span class="apidocSignatureSpan">urllib.HttpClient2.</span>super_ (options)](#apidoc.element.urllib.HttpClient2.super_)
- description and source-code
```javascript
function HttpClient(options) {
  EventEmitter.call(this);
  options = options || {};

  if (options.agent !== undefined) {
    this.agent = options.agent;
    this.hasCustomAgent = true;
  } else {
    this.agent = urllib.agent;
    this.hasCustomAgent = false;
  }

  if (options.httpsAgent !== undefined) {
    this.httpsAgent = options.httpsAgent;
    this.hasCustomHttpsAgent = true;
  } else {
    this.httpsAgent = urllib.httpsAgent;
    this.hasCustomHttpsAgent = false;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.urllib.HttpClient2.prototype"></a>[module urllib.HttpClient2.prototype](#apidoc.module.urllib.HttpClient2.prototype)

#### <a name="apidoc.element.urllib.HttpClient2.prototype.curl"></a>[function <span class="apidocSignatureSpan">urllib.HttpClient2.prototype.</span>curl (url, args)](#apidoc.element.urllib.HttpClient2.prototype.curl)
- description and source-code
```javascript
function request(url, args) {
  var self = this;
  args = args || {};
  args.retry = args.retry || 0;
  if (args.retryDelay) {
    args.retryDelay = ms(args.retryDelay);
  }
  args.isRetry = args.isRetry || function(res) {
    return res.status >= 500;
  };
  return HttpClient.prototype.request.call(self, url, args)
  .catch(function(err) {
    if (args.retry > 0) {
      args.retry--;
      debug('retry request %s, remain %s, err %s', url, args.retry, err);
      if (args.retryDelay) {
        debug('retry after %sms', args.retryDelay);
        return sleep(args.retryDelay).then(function() { return self.request(url, args); });
      }
      return self.request(url, args);
    }
    throw err;
  })
  .then(function(res) {
    if (args.retry > 0 && typeof args.isRetry === 'function' && args.isRetry(res)) {
      args.retry--;
      debug('retry request %s, remain %s', url, args.retry);
      if (args.retryDelay) {
        debug('retry after %sms', args.retryDelay);
        return sleep(args.retryDelay).then(function() { return self.request(url, args); });
      }
      return self.request(url, args);
    }
    return res;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.urllib.HttpClient2.prototype.request"></a>[function <span class="apidocSignatureSpan">urllib.HttpClient2.prototype.</span>request (url, args)](#apidoc.element.urllib.HttpClient2.prototype.request)
- description and source-code
```javascript
function request(url, args) {
  var self = this;
  args = args || {};
  args.retry = args.retry || 0;
  if (args.retryDelay) {
    args.retryDelay = ms(args.retryDelay);
  }
  args.isRetry = args.isRetry || function(res) {
    return res.status >= 500;
  };
  return HttpClient.prototype.request.call(self, url, args)
  .catch(function(err) {
    if (args.retry > 0) {
      args.retry--;
      debug('retry request %s, remain %s, err %s', url, args.retry, err);
      if (args.retryDelay) {
        debug('retry after %sms', args.retryDelay);
        return sleep(args.retryDelay).then(function() { return self.request(url, args); });
      }
      return self.request(url, args);
    }
    throw err;
  })
  .then(function(res) {
    if (args.retry > 0 && typeof args.isRetry === 'function' && args.isRetry(res)) {
      args.retry--;
      debug('retry request %s, remain %s', url, args.retry);
      if (args.retryDelay) {
        debug('retry after %sms', args.retryDelay);
        return sleep(args.retryDelay).then(function() { return self.request(url, args); });
      }
      return self.request(url, args);
    }
    return res;
  });
}
```
- example usage
```shell
...
## Usage

### callback

'''js
var urllib = require('urllib');

urllib.request('http://cnodejs.org/', function (err, data, res) {
if (err) {
  throw err; // you need to handle error
}
console.log(res.statusCode);
console.log(res.headers);
// data is Buffer instance
console.log(data.toString());
...
```

#### <a name="apidoc.element.urllib.HttpClient2.prototype.requestThunk"></a>[function <span class="apidocSignatureSpan">urllib.HttpClient2.prototype.</span>requestThunk (url, args)](#apidoc.element.urllib.HttpClient2.prototype.requestThunk)
- description and source-code
```javascript
function requestThunk(url, args) {
  var self = this;
  return function(done) {
    self.request(url, args)
    .catch(done)
    .then(function(res) {
      // if callback throw an error, promise will emit UnhandledPromiseRejection,
      // so use nextTick to prevent promise handling this error.
      process.nextTick(function() {
        done(null, res);
      });
    });
  };
}
```
- example usage
```shell
...
If you are using [co](https://github.com/visionmedia/co) or [koa](https://github.com/koajs/koa):

'''js
var co = require('co');
var urllib = require('urllib');

co(function* () {
  var result = yield urllib.requestThunk('http://nodejs.org');
  console.log('status: %s, body size: %d, headers: %j',
    result.status, result.data.length, result.headers);
})();
'''

## Global 'response' event
...
```



# <a name="apidoc.module.urllib.urljs"></a>[module urllib.urljs](#apidoc.module.urllib.urljs)

#### <a name="apidoc.element.urllib.urljs.curl"></a>[function <span class="apidocSignatureSpan">urllib.urljs.</span>curl (url, args, callback)](#apidoc.element.urllib.urljs.curl)
- description and source-code
```javascript
function request(url, args, callback) {
  // request(url, callback)
  if (arguments.length === 2 && typeof args === 'function') {
    callback = args;
    args = null;
  }
  if (typeof callback === 'function') {
    return exports.requestWithCallback(url, args, callback);
  }

  // Promise
  if (!_Promise) {
    _Promise = require('any-promise');
  }
  return new _Promise(function (resolve, reject) {
    exports.requestWithCallback(url, args, makeCallback(resolve, reject));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.urllib.urljs.request"></a>[function <span class="apidocSignatureSpan">urllib.urljs.</span>request (url, args, callback)](#apidoc.element.urllib.urljs.request)
- description and source-code
```javascript
function request(url, args, callback) {
  // request(url, callback)
  if (arguments.length === 2 && typeof args === 'function') {
    callback = args;
    args = null;
  }
  if (typeof callback === 'function') {
    return exports.requestWithCallback(url, args, callback);
  }

  // Promise
  if (!_Promise) {
    _Promise = require('any-promise');
  }
  return new _Promise(function (resolve, reject) {
    exports.requestWithCallback(url, args, makeCallback(resolve, reject));
  });
}
```
- example usage
```shell
...
## Usage

### callback

'''js
var urllib = require('urllib');

urllib.request('http://cnodejs.org/', function (err, data, res) {
if (err) {
  throw err; // you need to handle error
}
console.log(res.statusCode);
console.log(res.headers);
// data is Buffer instance
console.log(data.toString());
...
```

#### <a name="apidoc.element.urllib.urljs.requestThunk"></a>[function <span class="apidocSignatureSpan">urllib.urljs.</span>requestThunk (url, args)](#apidoc.element.urllib.urljs.requestThunk)
- description and source-code
```javascript
function requestThunk(url, args) {
  return function (callback) {
    exports.requestWithCallback(url, args, function (err, data, res) {
      if (err) {
        return callback(err);
      }
      callback(null, {
        data: data,
        status: res.statusCode,
        headers: res.headers,
        res: res
      });
    });
  };
}
```
- example usage
```shell
...
If you are using [co](https://github.com/visionmedia/co) or [koa](https://github.com/koajs/koa):

'''js
var co = require('co');
var urllib = require('urllib');

co(function* () {
  var result = yield urllib.requestThunk('http://nodejs.org');
  console.log('status: %s, body size: %d, headers: %j',
    result.status, result.data.length, result.headers);
})();
'''

## Global 'response' event
...
```

#### <a name="apidoc.element.urllib.urljs.requestWithCallback"></a>[function <span class="apidocSignatureSpan">urllib.urljs.</span>requestWithCallback (url, args, callback)](#apidoc.element.urllib.urljs.requestWithCallback)
- description and source-code
```javascript
function requestWithCallback(url, args, callback) {
  // requestWithCallback(url, callback)
  if (!url || (typeof url !== 'string' && typeof url !== 'object')) {
    var msg = util.format('expect request url to be a string or a http request options, but got %j', url);
    throw new Error(msg);
  }

  if (arguments.length === 2 && typeof args === 'function') {
    callback = args;
    args = null;
  }

  args = args || {};
  if (REQUEST_ID >= MAX_VALUE) {
    REQUEST_ID = 0;
  }
  var reqId = ++REQUEST_ID;

  args.requestUrls = args.requestUrls || [];

  var reqMeta = {
    requestId: reqId,
    url: url,
    args: args,
    ctx: args.ctx,
  };
  if (args.emitter) {
    args.emitter.emit('request', reqMeta);
  }

  args.timeout = args.timeout || exports.TIMEOUTS;
  args.maxRedirects = args.maxRedirects || 10;
  args.streaming = args.streaming || args.customResponse;
  var requestStartTime = Date.now();
  var parsedUrl;

  if (typeof url === 'string') {
    if (!PROTO_RE.test(url)) {
      // Support 'request('www.server.com')'
      url = 'http://' + url;
    }
    parsedUrl = urlutil.parse(url);
  } else {
    parsedUrl = url;
  }

  var method = (args.type || args.method || parsedUrl.method || 'GET').toUpperCase();
  var port = parsedUrl.port || 80;
  var httplib = http;
  var agent = getAgent(args.agent, exports.agent);
  var fixJSONCtlChars = !!args.fixJSONCtlChars;

  if (parsedUrl.protocol === 'https:') {
    httplib = https;
    agent = getAgent(args.httpsAgent, exports.httpsAgent);

    if (!parsedUrl.port) {
      port = 443;
    }
  }

  var options = {
    host: parsedUrl.hostname || parsedUrl.host || 'localhost',
    path: parsedUrl.path || '/',
    method: method,
    port: port,
    agent: agent,
    headers: args.headers || {},
    // default is dns.lookup
    // https://github.com/nodejs/node/blob/master/lib/net.js#L986
    // custom dnslookup require node >= 4.0.0
    // https://github.com/nodejs/node/blob/archived-io.js-v0.12/lib/net.js#L952
    lookup: args.lookup,
  };

  var sslNames = [
    'pfx',
    'key',
    'passphrase',
    'cert',
    'ca',
    'ciphers',
    'rejectUnauthorized',
    'secureProtocol',
    'secureOptions',
  ];
  for (var i = 0; i < sslNames.length; i++) {
    var name = sslNames[i];
    if (args.hasOwnProperty(name)) {
      options[name] = args[name];
    }
  }

  // don't check ssl
  if (options.rejectUnauthorized === false && !options.hasOwnProperty('secureOptions')) {
    options.secureOptions = require('constants').SSL_OP_NO_TLSv1_2;
  }

  var auth = args.auth || parsedUrl.auth;
  if (auth) {
    options.auth = auth;
  }

  var body = args.content || args.data;
  var dataAsQueryString = method === 'GET' || method === 'HEAD' || args.dataAsQueryString;
  if (!args.content) {
    if (body && !(typeof body === 'string' || Buffer.isBuffer(body))) {
      if (dataAsQueryString) {
        // read: GET, HEAD, use query string
        body = qs.stringify(body);
      } else {
        var contentType = options.headers['Content-Type'] || options.headers['content-type'];
        // auto add application/x-www-form-urlencoded when using urlencode form request
        if (!contentType) {
          if (args.contentType === 'json') {
            contentType = 'application/json';
          } else {
            contentType = 'application/x-www-form-urlencoded';
          }
          options.headers['Content-Type'] = contentType;
        }

        if (parseContentType(contentType).type === 'application/json') {
          body = JSON.stringify(body);
        } else {
          // 'application/x-www-form-urlencoded'
          body = qs.stringify(body);
        }
      }
    }
  }

  // if it's a GET or HEAD request, data should be sent as query string
  if (dataAsQueryString && body) {
    options.path += (parsedUrl.query ? '&' : '?') + body;
    body = null;
  }

  var requestSize = 0;
  if (body) {
    var length = body.length;
    if (!Buffer.isBuffer(body)) {
      length = Buffer.byteLength(body);
    }
    requestSize = options.headers['Content-Length'] = length;
  }

  if (args.dataT ...
```
- example usage
```shell
...
exports.request = function request(url, args, callback) {
// request(url, callback)
if (arguments.length === 2 && typeof args === 'function') {
  callback = args;
  args = null;
}
if (typeof callback === 'function') {
  return exports.requestWithCallback(url, args, callback);
}

// Promise
if (!_Promise) {
  _Promise = require('any-promise');
}
return new _Promise(function (resolve, reject) {
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
