# Xibang Common

[![github](https://img.shields.io/github/followers/willin.svg?style=social&label=Followers)](https://github.com/willin) [![npm](https://img.shields.io/npm/v/@xibang/node-common.svg)](https://npmjs.org/package/@xibang/node-common) [![npm](https://img.shields.io/npm/dt/@xibang/node-common.svg)](https://npmjs.org/package/@xibang/node-common) [![codebeat badge](https://codebeat.co/badges/2fc9ce50-a4ff-418c-84eb-b159ac64b5b4)](https://codebeat.co/projects/github-com-xibang-node-common-master) [![codecov](https://codecov.io/gh/xibang/node-common/branch/master/graph/badge.svg)](https://codecov.io/gh/xibang/node-common) [![Build Status](https://travis-ci.org/xibang/node-common.svg?branch=master)](https://travis-ci.org/xibang/node-common)

## 安装

```
npm install @xibang/node-common --save
```

## 使用

ES7:

```js
const { md5 } = require('@xibang/node-common');

console.log(md5('1'));
```

## 具体参数

### Members

#### <span class="type-signature"></span>isNumber<span class="type-signature"></span>

<div class="description">

判断是否为数字

</div>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 95](index.js.html#line95)

</dd>

</dl>

#### <span class="type-signature"></span>isObject<span class="type-signature"></span>

<div class="description">

判断是否为对象

</div>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 102](index.js.html#line102)

</dd>

</dl>

#### <span class="type-signature"></span>uuid<span class="type-signature"></span>

<div class="description">

生成GUID

</div>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 70](index.js.html#line70)

</dd>

</dl>

### Methods

#### <span class="type-signature"></span>formatDate<span class="signature">(inputPattern, inputDate)</span> <span class="type-signature">→ {string}</span>

<div class="description">

格式化时间

</div>

##### Parameters:

<table class="params">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th class="last">Description</th>

</tr>

</thead>

<tbody>

<tr>

<td class="name">`inputPattern`</td>

<td class="type"><span class="param-type">string</span></td>

<td class="description last">

时间格式,默认为'yyyy-MM-dd hh:mm:ss'

</td>

</tr>

<tr>

<td class="name">`inputDate`</td>

<td class="type"><span class="param-type">any</span></td>

<td class="description last">

输入时间,默认为当前

</td>

</tr>

</tbody>

</table>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 43](index.js.html#line43)

</dd>

</dl>

##### Returns:

<div class="param-desc">

格式化的时间

</div>

<dl>

<dt>Type</dt>

<dd><span class="param-type">string</span></dd>

</dl>

#### <span class="type-signature"></span>getDefer<span class="signature">()</span> <span class="type-signature">→ {Promise.defer}</span>

<div class="description">

getDefer

</div>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 181](index.js.html#line181)

</dd>

</dl>

##### Returns:

<div class="param-desc">

defer对象

</div>

<dl>

<dt>Type</dt>

<dd><span class="param-type">Promise.defer</span></dd>

</dl>

#### <span class="type-signature"></span>getTimestamp<span class="signature">()</span> <span class="type-signature">→ {int}</span>

<div class="description">

获取UNIX标准时间戳

</div>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 31](index.js.html#line31)

</dd>

</dl>

##### Returns:

<div class="param-desc">

UNIX标准时间戳

</div>

<dl>

<dt>Type</dt>

<dd><span class="param-type">int</span></dd>

</dl>

#### <span class="type-signature"></span>hmac<span class="signature">(str, type, key)</span> <span class="type-signature">→ {string}</span>

<div class="description">

Hmac

</div>

##### Parameters:

<table class="params">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th class="last">Description</th>

</tr>

</thead>

<tbody>

<tr>

<td class="name">`str`</td>

<td class="type"><span class="param-type">string</span></td>

<td class="description last">

待加密字符串

</td>

</tr>

<tr>

<td class="name">`type`</td>

<td class="type"><span class="param-type">string</span></td>

<td class="description last">

sha1或sha256

</td>

</tr>

<tr>

<td class="name">`key`</td>

<td class="type"><span class="param-type">string</span></td>

<td class="description last">

密钥

</td>

</tr>

</tbody>

</table>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 234](index.js.html#line234)

</dd>

</dl>

##### Returns:

<dl>

<dt>Type</dt>

<dd><span class="param-type">string</span></dd>

</dl>

#### <span class="type-signature"></span>int2ip<span class="signature">(num)</span> <span class="type-signature">→ {string}</span>

<div class="description">

INT2IP

</div>

##### Parameters:

<table class="params">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th class="last">Description</th>

</tr>

</thead>

<tbody>

<tr>

<td class="name">`num`</td>

<td class="type"><span class="param-type">int</span></td>

<td class="description last">

IP数值

</td>

</tr>

</tbody>

</table>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 262](index.js.html#line262)

</dd>

</dl>

##### Returns:

<div class="param-desc">

IP地址，如1.2.3.4

</div>

<dl>

<dt>Type</dt>

<dd><span class="param-type">string</span></dd>

</dl>

#### <span class="type-signature"></span>ip2int<span class="signature">(ip)</span> <span class="type-signature">→ {number}</span>

<div class="description">

IP2INT

</div>

##### Parameters:

<table class="params">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th class="last">Description</th>

</tr>

</thead>

<tbody>

<tr>

<td class="name">`ip`</td>

<td class="type"><span class="param-type">str</span></td>

<td class="description last">

IP地址，如1.2.3.4

</td>

</tr>

</tbody>

</table>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 245](index.js.html#line245)

</dd>

</dl>

##### Returns:

<div class="param-desc">

IP数值

</div>

<dl>

<dt>Type</dt>

<dd><span class="param-type">number</span></dd>

</dl>

#### <span class="type-signature"></span>isEmpty<span class="signature">(obj)</span> <span class="type-signature">→ {boolean}</span>

<div class="description">

判断是否为空

</div>

##### Parameters:

<table class="params">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th class="last">Description</th>

</tr>

</thead>

<tbody>

<tr>

<td class="name">`obj`</td>

<td class="type"><span class="param-type">*</span></td>

<td class="description last">

任意

</td>

</tr>

</tbody>

</table>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 113](index.js.html#line113)

</dd>

</dl>

##### Returns:

<div class="param-desc">

真为空，假为非空

</div>

<dl>

<dt>Type</dt>

<dd><span class="param-type">boolean</span></dd>

</dl>

#### <span class="type-signature"></span>isNumberString<span class="signature">(obj)</span> <span class="type-signature">→ {boolean}</span>

<div class="description">

判断是否为数字字符串

</div>

##### Parameters:

<table class="params">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th class="last">Description</th>

</tr>

</thead>

<tbody>

<tr>

<td class="name">`obj`</td>

<td class="type"><span class="param-type">*</span></td>

<td class="description last">

任意

</td>

</tr>

</tbody>

</table>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 83](index.js.html#line83)

</dd>

</dl>

##### Returns:

<div class="param-desc">

是否为数字字符串

</div>

<dl>

<dt>Type</dt>

<dd><span class="param-type">boolean</span></dd>

</dl>

#### <span class="type-signature"></span>JSONparse<span class="signature">(str, default)</span> <span class="type-signature">→ {object}</span>

<div class="description">

安全处理 JSON

</div>

##### Parameters:

<table class="params">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th class="last">Description</th>

</tr>

</thead>

<tbody>

<tr>

<td class="name">`str`</td>

<td class="type"><span class="param-type">string</span></td>

<td class="description last">

JSON字符串

</td>

</tr>

<tr>

<td class="name">`default`</td>

<td class="type"><span class="param-type">object</span></td>

<td class="description last">

默认值 {}

</td>

</tr>

</tbody>

</table>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 15](index.js.html#line15)

</dd>

</dl>

##### Returns:

<div class="param-desc">

JSON对象

</div>

<dl>

<dt>Type</dt>

<dd><span class="param-type">object</span></dd>

</dl>

#### <span class="type-signature"></span>md5<span class="signature">(str)</span> <span class="type-signature">→ {string}</span>

<div class="description">

MD5

</div>

##### Parameters:

<table class="params">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th class="last">Description</th>

</tr>

</thead>

<tbody>

<tr>

<td class="name">`str`</td>

<td class="type"><span class="param-type">string</span></td>

<td class="description last"></td>

</tr>

</tbody>

</table>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 199](index.js.html#line199)

</dd>

</dl>

##### Returns:

<dl>

<dt>Type</dt>

<dd><span class="param-type">string</span></dd>

</dl>

#### <span class="type-signature"></span>pad<span class="signature">(n, len, char)</span> <span class="type-signature">→ {string}</span>

<div class="description">

Pad Numbers

</div>

##### Parameters:

<table class="params">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th class="last">Description</th>

</tr>

</thead>

<tbody>

<tr>

<td class="name">`n`</td>

<td class="type"><span class="param-type">int</span></td>

<td class="description last">

数值

</td>

</tr>

<tr>

<td class="name">`len`</td>

<td class="type"><span class="param-type">int</span></td>

<td class="description last">

补位长度

</td>

</tr>

<tr>

<td class="name">`char`</td>

<td class="type"><span class="param-type">char</span></td>

<td class="description last">

补位字符，默认：0

</td>

</tr>

</tbody>

</table>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 283](index.js.html#line283)

</dd>

</dl>

##### Returns:

<div class="param-desc">

补位后的字符串

</div>

<dl>

<dt>Type</dt>

<dd><span class="param-type">string</span></dd>

</dl>

#### <span class="type-signature"></span>randNumber<span class="signature">(m, n)</span> <span class="type-signature">→ {int}</span>

<div class="description">

随机数

</div>

##### Parameters:

<table class="params">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th class="last">Description</th>

</tr>

</thead>

<tbody>

<tr>

<td class="name">`m`</td>

<td class="type"><span class="param-type">int</span></td>

<td class="description last">

m

</td>

</tr>

<tr>

<td class="name">`n`</td>

<td class="type"><span class="param-type">int</span></td>

<td class="description last">

n

</td>

</tr>

</tbody>

</table>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 175](index.js.html#line175)

</dd>

</dl>

##### Returns:

<div class="param-desc">

生成 m 到 n 的随机整数

</div>

<dl>

<dt>Type</dt>

<dd><span class="param-type">int</span></dd>

</dl>

#### <span class="type-signature"></span>randNumberStr<span class="signature">(len)</span> <span class="type-signature">→ {string}</span>

<div class="description">

随机数字字符串

</div>

##### Parameters:

<table class="params">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th class="last">Description</th>

</tr>

</thead>

<tbody>

<tr>

<td class="name">`len`</td>

<td class="type"><span class="param-type">int</span></td>

<td class="description last">

字符串长度

</td>

</tr>

</tbody>

</table>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 160](index.js.html#line160)

</dd>

</dl>

##### Returns:

<div class="param-desc">

const { randNumberStr } = require('@xibang/common'); const str = randNumberStr(6); console.log(str);

</div>

<dl>

<dt>Type</dt>

<dd><span class="param-type">string</span></dd>

</dl>

#### <span class="type-signature"></span>randStr<span class="signature">(len)</span> <span class="type-signature">→ {string}</span>

<div class="description">

随机字符串

</div>

##### Parameters:

<table class="params">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th class="last">Description</th>

</tr>

</thead>

<tbody>

<tr>

<td class="name">`len`</td>

<td class="type"><span class="param-type">int</span></td>

<td class="description last">

字符串长度

</td>

</tr>

</tbody>

</table>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 147](index.js.html#line147)

</dd>

</dl>

##### Returns:

<dl>

<dt>Type</dt>

<dd><span class="param-type">string</span></dd>

</dl>

#### <span class="type-signature"></span>sha1<span class="signature">(str)</span> <span class="type-signature">→ {string}</span>

<div class="description">

SHA1

</div>

##### Parameters:

<table class="params">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th class="last">Description</th>

</tr>

</thead>

<tbody>

<tr>

<td class="name">`str`</td>

<td class="type"><span class="param-type">string</span></td>

<td class="description last"></td>

</tr>

</tbody>

</table>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 210](index.js.html#line210)

</dd>

</dl>

##### Returns:

<dl>

<dt>Type</dt>

<dd><span class="param-type">string</span></dd>

</dl>

#### <span class="type-signature"></span>sha256<span class="signature">(str)</span> <span class="type-signature">→ {string}</span>

<div class="description">

SHA256

</div>

##### Parameters:

<table class="params">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th class="last">Description</th>

</tr>

</thead>

<tbody>

<tr>

<td class="name">`str`</td>

<td class="type"><span class="param-type">string</span></td>

<td class="description last"></td>

</tr>

</tbody>

</table>

<dl class="details">

<dt class="tag-source">Source:</dt>

<dd class="tag-source">

*   [index.js](index.js.html), [line 221](index.js.html#line221)

</dd>

</dl>

##### Returns:

<dl>

<dt>Type</dt>

<dd><span class="param-type">string</span></dd>

</dl>

## License

Apache 2.0

通过支付宝捐赠：

![qr](https://cloud.githubusercontent.com/assets/1890238/15489630/fccbb9cc-2193-11e6-9fed-b93c59d6ef37.png)
