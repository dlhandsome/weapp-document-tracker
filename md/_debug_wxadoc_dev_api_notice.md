<div class="book with-summary">

<div class="head">

<div class="head_box">

# [](javascript:; "_('微信公众平台 小程序')")

<div class="header_ctrls">

*   [介绍](https://mp.weixin.qq.com/debug/wxadoc/introduction/index.html?t=2017616)
*   [设计](https://mp.weixin.qq.com/debug/wxadoc/design/index.html?t=2017616)
*   [开发](https://mp.weixin.qq.com/debug/wxadoc/dev/index.html?t=2017616)
*   [运营](https://mp.weixin.qq.com/debug/wxadoc/product/index.html?t=2017616)
*   [数据](https://mp.weixin.qq.com/debug/wxadoc/analysis/index.html?t=2017616)

</div>

</div>

</div>

<div class="sub_nav_box">

<div class="sub_nav_inner">

<div class="book-summary-opr" id="js-book-summary-opr"><a class="book-summary-btn"></a></div>

<div class="top_sub_nav">

<div class="top_title_wap"><span class="icon_title icon_dev"></span>

微信小程序开发文档

</div>

*   [简易教程](../)
*   [框架](../framework/MINA.html)
*   [组件](../component/)
*   [API](./)
*   [工具](../devtools/devtools.html)
*   [Q&A](../qa.html)

</div>

<div id="book-search-input" role="search">

<form><label for="search-input" class="search-icon" id="js-search-icon"></label><input type="text" id="search-input" name="search-input" placeholder="搜索"> </form>

</div>

</div>

</div>

<div class="book-summary">

<div class="book-summary-home" id="js-summary-home"><a><span class="icon_home_s icon_dev"></span><span class="s_title_2">开发文档首页</span></a></div>

<nav role="navigation">

*   [网络](api-network.html)
    *   [发起请求](network-request.html)
        *   [wx.request](network-request.html#wxrequestobject)
    *   [上传、下载](network-file.html)
        *   [wx.uploadFile](network-file.html#wxuploadfileobject)
        *   [wx.downloadFile](network-file.html#wxdownloadfileobject)
    *   [WebSocket](network-socket.html)
        *   [wx.connectSocket](network-socket.html#wxconnectsocketobject)
        *   [wx.onSocketOpen](network-socket.html#wxonsocketopencallback)
        *   [wx.onSocketError](network-socket.html#wxonsocketerrorcallback)
        *   [wx.sendSocketMessage](network-socket.html#wxsendsocketmessageobject)
        *   [wx.onSocketMessage](network-socket.html#wxonsocketmessagecallback)
        *   [wx.closeSocket](network-socket.html#wxclosesocket)
        *   [wx.onSocketClose](network-socket.html#wxonsocketclosecallback)
*   [媒体](media-picture.html)
    *   [图片](media-picture.html)
        *   [wx.chooseImage](media-picture.html#wxchooseimageobject)
        *   [wx.previewImage](media-picture.html#wxpreviewimageobject)
        *   [wx.getImageInfo](media-picture.html#wxgetimageinfoobject)
        *   [wx.saveImageToPhotosAlbum](media-picture.html#wxsaveimagetophotosalbumobject)
    *   [录音](media-record.html)
        *   [wx.startRecord](media-record.html#wxstartrecordobject)
        *   [wx.stopRecord](media-record.html#wxstoprecord)
    *   [音频播放控制](media-voice.html)
        *   [wx.playVoice](media-voice.html#wxplayvoiceobject)
        *   [wx.pauseVoice](media-voice.html#wxpausevoice)
        *   [wx.stopVoice](media-voice.html#wxstopvoice)
    *   [音乐播放控制](media-background-audio.html)
        *   [wx.getBackgroundAudioPlayerState](media-background-audio.html#wxgetbackgroundaudioplayerstateobject)
        *   [wx.playBackgroundAudio](media-background-audio.html#wxplaybackgroundaudioobject)
        *   [wx.pauseBackgroundAudio](media-background-audio.html#wxpausebackgroundaudio)
        *   [wx.seekBackgroundAudio](media-background-audio.html#wxseekbackgroundaudioobject)
        *   [wx.stopBackgroundAudio](media-background-audio.html#wxstopbackgroundaudio)
        *   [wx.onBackgroundAudioPlay](media-background-audio.html#wxonbackgroundaudioplaycallback)
        *   [wx.onBackgroundAudioPause](media-background-audio.html#wxonbackgroundaudiopausecallback)
        *   [wx.onBackgroundAudioStop](media-background-audio.html#wxonbackgroundaudiostopcallback)
    *   [背景音频播放管理](getBackgroundAudioManager.html)
        *   [wx.getBackgroundAudioManager](getBackgroundAudioManager.html)
    *   [音频组件控制](api-audio.html)
        *   [wx.createAudioContext](api-audio.html#wxcreateaudiocontextaudioid)
    *   [视频](media-video.html)
        *   [wx.chooseVideo](media-video.html#wxchoosevideoobject)
        *   [wx.saveVideoToPhotosAlbum](media-video.html#wxsavevideotophotosalbumobject)
    *   [视频组件控制](api-video.html)
        *   [wx.createVideoContext](api-video.html#wxcreatevideocontextvideoid)
*   [文件](file.html)
    *   [wx.saveFile](file.html#wxsavefileobject)
    *   [wx.getSavedFileList](file.html#wxgetsavedfilelistobject)
    *   [wx.getSavedFileInfo](file.html#wxgetsavedfileinfoobject)
    *   [wx.removeSavedFile](file.html#wxremovesavedfileobject)
    *   [wx.openDocument](file.html#wxopendocumentobject)
*   [数据缓存](data.html)
    *   [wx.setStorage](data.html#wxsetstorageobject)
    *   [wx.setStorageSync](data.html#wxsetstoragesynckeydata)
    *   [wx.getStorage](data.html#wxgetstorageobject)
    *   [wx.getStorageSync](data.html#wxgetstoragesynckey)
    *   [wx.getStorageInfo](data.html#wxgetstorageinfoobject)
    *   [wx.getStorageInfoSync](data.html#wxgetstorageinfosync)
    *   [wx.removeStorage](data.html#wxremovestorageobject)
    *   [wx.removeStorageSync](data.html#wxremovestoragesynckey)
    *   [wx.clearStorage](data.html#wxclearstorage)
    *   [wx.clearStorageSync](data.html#wxclearstoragesync)
*   [位置](location.html)
    *   [获取位置](location.html)
        *   [wx.getLocation](location.html#wxgetlocationobject)
        *   [wx.chooseLocation](location.html#wxchooselocationobject)
    *   [查看位置](location.html#wxopenlocationobject)
        *   [wx.openLocation](location.html#wxopenlocationobject)
    *   [地图组件控制](api-map.html)
        *   [wx.createMapContext](api-map.html#wxcreatemapcontextmapid)
*   [设备](systeminfo.html)
    *   [系统信息](systeminfo.html)
        *   [wx.getSystemInfo](systeminfo.html#wxgetsysteminfoobject)
        *   [wx.getSystemInfoSync](systeminfo.html#wxgetsysteminfosync)
        *   [wx.canIUse](api-caniuse.html)
    *   [网络状态](device.html)
        *   [wx.getNetworkType](device.html#wxgetnetworktypeobject)
        *   [wx.onNetworkStatusChange](device.html#wxonnetworkstatuschangecallback)
    *   [加速度计](accelerometer.html)
        *   [wx.onAccelerometerChange](accelerometer.html#wxonaccelerometerchangecallback)
        *   [wx.startAccelerometer](accelerometer.html#wxstartaccelerometerobject)
        *   [wx.stopAccelerometer](accelerometer.html#wxstopaccelerometerobject)
    *   [罗盘](compass.html)
        *   [wx.onCompassChange](compass.html#wxoncompasschangecallback)
        *   [wx.startCompass](compass.html#wxstartcompassobject)
        *   [wx.stopCompass](compass.html#wxstopcompassobject)
    *   [拨打电话](phonecall.html)
        *   [wx.makePhoneCall](phonecall.html#wxmakephonecallobject)
    *   [扫码](scancode.html)
        *   [wx.scanCode](scancode.html#wxscancodeobject)
    *   [剪贴板](clipboard.html)
        *   [wx.setClipboardData](clipboard.html#wxsetclipboarddataobject)
        *   [wx.getClipboardData](clipboard.html#wxgetclipboarddataobject)
    *   [蓝牙](bluetooth.html)
        *   [wx.openBluetoothAdapter](bluetooth.html#wxopenbluetoothadapterobject)
        *   [wx.closeBluetoothAdapter](bluetooth.html#wxclosebluetoothadapterobject)
        *   [wx.getBluetoothAdapterState](bluetooth.html#wxgetbluetoothadapterstateobject)
        *   [wx.onBluetoothAdapterStateChange](bluetooth.html#wxonbluetoothadapterstatechangecallback)
        *   [wx.startBluetoothDevicesDiscovery](bluetooth.html#wxstartbluetoothdevicesdiscoveryobject)
        *   [wx.stopBluetoothDevicesDiscovery](bluetooth.html#wxstopbluetoothdevicesdiscoveryobject)
        *   [wx.getBluetoothDevices](bluetooth.html#wxgetbluetoothdevicesobject)
        *   [wx.getConnectedBluetoothDevices](bluetooth.html#wxgetconnectedbluetoothdevicesobject)
        *   [wx.onBluetoothDeviceFound](bluetooth.html#wxonbluetoothdevicefoundcallback)
        *   [wx.createBLEConnection](bluetooth.html#wxcreatebleconnectionobject)
        *   [wx.closeBLEConnection](bluetooth.html#wxclosebleconnectionobject)
        *   [wx.getBLEDeviceServices](bluetooth.html#wxgetbledeviceservicesobject)
        *   [wx.getBLEDeviceCharacteristics](bluetooth.html#wxgetbledevicecharacteristicsobject)
        *   [wx.readBLECharacteristicValue](bluetooth.html#wxreadblecharacteristicvalueobject)
        *   [wx.writeBLECharacteristicValue](bluetooth.html#wxwriteblecharacteristicvalueobject)
        *   [wx.notifyBLECharacteristicValueChange](bluetooth.html#wxnotifyblecharacteristicvaluechangeobject)
        *   [wx.onBLEConnectionStateChange](bluetooth.html#wxonbleconnectionstatechangecallback)
        *   [wx.onBLECharacteristicValueChange](bluetooth.html#wxonblecharacteristicvaluechangecallback)
    *   [iBeacon](iBeacon.html)
        *   [wx.startBeaconDiscovery](iBeacon.html#wxstartbeacondiscoveryobject)
        *   [wx.stopBeaconDiscovery](iBeacon.html#wxstopbeacondiscoveryobject)
        *   [wx.getBeacons](iBeacon.html#wxgetbeaconsobject)
        *   [wx.onBeaconUpdate](iBeacon.html#wxonbeaconupdatecallback)
        *   [wx.onBeaconServiceChange](iBeacon.html#wxonbeaconservicechangecallback)
    *   [屏幕亮度](device.html#wxsetscreenbrightnessobject)
        *   [wx.setScreenBrightness](device.html#wxsetscreenbrightnessobject)
        *   [wx.getScreenBrightness](device.html#wxgetscreenbrightnessobject)
    *   [振动](device.html#wxvibratelongobject)
        *   [wx.vibrateLong](device.html#wxvibratelongobject)
        *   [wx.vibrateShort](device.html#wxvibrateshortobject)
    *   [手机联系人](phone-contact.html)
        *   [wx.addPhoneContact](phone-contact.html#wxaddphonecontactobject)
*   [界面](api-react.html)
    *   [交互反馈](api-react.html)
        *   [wx.showToast](api-react.html#wxshowtoastobject)
        *   [wx.showLoading](api-react.html#wxshowloadingobject)
        *   [wx.hideToast](api-react.html#wxhidetoast)
        *   [wx.hideLoading](api-react.html#wxhideloading)
        *   [wx.showModal](api-react.html#wxshowmodalobject)
        *   [wx.showActionSheet](api-react.html#wxshowactionsheetobject)
    *   [设置导航条](ui.html)
        *   [wx.setNavigationBarTitle](ui.html#wxsetnavigationbartitleobject)
        *   [wx.showNavigationBarLoading](ui.html#wxshownavigationbarloading)
        *   [wx.hideNavigationBarLoading](ui.html#wxhidenavigationbarloading)
    *   [导航](ui-navigate.html)
        *   [wx.navigateTo](ui-navigate.html#wxnavigatetoobject)
        *   [wx.redirectTo](ui-navigate.html#wxredirecttoobject)
        *   [wx.switchTab](ui-navigate.html#wxswitchtabobject)
        *   [wx.navigateBack](ui-navigate.html#wxnavigatebackobject)
        *   [wx.reLaunch](ui-navigate.html#wxrelaunchobject)
    *   [动画](api-animation.html)
        *   [wx.createAnimation](api-animation.html#wxcreateanimationobject)
    *   [绘图](canvas/reference.html)
        *   [intro](canvas/intro.html)
        *   [coordinates](canvas/coordinates.html)
        *   [gradient](canvas/gradient.html)
        *   [reference](canvas/reference.html)
        *   [color](canvas/color.html)
        *   [wx.createCanvasContext](canvas/create-canvas-context.html)
        *   [wx.createContext](canvas/create-context.html)
        *   [wx.drawCanvas](canvas/draw-canvas.html)
        *   [wx.canvasToTempFilePath](canvas/temp-file.html)
        *   [setFillStyle](canvas/set-fill-style.html)
        *   [setStrokeStyle](canvas/set-stroke-style.html)
        *   [setShadow](canvas/set-shadow.html)
        *   [createLinearGradient](canvas/create-linear-gradient.html)
        *   [createCircularGradient](canvas/create-circular-gradient.html)
        *   [addColorStop](canvas/add-color-stop.html)
        *   [setLineWidth](canvas/set-line-width.html)
        *   [setLineCap](canvas/set-line-cap.html)
        *   [setLineJoin](canvas/set-line-join.html)
        *   [setMiterLimit](canvas/set-miter-limit.html)
        *   [rect](canvas/rect.html)
        *   [fillRect](canvas/fill-rect.html)
        *   [strokeRect](canvas/stroke-rect.html)
        *   [clearRect](canvas/clear-rect.html)
        *   [fill](canvas/fill.html)
        *   [stroke](canvas/stroke.html)
        *   [beginPath](canvas/begin-path.html)
        *   [closePath](canvas/close-path.html)
        *   [moveTo](canvas/move-to.html)
        *   [lineTo](canvas/line-to.html)
        *   [arc](canvas/arc.html)
        *   [bezierCurveTo](canvas/bezier-curve-to.html)
        *   [quadraticCurveTo](canvas/quadratic-curve-to.html)
        *   [scale](canvas/scale.html)
        *   [rotate](canvas/rotate.html)
        *   [translate](canvas/translate.html)
        *   [setFontSize](canvas/set-font-size.html)
        *   [fillText](canvas/fill-text.html)
        *   [setTextAlign](canvas/set-text-align.html)
        *   [drawImage](canvas/draw-image.html)
        *   [setGlobalAlpha](canvas/set-global-alpha.html)
        *   [save](canvas/save-restore.html)
        *   [restore](canvas/save-restore.html#restore)
        *   [draw](canvas/draw.html)
        *   [getActions](canvas/get-actions.html)
        *   [clearActions](canvas/clear-actions.html)
    *   [下拉刷新](pulldown.html)
        *   [Page.onPullDownRefresh](pulldown.html#onpulldownrefresh)
        *   [wx.stopPullDownRefresh](pulldown.html#wxstoppulldownrefresh)
*   [第三方平台](ext-api.html)
    *   [wx.getExtConfig](ext-api.html#wxgetextconfigobject)
    *   [wx.getExtConfigSync](ext-api.html#wxgetextconfigsync)
*   [开放接口](api-login.html)
    *   [登录](api-login.html)
        *   [wx.login](api-login.html#wxloginobject)
        *   [wx.checkSession](api-login.html#wxchecksessionobject)
        *   [签名加密](signature.html)
    *   [授权](authorize.html)
        *   [wx.authorize](authorize.html#wxauthorizeobject)
    *   [用户信息](open.html)
        *   [wx.getUserInfo](open.html#wxgetuserinfoobject)
    *   [微信支付](api-pay.html)
        *   [wx.requestPayment](api-pay.html#wxrequestpaymentobject)
    *   [模板消息](notice.html)
        *   [使用说明](notice.html#使用说明)
        *   [接口说明](notice.html#接口说明)
    *   [客服消息](custommsg/receive.html)
        *   [接收消息和事件](custommsg/receive.html#接收消息和事件)
            *   [文本消息](custommsg/receive.html#文本消息)
            *   [图片消息](custommsg/receive.html#图片消息)
            *   [进入会话事件](custommsg/receive.html#进入会话事件)
        *   [发送客服消息](custommsg/conversation.html)
        *   [临时素材接口](custommsg/material.html)
            *   [获取临时素材](custommsg/material.html#获取临时素材)
            *   [新增临时素材](custommsg/material.html#新增临时素材)
        *   [接入指引](custommsg/callback_help.html)
    *   [转发](share.html)
        *   [Page.onShareAppMessage](share.html#onshareappmessage)
        *   [wx.showShareMenu](share.html#wxshowsharemenuobject)
        *   [wx.hideShareMenu](share.html#wxhidesharemenuobject)
        *   [wx.updateShareMenu](share.html#wxupdatesharemenuobject)
        *   [wx.getShareInfo](share.html#wxgetshareinfoobject)
        *   [获取更多转发信息](share.html#获取更多转发信息)
        *   [页面内发起转发](share.html#页面内发起转发)
    *   [获取二维码](qrcode.html)
    *   [收货地址](address.html)
        *   [wx.chooseAddress](address.html#wxchooseaddressobject)
    *   [卡券](card.html)
        *   [wx.addCard](card.html#wxaddcardobject)
        *   [wx.openCard](card.html#wxopencardobject)
    *   [设置](setting.html)
        *   [wx.openSetting](setting.html#wxopensettingobject)
        *   [wx.getSetting](setting.html#wxgetsettingobject)
    *   [微信运动](we-run.html)
        *   [wx.getWeRunData](we-run.html#wxgetwerundataobject)
*   [数据](analysis.html)
    *   [常规分析](analysis.html)
        *   [概况](analysis.html#概况)
            *   [概况趋势](analysis.html#概况趋势)
        *   [访问分析](analysis-visit.html#访问分析)
            *   [访问趋势](analysis-visit.html#访问趋势)
            *   [访问分布](analysis-visit.html#访问分布)
            *   [访问留存](analysis-visit.html#访问留存)
            *   [访问页面](analysis-visit.html#访问页面)
        *   [用户画像](analysis-user.html)
    *   [自定义分析](analysis-report.html)
        *   [自定义数据上报](analysis-report.html)
*   [拓展接口](api-util.html)
    *   [wx.arrayBufferToBase64](api-util.html#wxarraybuffertobase64arraybuffer)
    *   [wx.base64ToArrayBuffer](api-util.html#wxbase64toarraybufferbase64)

</nav>

</div>

<div class="book-body">

<div class="body-inner">

<div class="page-wrapper" tabindex="-1" role="main">

<div class="page-inner">

<div id="book-search-results">

<div class="search-noresults">

<section class="normal markdown-section">

基于微信的通知渠道，我们为开发者提供了可以高效触达用户的模板消息能力，以便实现服务的闭环并提供更佳的体验。

模板推送位置：服务通知

模板下发条件：用户本人在微信体系内与页面有交互行为后触发，详见[下发条件说明](#下发条件说明)

模板跳转能力：点击查看详情仅能跳转下发模板的该帐号的各个页面

## 使用说明

1.  获取模板 id

登录[https://mp.weixin.qq.com](https://mp.weixin.qq.com)获取模板，如果没有合适的模板，可以申请添加新模板，审核通过后可使用，详见[模板审核说明](#审核说明)

![](https://mp.weixin.qq.com/debug/wxadoc/dev/image/mp-notice.png?t=2017616)

1.  页面的 [`<form/>`](../component/form.html) 组件，属性`report-submit`为`true`时，可以声明为需发模板消息，此时点击按钮提交表单可以获取`formId`，用于发送模板消息。或者当用户完成[支付行为](api-pay.html)，可以获取`prepay_id`用于发送模板消息。

2.  调用接口下发模板消息（详见[接口说明](#接口说明)）

## 接口说明

### 1\. 获取 access_token

access_token 是全局唯一接口调用凭据，开发者调用各接口时都需使用 access_token，请妥善保存。access_token 的存储至少要保留512个字符空间。access_token 的有效期目前为2个小时，需定时刷新，重复获取将导致上次获取的 access_token 失效。

公众平台的 API 调用所需的 access_token 的使用及生成方式说明：

1.  为了保密 appsecrect，第三方需要一个 access_token 获取和刷新的中控服务器。而其他业务逻辑服务器所使用的 access_token 均来自于该中控服务器，不应该各自去刷新，否则会造成 access_token 覆盖而影响业务；
2.  目前 access_token 的有效期通过返回的 expires_in 来传达，目前是7200秒之内的值。中控服务器需要根据这个有效时间提前去刷新新 access_token。在刷新过程中，中控服务器对外输出的依然是老 access_token，此时公众平台后台会保证在刷新短时间内，新老 access_token 都可用，这保证了第三方业务的平滑过渡；
3.  access_token 的有效时间可能会在未来有调整，所以中控服务器不仅需要内部定时主动刷新，还需要提供被动刷新 access_token 的接口，这样便于业务服务器在 API 调用获知 access_token 已超时的情况下，可以触发 access_token 的刷新流程。

开发者可以使用 AppID 和 AppSecret 调用本接口来获取 access_token。AppID 和 AppSecret 可登录微信公众平台官网-设置-开发设置中获得（需要已经绑定成为开发者，且帐号没有异常状态）。AppSecret 生成后请自行保存，因为在公众平台每次生成查看都会导致 AppSecret 被重置。注意调用所有微信接口时均需使用 https 协议。如果第三方不使用中控服务器，而是选择各个业务逻辑点各自去刷新 access_token，那么就可能会产生冲突，导致服务不稳定。

**接口地址：**

    https://api.weixin.qq.com/cgi-bin/token?grant_type=client_credential&appid=APPID&secret=APPSECRET

**HTTP请求方式:**

    GET

**参数说明 :**

<table>

<thead>

<tr>

<th>参数</th>

<th>必填</th>

<th>说明</th>

</tr>

</thead>

<tbody>

<tr>

<td>grant_type</td>

<td>是</td>

<td>获取 access_token 填写 client_credential</td>

</tr>

<tr>

<td>appid</td>

<td>是</td>

<td>第三方用户唯一凭证</td>

</tr>

<tr>

<td>secret</td>

<td>是</td>

<td>第三方用户唯一凭证密钥，即appsecret</td>

</tr>

</tbody>

</table>

**返回参数说明：**

正常情况下，微信会返回下述 JSON 数据包给开发者：

    {"access_token": "ACCESS_TOKEN", "expires_in": 7200}

<table>

<thead>

<tr>

<th>参数</th>

<th>说明</th>

</tr>

</thead>

<tbody>

<tr>

<td>access_token</td>

<td>获取到的凭证</td>

</tr>

<tr>

<td>expires_in</td>

<td>凭证有效时间，单位：秒</td>

</tr>

</tbody>

</table>

错误时微信会返回错误码等信息，JSON 数据包示例如下（该示例为 AppID 无效错误）:

    {"errcode": 40013, "errmsg": "invalid appid"}

### 2\. 发送模板消息

**接口地址：(ACCESS_TOKEN 需换成上文获取到的 access_token)**

    https://api.weixin.qq.com/cgi-bin/message/wxopen/template/send?access_token=ACCESS_TOKEN

**HTTP请求方式：**

    POST

**POST参数说明：**

<table>

<thead>

<tr>

<th>参数</th>

<th>必填</th>

<th>说明</th>

</tr>

</thead>

<tbody>

<tr>

<td>touser</td>

<td>是</td>

<td>接收者（用户）的 openid</td>

</tr>

<tr>

<td>template_id</td>

<td>是</td>

<td>所需下发的模板消息的id</td>

</tr>

<tr>

<td>page</td>

<td>否</td>

<td>点击模板卡片后的跳转页面，仅限本小程序内的页面。支持带参数,（示例index?foo=bar）。该字段不填则模板无跳转。</td>

</tr>

<tr>

<td>form_id</td>

<td>是</td>

<td>表单提交场景下，为 submit 事件带上的 [formId](../component/form.html)；支付场景下，为本次支付的 [prepay_id](api-pay.html)</td>

</tr>

<tr>

<td>data</td>

<td>是</td>

<td>模板内容，不填则下发空模板</td>

</tr>

<tr>

<td>color</td>

<td>否</td>

<td>模板内容字体的颜色，不填默认黑色</td>

</tr>

<tr>

<td>emphasis_keyword</td>

<td>否</td>

<td>模板需要放大的关键词，不填则默认无放大</td>

</tr>

</tbody>

</table>

##### 示例：

    {
      "touser": "OPENID",  
      "template_id": "TEMPLATE_ID", 
      "page": "index",          
      "form_id": "FORMID",         
      "data": {
          "keyword1": {
              "value": "339208499", 
              "color": "#173177"
          }, 
          "keyword2": {
              "value": "2015年01月05日 12:30", 
              "color": "#173177"
          }, 
          "keyword3": {
              "value": "粤海喜来登酒店", 
              "color": "#173177"
          } , 
          "keyword4": {
              "value": "广州市天河区天河路208号", 
              "color": "#173177"
          } 
      },
      "emphasis_keyword": "keyword1.DATA" 
    }

**返回码说明：**

在调用模板消息接口后，会返回JSON数据包。

正常时的返回JSON数据包示例：

    {
      "errcode": 0,
      "errmsg": "ok",
    }

错误时会返回错误码信息，说明如下：

<table>

<thead>

<tr>

<th>返回码</th>

<th>说明</th>

</tr>

</thead>

<tbody>

<tr>

<td>40037</td>

<td>template_id不正确</td>

</tr>

<tr>

<td>41028</td>

<td>form_id不正确，或者过期</td>

</tr>

<tr>

<td>41029</td>

<td>form_id已被使用</td>

</tr>

<tr>

<td>41030</td>

<td>page不正确</td>

</tr>

<tr>

<td>45009</td>

<td>接口调用超过限额（目前默认每个帐号日调用限额为100万）</td>

</tr>

</tbody>

</table>

**使用效果：**

![](https://mp.weixin.qq.com/debug/wxadoc/dev/image/notice.png?t=2017616)

### 下发条件说明

1.  支付

    当用户在小程序内完成过支付行为，可允许开发者向用户在7天内推送有限条数的模板消息（1次支付可下发3条，多次支付下发条数独立，互相不影响）

2.  提交表单

    当用户在小程序内发生过提交[表单](../component/form.html)行为且该表单声明为要发模板消息的，开发者需要向用户提供服务时，可允许开发者向用户在7天内推送有限条数的模板消息（1次提交表单可下发1条，多次提交下发条数独立，相互不影响）

## 审核说明

### 1.标题

1.1标题不能存在相同

1.2标题意思不能存在过度相似

1.3标题必须以“提醒”或“通知”结尾

1.4标题不能带特殊符号、个性化字词等没有行业通用性的内容

1.5标题必须能体现具体服务场景

1.6标题不能涉及营销相关内容，包括不限于：

消费优惠类、购物返利类、商品更新类、优惠券类、代金券类、红包类、会员卡类、积分类、活动类等营销倾向通知

### 2.关键词

2.1同一标题下，关键词不能存在相同

2.2同一标题下，关键词不能存在过度相似

2.3关键词不能带特殊符号、个性化字词等没有行业通用性的内容

2.4关键词内容示例必须与关键词对应匹配

2.5关键词不能太过宽泛，需要具有限制性，例如：“内容”这个就太宽泛，不能审核通过

## 违规说明

除不能违反运营规范外，还不能违反以下规则，包括但不限于：

1.  不允许恶意诱导用户进行触发操作，以达到可向用户下发模板目的
2.  不允许恶意骚扰，下发对用户造成骚扰的模板
3.  不允许恶意营销，下发营销目的模板
4.  不允许通过服务号下发模板来告知用户在小程序内触发的服务相关内容

## 处罚说明

根据违规情况给予相应梯度的处罚，一般处罚规则如下：

第一次违规，删除违规模板以示警告，

第二次违规，封禁接口7天，

第三次违规，封禁接口30天，

第四次违规，永久封禁接口

处罚结果及原因以站内信形式告知

### Bug & Tip

1.  `tip`: 微信6.5.2及以上版本支持模板功能。低于该版本将无法收到模板消息。

</section>

</div>

<div class="search-results">

<div class="has-results">

# <span class="search-results-count"></span>个结果 "<span class="search-query"></span>"

</div>

<div class="no-results">

# 没有找到相关内容 "<span class="search-query"></span>"

</div>

</div>

</div>

</div>

</div>

<div class="foot" id="footer">

*   [关于腾讯](http://www.tencent.com/zh-cn/index.shtml)
*   [文档中心](https://mp.weixin.qq.com/debug/wxadoc/introduction/index.html?t=1484641676&t=2017616)
*   [辟谣中心](https://mp.weixin.qq.com/cgi-bin/opshowpage?action=dispelinfo&lang=zh_CN&begin=1&count=9)
*   [客服中心](http://kf.qq.com/faq/120911VrYVrA1509086vyumm.html)
*   [联系邮箱](mailto:weixinmp@qq.com)
*   Copyright © 2012-<span id="s_copyright_year"></span> Tencent. All Rights Reserved.

</div>

</div>

[](api-pay.html#wxrequestpaymentobject)[](notice.html#使用说明)</div>

</div>