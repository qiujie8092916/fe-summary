# fe-summary
* ## 工程化
    * ### 模块化
        * js模块化：es-module、babel、webpack
        * css模块化：css-in-js(styled-components)、css-modules(material-ui)
        * 资源模块化：webpack、loader
        * 框架模块化：
            * 抽象基类：BaseEnv、BaseModel、BaseStorage、BasePage、BaseI18n
            * Bridge：
                * 实现：h5-in-native、h5-in-unity、react-native-in-native
                * 方法：
                    * location、openWebview、openNativePage、publicJump、getAppVersion、share、getSignalBarHeight、setSignalBarBackgroundColor、callPhone、getUId、getRequestHeader、banIOSBounces、openNativeAlbum、openNativeContacts、getAppLang，etc...
                    * pageWillAppear、pageDidAppear、pageWillDisappear、pageDidDisappear、backButtonPressed、appEnterBackground、appEnterForeground，etc...
            * 工具类：
              * UtilDevice：isInApp、isInUnity、isIOS、isAndroid、isInWechat、isInAlipay，etc...
              * UtilExt：isArray、isEmpty、isJSONString、clone、cloneDeep、format、throttle、debounce，etc...
              * UtilSubscribes
              * UtilUser
    * ### 组件化
        * npm
        ```
        |-framework
        |   |-web-framework
        |   |-web-ui
        |   |-rn-framework
        |   |-rn-ui
        |   |-miniapp-framework
        |   |-miniapp-ui
        ```
        * Implement：Page、Model、Storage，etc...
        * Enhance：LifeCycle、Ubt、I18n、UrlQuery、Login、Share、Pay
    * ### 规范化
        * lint
        * prettier
        * lint-staged
    * ### 自动化
        
