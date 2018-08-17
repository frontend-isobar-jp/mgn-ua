# mgn-ua ( Don't Need jQuery )


class that summarizes function/variable such as user agent acquisition.

___

# Install

```
npm i mgn-ua -S
```

## Or Download raw data
[↓ download "mgn-ua.js"](https://raw.githubusercontent.com/frontend-isobar-jp/mgn-ua/master/src/mgn-ua.js)

___

# Import

```
import mgnUa from 'mgn-ua';
```

___

# Constructor

```
new mgnUa();
```

___

# Property

|Property|Data type|Default|Descroption|
|:-------|:--------|:------|:----------|
|isMSIE|Boolean|-|IE (11 and above)|
|isIE6|Boolean|-|IE6|
|isIE7|Boolean|-|IE7|
|isIE8|Boolean|-|IE8|
|isIE9|Boolean|-|IE9|
|isIE10|Boolean|-|IE10|
|isIE11|Boolean|-|IE11|
|isIE|Boolean|-|IE (all versions)|
|isEdge|Boolean|-|Edge|
|isChrome|Boolean|-|Chrome|
|isFirefox|Boolean|-|Firefox|
|isSafari|Boolean|-|Safari|
|isOpera|Boolean|-|Opera|
|isIphone|Boolean|-|iPhone|
|isIpod|Boolean|-|iPod|
|isAndroid|Boolean|-|Android|
|isWinPhone|Boolean|-|WinPhone|
|isIpad|Boolean|-|iPad|
|isAndroidTab|Boolean|-|AndroidTab|
|isSp|Boolean|-|iPhone / iPod / Android / WinPhone|
|isTab|Boolean|-|iPad / AndroidTab|
|isTouch|Boolean|-|Enables touch event or not|

___

# Method

|Method|Argument|Descroption|
|:-------|:--------|:----------|
|GetIosVersion()|-|Get iOS version.|
|GetAndroidVersion()|-|Get Android version.|
___

# Sample code

```
import mgnUa from 'mgn-ua';

//

let UA = new mgnUa();

if( UA.isIE9 ) {
    alert("isIE9");
}

//

if( UA.GetIosVersion() == 9.2 ) {
    alert("iOS v9.2");
}
```
