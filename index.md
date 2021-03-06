<!DOCTYPE html>
<html lang="en">

<head>
  <meta http-equiv="X-UA-Compatible" content="IE=Edge" />

  <meta charset="utf-8" />
  <link rel="shortcut icon" href="https://static.parastorage.com/client/pfavico.ico" type="image/x-icon" />
  <link rel="apple-touch-icon" href="https://static.parastorage.com/client/pfavico.ico" type="image/x-icon" />

  <meta name="format-detection" content="telephone=no" />

  <meta name="SKYPE_TOOLBAR" content="SKYPE_TOOLBAR_PARSER_COMPATIBLE" />

  <!-- META DATA -->
  <script type="text/javascript">
    var googleAnalytics = "";
    var ipAnonymization = false;

    var googleRemarketing = "";
    var googleTagManager = "";
    var facebookRemarketing = "";
    var yandexMetrika = "";
  </script>


  <script>
    var wixBiSession = {
      initialTimestamp: Date.now(),
      ssrRequestTimestamp: 1572971871296,
      requestId: publicModel.requestId,
      viewerSessionId: 'xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx'.replace(/[xy]/g, function (c) {
        var r = Math.random() * 16 | 0,
          v = c == 'x' ? r : (r & 0x3 | 0x8);
        return v.toString(16);
      }),
      sessionId: 'e6dc90ba-bde3-41bd-96d6-206f77adaa20',
      initialRequestTimestamp: performance.timeOrigin ? performance.timeOrigin : Date.now() - performance.now(),
      visitorId: publicModel.sessionInfo.visitorId,
      is_rollout: 0,
      is_platform_loaded: 1,
      suppressbi: false,
      dc: '96',
      renderType: 'bolt',
      siteRevision: '129',
      siteCacheRevision: '1572919281366',
      wixBoltExclusionReason: '',
      wixBoltExclusionReasonMoreInfo: '',
      checkVisibility: (function () {
        var alwaysVisible = document.hidden !== true;

        function checkVisibility() {
          alwaysVisible = alwaysVisible && document.hidden !== true;
          return alwaysVisible;
        }
        document.addEventListener('visibilitychange', checkVisibility, false);
        return checkVisibility;
      })(),
      sendBeacon: function (url) {
        if (!wixBiSession.suppressbi) {

          var sent = false;
          try {
            sent = navigator.sendBeacon(url);
          } catch (e) {}
          if (!sent) {
            (new Image()).src = url;
          }

        }
      },
    };

    (function () {
      var microPop, caching = 'none';
      var match = document.cookie.match(
        /ssr-caching="cache,\s*desc=(\w+)(?:,\s*varnish=(\w+))?(?:,\s*dc,\s*desc=(\w+))?(?:"|;|$)/);
      if (!match && window.PerformanceServerTiming) {
        match = [];
        var serverTiming = performance.getEntriesByType('navigation')[0].serverTiming;
        serverTiming.forEach(function (st) {
          switch (st.name) {
            case 'cache':
              match[1] = st.description;
              break;
            case 'varnish':
              match[2] = st.description;
              break;
            case 'dc':
              microPop = st.description;
          }
        });
      }
      if (match && match.length) {
        caching = match[1] + ',' + (match[2] || 'none');
        if (!microPop) {
          microPop = match[3];
        }
      }
      wixBiSession.caching = caching;
      wixBiSession.isCached = caching.indexOf("hit") === 0;
      if (microPop) {
        wixBiSession.microPop = microPop;
      }
    })();
  </script>

  <script type="text/javascript">
    (function (x, e, o, s, n) {
      var a = window.fedops || {};
      a.apps = a.apps || {};
      a.apps[x] = {
        startLoadTime: e && e.now && e.now()
      };
      try {
        a.sessionId = o.getItem("fedops.logger.sessionId")
      } catch (x) {}
      a.sessionId = a.sessionId || wixBiSession.viewerSessionId;
      window.fedops = a;
<!--      var d = "//frog.wix.com/bolt-performance?appName=" + x + "&src=72&evid=21" + '&dc=96' + "&is_rollout=" +
        wixBiSession.is_rollout + "&is_cached=" + wixBiSession.isCached + "&session_id=" + a.sessionId + "&_=" + s();
-->
        wixBiSession.sendBeacon(d)
    })('bolt-viewer', window.performance, window.localStorage, Math.random, window.navigator);
  </script>

  <script>
    var requirejs = {
      onNodeCreated: function (node) {
        var src = node.getAttribute('src');
        var shouldIgnore = ['googletagmanager.com', 'google-analytics.com', 'googleadservices.com',
          'doubleclick.net', 'connect.facebook.net'
        ].some(function (domain) {
          return src.indexOf(domain) !== -1;
        });
        if (!shouldIgnore) {
          node.setAttribute('crossorigin', 'anonymous')
        }
      }
    }
  </script>

  <script>
    window.messageBuffer = [];
    window.messageHandler = function (event) {
      messageBuffer.push(event)
    };
    window.addEventListener('message', window.messageHandler, false);
  </script>

  <script type="text/javascript" src="viewerMainStyle.js"></script>
  <script type="text/javascript" src="fonts.js"></script>

<!--  <link rel="prefetch" href="/_partials/wix-bolt/1.4089.0/node_modules/viewer-platform-worker/dist/bolt-worker.js">
  <link rel="preconnect" href="https://siteassets.parastorage.com/pages/singlePage/viewerViewModeJson" crossorigin>
-->

  <title>Director of Software Engineering | Alan Darryl Martin | Portland, Ore</title>

  <meta name="description"
    content="Darryl Martin, experienced director of software engineering, leading web and data processing engineers for 14 years. Passion for solving tough problems, improving processes, expanding technology options, and coordinating people and teams." />

  <link rel="canonical" href="https://www.darrylmartin.com" />

  <meta property="og:title" content="Director of Software Engineering | Alan Darryl Martin | Portland, Ore" />

  <meta property="og:description"
    content="Darryl Martin, experienced director of software engineering, leading web and data processing engineers for 14 years. Passion for solving tough problems, improving processes, expanding technology options, and coordinating people and teams." />

  <meta property="og:url" content="https://www.darrylmartin.com" />

  <meta property="og:site_name" content="Alan Darryl Martin" />

  <meta property="og:type" content="website" />

  <meta name="keywords" content="Portfolio, Director, resume" />

  <meta name="google-site-verification" content="7_OmcLepT_U5ZVx0xqF7WriD5s2kEkwnz7YBuoVsLnA" />

</head>


<body class="prewarmup">

  <script type="text/javascript">
    var htmlClassList = document.documentElement.classList;

    var clientSideRender = false;
  </script>

  <!--body start html embeds start-->

  <!--body start html embeds end-->

  <div id="SITE_CONTAINER">
    <style type="text/css" data-styleid="uploadedFonts"></style>
    <div>
      <style type="text/css" data-styleid="theme_fonts">
        .font_0 {
          font: normal normal normal 22px/1.41em ebrima, sans-serif;
          color: #000000;
        }

        .font_1 {
          font: normal normal normal 14px/1.79em avenir-lt-w01_35-light1475496, sans-serif;
          color: #000000;
        }

        .font_2 {
          font: normal normal normal 28px/1.375em ebrima, sans-serif;
          color: #000000;
        }

        .font_3 {
          font: normal normal normal 88px/1.2em ebrima, sans-serif;
          color: #000000;
        }

        .font_4 {
          font: normal normal normal 72px/1.25em ebrima, sans-serif;
          color: #000000;
        }

        .font_5 {
          font: normal normal normal 50px/1.34em ebrima, sans-serif;
          color: #000000;
        }

        .font_6 {
          font: normal normal normal 40px/1.35em ebrima, sans-serif;
          color: #000000;
        }

        .font_7 {
          font: normal normal normal 20px/1.67em avenir-lt-w01_35-light1475496, sans-serif;
          color: #000000;
        }

        .font_8 {
          font: normal normal normal 18px/1.75em avenir-lt-w01_35-light1475496, sans-serif;
          color: #000000;
        }

        .font_9 {
          font: normal normal normal 15px/1.875em avenir-lt-w01_35-light1475496, sans-serif;
          color: #000000;
        }

        .font_10 {
          font: normal normal normal 14px/1.79em avenir-lt-w01_35-light1475496, sans-serif;
          color: #000000;
        }
      </style>
      <style type="text/css" data-styleid="theme_colors">
        .color_0 {
          color: #FFFFFF;
        }

        .backcolor_0 {
          background-color: #FFFFFF;
        }

        .color_1 {
          color: #000000;
        }

        .backcolor_1 {
          background-color: #000000;
        }

        .color_2 {
          color: #E3D0A8;
        }

        .backcolor_2 {
          background-color: #E3D0A8;
        }

        .color_3 {
          color: #191919;
        }

        .backcolor_3 {
          background-color: #191919;
        }

        .color_4 {
          color: #F7F7F7;
        }

        .backcolor_4 {
          background-color: #F7F7F7;
        }

        .color_5 {
          color: #E3F2F3;
        }

        .backcolor_5 {
          background-color: #E3F2F3;
        }

        .color_6 {
          color: #FFFFFF;
        }

        .backcolor_6 {
          background-color: #FFFFFF;
        }

        .color_7 {
          color: #BFBFBF;
        }

        .backcolor_7 {
          background-color: #BFBFBF;
        }

        .color_8 {
          color: #808080;
        }

        .backcolor_8 {
          background-color: #808080;
        }

        .color_9 {
          color: #404040;
        }

        .backcolor_9 {
          background-color: #404040;
        }

        .color_10 {
          color: #000000;
        }

        .backcolor_10 {
          background-color: #000000;
        }

        .color_11 {
          color: #FFFFFF;
        }

        .backcolor_11 {
          background-color: #FFFFFF;
        }

        .color_12 {
          color: #BFBFBF;
        }

        .backcolor_12 {
          background-color: #BFBFBF;
        }

        .color_13 {
          color: #808080;
        }

        .backcolor_13 {
          background-color: #808080;
        }

        .color_14 {
          color: #404040;
        }

        .backcolor_14 {
          background-color: #404040;
        }

        .color_15 {
          color: #000000;
        }

        .backcolor_15 {
          background-color: #000000;
        }

        .color_16 {
          color: #FDFCFA;
        }

        .backcolor_16 {
          background-color: #FDFCFA;
        }

        .color_17 {
          color: #F4ECDD;
        }

        .backcolor_17 {
          background-color: #F4ECDD;
        }

        .color_18 {
          color: #E3D0A8;
        }

        .backcolor_18 {
          background-color: #E3D0A8;
        }

        .color_19 {
          color: #CBA75C;
        }

        .backcolor_19 {
          background-color: #CBA75C;
        }

        .color_20 {
          color: #7B6028;
        }

        .backcolor_20 {
          background-color: #7B6028;
        }

        .color_21 {
          color: #C3C3C3;
        }

        .backcolor_21 {
          background-color: #C3C3C3;
        }

        .color_22 {
          color: #8E8E8E;
        }

        .backcolor_22 {
          background-color: #8E8E8E;
        }

        .color_23 {
          color: #606060;
        }

        .backcolor_23 {
          background-color: #606060;
        }

        .color_24 {
          color: #393939;
        }

        .backcolor_24 {
          background-color: #393939;
        }

        .color_25 {
          color: #191919;
        }

        .backcolor_25 {
          background-color: #191919;
        }

        .color_26 {
          color: #FFFFFF;
        }

        .backcolor_26 {
          background-color: #FFFFFF;
        }

        .color_27 {
          color: #F7F7F7;
        }

        .backcolor_27 {
          background-color: #F7F7F7;
        }

        .color_28 {
          color: #D6D6D6;
        }

        .backcolor_28 {
          background-color: #D6D6D6;
        }

        .color_29 {
          color: #A2A2A2;
        }

        .backcolor_29 {
          background-color: #A2A2A2;
        }

        .color_30 {
          color: #5B5B5B;
        }

        .backcolor_30 {
          background-color: #5B5B5B;
        }

        .color_31 {
          color: #FCFEFE;
        }

        .backcolor_31 {
          background-color: #FCFEFE;
        }

        .color_32 {
          color: #E3F2F3;
        }

        .backcolor_32 {
          background-color: #E3F2F3;
        }

        .color_33 {
          color: #B3DCDE;
        }

        .backcolor_33 {
          background-color: #B3DCDE;
        }

        .color_34 {
          color: #6CBBC0;
        }

        .backcolor_34 {
          background-color: #6CBBC0;
        }

        .color_35 {
          color: #327074;
        }

        .backcolor_35 {
          background-color: #327074;
        }
      </style>
    </div>
    <div data-aid="stylesContainer">
      <style type="text/css" data-styleid="pc1">
        .pc1screenWidthBackground {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }

        .pc1[data-state~="fixedPosition"] {
          position: fixed !important;
          left: auto !important;
          z-index: 50;
        }

        .pc1[data-state~="fixedPosition"].pc1_footer {
          top: auto;
          bottom: 0;
        }

        .pc1bg {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }

        .pc1inlineContent {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }

        .pc1centeredContent {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }
      </style>
      <style type="text/css" data-styleid="siteBackground">
        .siteBackground {
          width: 100%;
          position: absolute;
        }

        .siteBackgroundbgBeforeTransition {
          position: absolute;
          top: 0;
        }

        .siteBackgroundbgAfterTransition {
          position: absolute;
          top: 0;
        }
      </style>
      <style type="text/css" data-styleid="fc1">
        .fc1screenWidthBackground {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }

        .fc1[data-state~="fixedPosition"] {
          position: fixed !important;
          left: auto !important;
          z-index: 50;
        }

        .fc1[data-state~="fixedPosition"].fc1_footer {
          top: auto;
          bottom: 0;
        }

        .fc1_bg {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
          background-color: rgba(255, 255, 255, 1);
          border-top: 1px solid rgba(255, 255, 255, 0.15);
          border-bottom: 0px solid rgba(255, 255, 255, 0.15);
        }

        .fc1bg {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }

        .fc1[data-state~="mobileView"] .fc1bg {
          left: 10px;
          right: 10px;
        }

        .fc1_bg-center {
          position: absolute;
          top: 1px;
          right: 0;
          bottom: 0px;
          left: 0;
          background-color: rgba(255, 255, 255, 1);
          border-radius: 0;
        }

        .fc1inlineContent {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }

        .fc1centeredContent {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }
      </style>
      <style type="text/css" data-styleid="hc1">
        .hc1screenWidthBackground {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }

        .hc1[data-state~="fixedPosition"] {
          position: fixed !important;
          left: auto !important;
          z-index: 50;
        }

        .hc1[data-state~="fixedPosition"].hc1_footer {
          top: auto;
          bottom: 0;
        }

        .hc1_bg {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
          background-color: rgba(255, 255, 255, 1);
          border-top: 0px solid transparent;
          border-bottom: 0px solid transparent;
        }

        .hc1bg {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }

        .hc1[data-state~="mobileView"] .hc1bg {
          left: 10px;
          right: 10px;
        }

        .hc1_bg-center {
          position: absolute;
          top: 0px;
          right: 0;
          bottom: 0px;
          left: 0;
          background-color: rgba(255, 255, 255, 1);
          border-radius: 0;
        }

        .hc1inlineContent {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }

        .hc1centeredContent {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }
      </style>
      <style type="text/css" data-styleid="txtNew">
        .txtNew {
          word-wrap: break-word;
          text-align: start;
        }

        .txtNew_override-left * {
          text-align: left !important;
        }

        .txtNew_override-right * {
          text-align: right !important;
        }

        .txtNew_override-center * {
          text-align: center !important;
        }

        .txtNew_override-justify * {
          text-align: justify !important;
        }

        .txtNew>* {
          pointer-events: auto;
        }

        .txtNew li {
          font-style: inherit;
          font-weight: inherit;
          line-height: inherit;
          letter-spacing: normal;
        }

        .txtNew ol,
        .txtNew ul {
          padding-left: 1.3em;
          padding-right: 0;
          margin-left: 0.5em;
          margin-right: 0;
          line-height: normal;
          letter-spacing: normal;
        }

        .txtNew ul {
          list-style-type: disc;
        }

        .txtNew ol {
          list-style-type: decimal;
        }

        .txtNew ul ul,
        .txtNew ol ul {
          list-style-type: circle;
        }

        .txtNew ul ul ul,
        .txtNew ol ul ul {
          list-style-type: square;
        }

        .txtNew ul ol ul,
        .txtNew ol ol ul {
          list-style-type: square;
        }

        .txtNew ul[dir="rtl"],
        .txtNew ol[dir="rtl"] {
          padding-left: 0;
          padding-right: 1.3em;
          margin-left: 0;
          margin-right: 0.5em;
        }

        .txtNew ul[dir="rtl"] ul,
        .txtNew ul[dir="rtl"] ol,
        .txtNew ol[dir="rtl"] ul,
        .txtNew ol[dir="rtl"] ol {
          padding-left: 0;
          padding-right: 1.3em;
          margin-left: 0;
          margin-right: 0.5em;
        }

        .txtNew p {
          margin: 0;
          line-height: normal;
          letter-spacing: normal;
        }

        .txtNew h1 {
          margin: 0;
          line-height: normal;
          letter-spacing: normal;
        }

        .txtNew h2 {
          margin: 0;
          line-height: normal;
          letter-spacing: normal;
        }

        .txtNew h3 {
          margin: 0;
          line-height: normal;
          letter-spacing: normal;
        }

        .txtNew h4 {
          margin: 0;
          line-height: normal;
          letter-spacing: normal;
        }

        .txtNew h5 {
          margin: 0;
          line-height: normal;
          letter-spacing: normal;
        }

        .txtNew h6 {
          margin: 0;
          line-height: normal;
          letter-spacing: normal;
        }

        .txtNew a {
          color: inherit;
        }
      </style>
      <style type="text/css" data-styleid="strc1">
        .strc1:not([data-mobile-responsive])>.strc1inlineContent {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }

        .strc1[data-mobile-responsive]>.strc1inlineContent {
          position: relative;
        }

        .strc1[data-responsive] {
          display: -ms-grid;
          display: grid;
          justify-content: center;
          grid-template-columns: 100%;
          grid-template-rows: 1fr;
          -ms-grid-columns: 100%;
          -ms-grid-rows: 1fr;
        }

        .strc1[data-responsive]>.strc1inlineContent {
          display: flex;
        }

        .strc1[data-responsive]>* {
          position: relative;
          grid-row-start: 1;
          grid-column-start: 1;
          grid-row-end: 2;
          grid-column-end: 2;
          -ms-grid-row-span: 1;
          -ms-grid-column-span: 1;
          margin: 0 auto;
        }
      </style>
      <style type="text/css" data-styleid="style-k0sb3z6u">
        .style-k0sb3z6u:not([data-mobile-responsive]) .style-k0sb3z6uinlineContent,
        .style-k0sb3z6u:not([data-mobile-responsive]) .style-k0sb3z6ucontainer {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }
      </style>
      <style type="text/css" data-styleid="style-k0sb3z7a">
        .style-k0sb3z7awrapper {
          min-width: 180px;
          max-width: 980px;
          position: relative;
          width: 100%;
          text-align: center;
        }

        .style-k0sb3z7a_hiddenField {
          display: none !important;
        }

        .style-k0sb3z7a_first-row-wrapper {
          display: -webkit-box;
          display: -webkit-flex;
          display: flex;
        }

        .style-k0sb3z7a_first-row-wrapper input {
          -webkit-box-flex: 1;
          -webkit-flex: 1;
          flex: 1;
          min-width: 0;
        }

        .style-k0sb3z7a_first-row-wrapper input:first-child {
          margin-right: 30px;
        }

        .style-k0sb3z7a input,
        .style-k0sb3z7a textarea {
          padding: 5px;
          border: none;
          border-bottom: 1px solid rgba(0, 0, 0, 1);
          color: #000000;
          margin: 0 0 5px;
          width: 100%;
          -webkit-transition: 0.5s ease all;
          transition: 0.5s ease all;
          background-color: transparent;
          -webkit-appearance: none;
          -moz-appearance: none;
          font: normal normal normal 15px/1.875em avenir-lt-w01_35-light1475496, sans-serif;
          -webkit-appearance: none;
          border-radius: 0;
        }

        .style-k0sb3z7a input:focus,
        .style-k0sb3z7a textarea:focus {
          outline: none;
          border-color: rgba(227, 208, 168, 1);
        }

        .style-k0sb3z7a input.style-k0sb3z7a_error,
        .style-k0sb3z7a textarea.style-k0sb3z7a_error {
          font: normal normal normal 15px/1.875em avenir-lt-w01_35-light1475496, sans-serif;
          color: #FF0000;
          border-bottom: 1px solid #FF0000;
        }

        .style-k0sb3z7a input.style-k0sb3z7a_error::-webkit-input-placeholder,
        .style-k0sb3z7a textarea.style-k0sb3z7a_error::-webkit-input-placeholder {
          color: #FF0000;
        }

        .style-k0sb3z7a input.style-k0sb3z7a_error::-ms-input-placeholder,
        .style-k0sb3z7a textarea.style-k0sb3z7a_error::-ms-input-placeholder {
          color: #FF0000;
        }

        .style-k0sb3z7a input.style-k0sb3z7a_error::placeholder,
        .style-k0sb3z7a textarea.style-k0sb3z7a_error::placeholder {
          color: #FF0000;
        }

        .style-k0sb3z7a input::-webkit-input-placeholder,
        .style-k0sb3z7a textarea::-webkit-input-placeholder {
          color: #000000;
        }

        .style-k0sb3z7a input::-ms-input-placeholder,
        .style-k0sb3z7a textarea::-ms-input-placeholder {
          color: #000000;
        }

        .style-k0sb3z7a input::placeholder,
        .style-k0sb3z7a textarea::placeholder {
          color: #000000;
        }

        .style-k0sb3z7a input {
          margin-bottom: 12px;
        }

        .style-k0sb3z7a textarea {
          resize: none;
          overflow: hidden;
          margin: 0 0 10px;
        }

        .style-k0sb3z7afieldMessage {
          min-height: 128px;
        }

        .style-k0sb3z7asubmit {
          color: #000000;
          font: normal normal normal 15px/1.875em avenir-lt-w01_35-light1475496, sans-serif;
        }

        .style-k0sb3z7asubmit:hover {
          cursor: pointer;
        }

        .style-k0sb3z7anotifications {
          font: normal 14px 'Helvetica Neue', Helvetica, sans-serif;
          margin-top: 20px;
          height: 14px;
        }

        .style-k0sb3z7anotifications.style-k0sb3z7a_success {
          color: #BADA55;
        }

        .style-k0sb3z7anotifications.style-k0sb3z7a_error {
          color: #FF0000;
        }

        .style-k0sb3z7a[data-state~="mobile"] input,
        .style-k0sb3z7a[data-state~="mobile"] textarea {
          font-size: 14px;
        }

        .style-k0sb3z7a[data-state~="mobile"] input::-webkit-input-placeholder,
        .style-k0sb3z7a[data-state~="mobile"] textarea::-webkit-input-placeholder {
          font-size: 14px;
        }

        .style-k0sb3z7a[data-state~="mobile"] input::-ms-input-placeholder,
        .style-k0sb3z7a[data-state~="mobile"] textarea::-ms-input-placeholder {
          font-size: 14px;
        }

        .style-k0sb3z7a[data-state~="mobile"] input::placeholder,
        .style-k0sb3z7a[data-state~="mobile"] textarea::placeholder {
          font-size: 14px;
        }

        .style-k0sb3z7a[data-state~="mobile"] input {
          min-height: 35px;
          line-height: 35px;
          margin-bottom: 12px;
        }

        .style-k0sb3z7a[data-state~="mobile"] textarea {
          min-height: 110px;
        }

        .style-k0sb3z7a[data-state~="right"] {
          direction: rtl;
          text-align: right;
        }

        .style-k0sb3z7a[data-state~="right"] input {
          -webkit-box-flex: 1;
          -webkit-flex: 1;
          flex: 1;
          min-width: 0;
        }

        .style-k0sb3z7a[data-state~="right"] input:first-child {
          margin-right: 0;
          margin-left: 30px;
        }

        .style-k0sb3z7a[data-state~="left"] {
          direction: ltr;
          text-align: left;
        }
      </style>
      <style type="text/css" data-styleid="style-k0sb3z5z">
        .style-k0sb3z5z:not([data-mobile-responsive]) .style-k0sb3z5zinlineContent,
        .style-k0sb3z5z:not([data-mobile-responsive]) .style-k0sb3z5zcontainer {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }
      </style>
      <style type="text/css" data-styleid="lb1">
        .lb1[data-is-responsive~="false"] .lb1itemsContainer {
          position: absolute;
          width: 100%;
          height: 100%;
          white-space: nowrap;
        }

        .lb1[data-is-responsive~="false"][data-state~="mobileView"] .lb1itemsContainer {
          position: absolute;
          width: 100%;
          height: 100%;
          white-space: normal;
        }

        .lb1[data-is-responsive~="true"] {
          display: table;
        }

        .lb1[data-is-responsive~="true"] .lb1itemsContainer {
          display: -webkit-box;
          display: -webkit-flex;
          display: flex;
        }

        .lb1itemsContainer>li:last-child {
          margin: 0 !important;
        }

        .lb1 a {
          display: block;
          height: 100%;
        }

        .lb1imageItemlink {
          cursor: pointer;
        }

        .lb1imageItemimageimage {
          position: static;
          box-shadow: #000 0 0 0;
          user-select: none;
        }
      </style>
      <style type="text/css" data-styleid="style-k0sb3z5r">
        .style-k0sb3z5ritemsContainer {
          width: calc(100% - 0px);
          height: calc(100% - 0px);
          white-space: nowrap;
          display: inline-block;
          overflow: visible;
          position: absolute;
        }

        .style-k0sb3z5rmoreContainer {
          overflow: visible;
          display: inherit;
          white-space: nowrap;
          width: auto;
          background-color: rgba(255, 255, 255, 1);
          border-radius: 0;
        }

        .style-k0sb3z5rdropWrapper {
          z-index: 99999;
          display: block;
          opacity: 1;
          visibility: visible;
          position: absolute;
          margin-top: 7px;
        }

        .style-k0sb3z5r>nav {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }

        .style-k0sb3z5rdropWrapper[data-dropMode="dropUp"] {
          margin-top: 0;
          margin-bottom: 7px;
        }

        .style-k0sb3z5rrepeaterButton {
          height: 100%;
          position: relative;
          box-sizing: border-box;
          display: inline-block;
          cursor: pointer;
          font: normal normal normal 14px/1.79em avenir-lt-w01_35-light1475496, sans-serif;
        }

        .style-k0sb3z5rrepeaterButton[data-state~="header"] a,
        .style-k0sb3z5rrepeaterButton[data-state~="header"] div {
          cursor: default !important;
        }

        .style-k0sb3z5rrepeaterButtonlinkElement {
          display: inline-block;
          height: 100%;
          width: 100%;
        }

        .style-k0sb3z5rrepeaterButton_gapper {
          padding: 0 0px;
        }

        .style-k0sb3z5rrepeaterButtonlabel {
          display: inline-block;
          padding: 0 10px;
          color: #000000;
          transition: color 0.4s ease 0s;
        }

        .style-k0sb3z5rrepeaterButton[data-state~="drop"] {
          width: 100%;
          display: block;
        }

        .style-k0sb3z5rrepeaterButton[data-state~="drop"] .style-k0sb3z5rrepeaterButtonlabel {
          padding: 0 .5em;
        }

        .style-k0sb3z5rrepeaterButton[data-state~="over"] .style-k0sb3z5rrepeaterButtonlabel,
        .style-k0sb3z5rrepeaterButton[data-preview~="hover"] .style-k0sb3z5rrepeaterButtonlabel {
          color: #191919;
          transition: color 0.4s ease 0s;
        }

        .style-k0sb3z5rrepeaterButton[data-state~="selected"] .style-k0sb3z5rrepeaterButtonlabel,
        .style-k0sb3z5rrepeaterButton[data-preview~="active"] .style-k0sb3z5rrepeaterButtonlabel {
          color: #191919;
          transition: color 0.4s ease 0s;
        }
      </style>
      <style type="text/css" data-styleid="style-k0sb3z86">
        .style-k0sb3z86 button.style-k0sb3z86link {
          width: 100%;
        }

        .style-k0sb3z86[data-state~="shouldUseFlex"] .style-k0sb3z86link,
        .style-k0sb3z86[data-state~="shouldUseFlex"] .style-k0sb3z86labelwrapper {
          text-align: initial;
          display: flex;
          align-items: center;
        }

        .style-k0sb3z86[data-state~="shouldUseFlex"][data-state~="center"] .style-k0sb3z86link,
        .style-k0sb3z86[data-state~="shouldUseFlex"][data-state~="center"] .style-k0sb3z86labelwrapper {
          justify-content: center;
        }

        .style-k0sb3z86[data-state~="shouldUseFlex"][data-state~="left"] .style-k0sb3z86link,
        .style-k0sb3z86[data-state~="shouldUseFlex"][data-state~="left"] .style-k0sb3z86labelwrapper {
          justify-content: flex-start;
        }

        .style-k0sb3z86[data-state~="shouldUseFlex"][data-state~="right"] .style-k0sb3z86link,
        .style-k0sb3z86[data-state~="shouldUseFlex"][data-state~="right"] .style-k0sb3z86labelwrapper {
          justify-content: flex-end;
        }

        .style-k0sb3z86link {
          border-radius: 100px;
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
          transition: border-color 0.4s ease 0s, background-color 0.4s ease 0s;
        }

        .style-k0sb3z86label {
          font: normal normal normal 15px/1.875em avenir-lt-w01_35-light1475496, sans-serif;
          transition: color 0.4s ease 0s;
          color: #000000;
          display: inline-block;
          margin: calc(-1 * 1px) 1px 0;
          position: relative;
          white-space: nowrap;
        }

        .style-k0sb3z86[data-state~="shouldUseFlex"] .style-k0sb3z86label {
          margin: 0;
        }

        .style-k0sb3z86[data-disabled="false"] .style-k0sb3z86link {
          background-color: transparent;
          border: solid rgba(0, 0, 0, 1) 1px;
          cursor: pointer !important;
        }

        .style-k0sb3z86[data-disabled="false"]:active[data-state~="mobile"] .style-k0sb3z86link,
        .style-k0sb3z86[data-disabled="false"]:hover[data-state~="desktop"] .style-k0sb3z86link,
        .style-k0sb3z86[data-disabled="false"][data-preview~="hover"] .style-k0sb3z86link {
          background-color: rgba(0, 0, 0, 1);
          border-color: transparent;
        }

        .style-k0sb3z86[data-disabled="false"]:active[data-state~="mobile"] .style-k0sb3z86label,
        .style-k0sb3z86[data-disabled="false"]:hover[data-state~="desktop"] .style-k0sb3z86label,
        .style-k0sb3z86[data-disabled="false"][data-preview~="hover"] .style-k0sb3z86label {
          color: #E3F2F3;
        }

        .style-k0sb3z86[data-disabled="true"] .style-k0sb3z86link,
        .style-k0sb3z86[data-preview~="disabled"] .style-k0sb3z86link {
          background-color: rgba(204, 204, 204, 1);
          border-color: rgba(204, 204, 204, 1);
        }

        .style-k0sb3z86[data-disabled="true"] .style-k0sb3z86label,
        .style-k0sb3z86[data-preview~="disabled"] .style-k0sb3z86label {
          color: #FFFFFF;
        }
      </style>
      <style type="text/css" data-styleid="mc1">
        .mc1:not([data-mobile-responsive]) .mc1inlineContent,
        .mc1:not([data-mobile-responsive]) .mc1container {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }
      </style>
      <style type="text/css" data-styleid="style-k0sb3z94">
        .style-k0sb3z94 {
          box-sizing: border-box;
          border-top: 3px solid rgba(15, 15, 15, 1);
          height: 0;
        }
      </style>
      <style type="text/css" data-styleid="style-k0sb3z8k">
/*        .style-k0sb3z8k_zoomedin {
          cursor: url(https://static.parastorage.com/services/skins/2.1229.80/images/wysiwyg/core/themes/base/cursor_zoom_out.png), url(https://static.parastorage.com/services/skins/2.1229.80/images/wysiwyg/core/themes/base/cursor_zoom_out.cur), auto;
          overflow: hidden;
          display: block;
        }

        .style-k0sb3z8k_zoomedout {
          cursor: url(https://static.parastorage.com/services/skins/2.1229.80/images/wysiwyg/core/themes/base/cursor_zoom_in.png), url(https://static.parastorage.com/services/skins/2.1229.80/images/wysiwyg/core/themes/base/cursor_zoom_in.cur), auto;
        }
*/
        .style-k0sb3z8klink {
          display: block;
          border-radius: 50%;
          border: 0px solid rgba(255, 255, 255, 1);
          background-color: rgba(255, 255, 255, 1);
          overflow: hidden;
        }

        .style-k0sb3z8kimg {
          border-radius: 50%;
          overflow: hidden;
        }

        .style-k0sb3z8kimgimage {
          position: static;
          box-shadow: #000 0 0 0;
          user-select: none;
        }
      </style>
      <style type="text/css" data-styleid="style-k0wq1doe">
        .style-k0wq1doe {
          overflow: hidden;
        }

        .style-k0wq1doe iframe {
          position: absolute;
          width: 100%;
          height: 100%;
          overflow: hidden;
        }

        .style-k0wq1doe iframe:-webkit-full-screen {
          min-height: auto !important;
        }

        .style-k0wq1doepreloaderOverlay {
          position: absolute;
          top: 0;
          left: 0;
          color: #373737;
          width: 100%;
          height: 100%;
        }

        .style-k0wq1doepreloaderOverlaycontent {
          width: 100%;
          height: 100%;
        }

        .style-k0wq1doeunavailableMessageOverlay {
          position: absolute;
          top: 0;
          left: 0;
          color: #373737;
          width: 100%;
          height: 100%;
        }

        .style-k0wq1doeunavailableMessageOverlaycontent {
          width: 100%;
          height: 100%;
          background: rgba(255, 255, 255, 0.9);
          font-size: 0;
          margin-top: 5px;
        }

        .style-k0wq1doeunavailableMessageOverlaytextContainer {
          color: #373737;
          font-family: "Helvetica Neue", "HelveticaNeueW01-55Roma", "HelveticaNeueW02-55Roma", "HelveticaNeueW10-55Roma", Helvetica, Arial, sans-serif;
          font-size: 14px;
          display: inline-block;
          vertical-align: middle;
          width: 100%;
          margin-top: 10px;
          text-align: center;
        }

        .style-k0wq1doeunavailableMessageOverlayreloadButton {
          display: inline-block;
        }

        .style-k0wq1doeunavailableMessageOverlay a {
          color: #0099FF;
          text-decoration: underline;
          cursor: pointer;
        }

        .style-k0wq1doeunavailableMessageOverlayiconContainer {
          display: none;
        }

        .style-k0wq1doeunavailableMessageOverlaydismissButton {
          display: none;
        }

        .style-k0wq1doeunavailableMessageOverlaytextTitle {
          font-family: "Helvetica Neue", "HelveticaNeueW01-55Roma", "HelveticaNeueW02-55Roma", "HelveticaNeueW10-55Roma", Helvetica, Arial, sans-serif;
          display: none;
        }

        .style-k0wq1doeunavailableMessageOverlay[data-state~="hideIframe"] .style-k0wq1doeunavailableMessageOverlay_buttons {
          opacity: 1;
        }

        .style-k0wq1doeunavailableMessageOverlay[data-state~="hideOverlay"] {
          display: none;
        }
      </style>
      <style type="text/css" data-styleid="p2">
        .p2bg {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }

        .p2[data-state~="mobileView"] .p2bg {
          left: 10px;
          right: 10px;
        }

        .p2inlineContent {
          position: absolute;
          top: 0;
          right: 0;
          bottom: 0;
          left: 0;
        }
      </style>
      <style type="text/css" data-styleid="s_DtaksTPAWidgetSkin">
        .s_DtaksTPAWidgetSkin {
          overflow: hidden;
        }

        .s_DtaksTPAWidgetSkin iframe {
          position: absolute;
          width: 100%;
          height: 100%;
          overflow: hidden;
        }

        .s_DtaksTPAWidgetSkin iframe:-webkit-full-screen {
          min-height: auto !important;
        }

        .s_DtaksTPAWidgetSkinpreloaderOverlay {
          position: absolute;
          top: 0;
          left: 0;
          color: #373737;
          width: 100%;
          height: 100%;
        }

        .s_DtaksTPAWidgetSkinpreloaderOverlaycontent {
          width: 100%;
          height: 100%;
        }

        .s_DtaksTPAWidgetSkinunavailableMessageOverlay {
          position: absolute;
          top: 0;
          left: 0;
          color: #373737;
          width: 100%;
          height: 100%;
        }

        .s_DtaksTPAWidgetSkinunavailableMessageOverlaycontent {
          width: 100%;
          height: 100%;
          background: rgba(255, 255, 255, 0.9);
          font-size: 0;
          margin-top: 5px;
        }

        .s_DtaksTPAWidgetSkinunavailableMessageOverlaytextContainer {
          color: #373737;
          font-family: "Helvetica Neue", "HelveticaNeueW01-55Roma", "HelveticaNeueW02-55Roma", "HelveticaNeueW10-55Roma", Helvetica, Arial, sans-serif;
          font-size: 14px;
          display: inline-block;
          vertical-align: middle;
          width: 100%;
          margin-top: 10px;
          text-align: center;
        }

        .s_DtaksTPAWidgetSkinunavailableMessageOverlayreloadButton {
          display: inline-block;
        }

        .s_DtaksTPAWidgetSkinunavailableMessageOverlay a {
          color: #0099FF;
          text-decoration: underline;
          cursor: pointer;
        }

        .s_DtaksTPAWidgetSkinunavailableMessageOverlayiconContainer {
          display: none;
        }

        .s_DtaksTPAWidgetSkinunavailableMessageOverlaydismissButton {
          display: none;
        }

        .s_DtaksTPAWidgetSkinunavailableMessageOverlaytextTitle {
          font-family: "Helvetica Neue", "HelveticaNeueW01-55Roma", "HelveticaNeueW02-55Roma", "HelveticaNeueW10-55Roma", Helvetica, Arial, sans-serif;
          display: none;
        }

        .s_DtaksTPAWidgetSkinunavailableMessageOverlay[data-state~="hideIframe"] .s_DtaksTPAWidgetSkinunavailableMessageOverlay_buttons {
          opacity: 1;
        }

        .s_DtaksTPAWidgetSkinunavailableMessageOverlay[data-state~="hideOverlay"] {
          display: none;
        }
      </style>
    </div>
    <div class="noop visual-focus-on" style="position:relative">
      <div id="FONTS_CONTAINER"></div>
      <div id="CSS_CONTAINER"></div>
      <div id="SITE_BACKGROUND" style="height:100%;top:0;min-height:calc(100vh - 0px);bottom:;left:;right:;position:"
        class="siteBackground">
        <div id="SITE_BACKGROUND_previous_noPrev" data-position="absolute" data-align="" data-fitting=""
          class="siteBackgroundprevious">
          <div id="SITE_BACKGROUNDpreviousImage" class="siteBackgroundpreviousImage"></div>
          <div id="SITE_BACKGROUNDpreviousVideo" class="siteBackgroundpreviousVideo"></div>
          <div id="SITE_BACKGROUND_previousOverlay_noPrev" class="siteBackgroundpreviousOverlay"></div>
        </div>
        <div id="SITE_BACKGROUND_current_jqtbi_k0wqhpqw_bg"
          style="top:0;height:100%;width:100%;background-color:rgba(250, 250, 250, 1);display:;position:absolute"
          data-position="absolute" data-align="center" data-fitting="fill" class="siteBackgroundcurrent">
          <div id="SITE_BACKGROUND_currentImage_jqtbi_k0wqhpqw_bg"
            style="position:absolute;top:0;height:100%;width:100%" data-type="bgimage" data-height="100%"
            class="siteBackgroundcurrentImage"></div>
          <div id="SITE_BACKGROUNDcurrentVideo" class="siteBackgroundcurrentVideo"></div>
          <div id="SITE_BACKGROUND_currentOverlay_jqtbi_k0wqhpqw_bg"
            style="position:absolute;top:0;width:100%;height:100%" class="siteBackgroundcurrentOverlay"></div>
        </div>
      </div>
      <div id="SITE_ROOT" class="SITE_ROOT" style="width:100%;min-width:980px;padding-bottom:0;top:0"
        aria-hidden="false">
        <div id="masterPage" class="mesh-layout" data-mesh-layout="grid">
          <footer style="bottom:auto;left:0;margin-left:0;width:100%;min-width:980px;top:;right:;position:"
            class="fc1_footer fc1" tabindex="-1" data-site-width="980" data-fixedposition="false"
            data-isrunninginmobile="false" data-state=" " id="SITE_FOOTER">
            <div style="left:0;width:100%" id="SITE_FOOTERscreenWidthBackground" class="fc1screenWidthBackground">
              <div class="fc1_bg"></div>
            </div>
            <div style="width:100%" id="SITE_FOOTERcenteredContent" class="fc1centeredContent">
              <div style="margin-left:calc((100% - 980px) / 2);width:980px" id="SITE_FOOTERbg" class="fc1bg">
                <div class="fc1_bg-center"></div>
              </div>
              <div id="SITE_FOOTERinlineContent" class="fc1inlineContent">
                <style id="SITE_FOOTER-mesh-styles">
                  #SITE_FOOTERinlineContent {
                    height: auto;
                    width: 100%;
                    position: relative;
                  }

                  #SITE_FOOTERinlineContent-gridWrapper {
                    pointer-events: none;
                  }

                  #SITE_FOOTERinlineContent-gridContainer {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: 120px;
                    grid-template-rows: 1fr;
                    grid-template-columns: 100%;
                  }

                  #comp-jpkmjxg5 {
                    position: relative;
                    margin: 0px 0px 10px calc((100% - 980px) * 0.5);
                    left: 0px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start;
                  }

                  #SITE_FOOTERcenteredContent {
                    position: relative;
                  }

                  #SITE_FOOTERinlineContent-gridContainer>* {
                    pointer-events: auto;
                  }

                  #SITE_FOOTERinlineContent-gridContainer>[id$="-rotated-wrapper"] {
                    pointer-events: none;
                  }

                  #SITE_FOOTERinlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                    pointer-events: auto;
                  }
                </style>
                <div id="SITE_FOOTERinlineContent-gridWrapper" data-mesh-internal="true">
                  <div id="SITE_FOOTERinlineContent-gridContainer" data-mesh-internal="true">
                    <section
                      style="left:0;width:100%;min-width:980px;height:auto;top:;bottom:;right:;position:;margin-left:0"
                      data-responsive="true" data-is-screen-width="true" data-col-margin="0" data-row-margin="0"
                      class="strc1" id="comp-jpkmjxg5">
                      <div
                        style="position:absolute;top:0;width:calc(100% - 0px);height:100%;overflow:hidden;pointer-events:auto;min-width:980px;left:0;right:0;bottom:0"
                        data-page-id="masterPage" data-enable-video="true" data-bg-effect-name="" data-media-type=""
                        data-use-clip-path="" data-needs-clipping="" data-wix-video-layout="" class="strc1balata"
                        id="comp-jpkmjxg5balata">
                        <div style="position:absolute;width:100%;height:100%;top:0;background-color:transparent"
                          class="bgColor" id="comp-jpkmjxg5balatabgcolor">
                          <div style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                            id="comp-jpkmjxg5balatabgcoloroverlay" class="bgColoroverlay"></div>
                        </div>
                      </div>
                      <div style="position:relative;width:calc(100% - 0px);min-width:980px"
                        id="comp-jpkmjxg5inlineContent" class="strc1inlineContent">
                        <div
                          style="position:relative;width:100%;left:0;flex:980;margin-left:0;min-width:980px;top:0;margin-top:0;margin-bottom:0;height:;display:flex;bottom:;right:"
                          data-content-width="980" data-is-mesh="true" class="strc1" id="comp-jpkmjxg51">
                          <div
                            style="position:absolute;top:0;width:100%;height:100%;overflow:hidden;pointer-events:auto;left:0;right:0;bottom:0"
                            data-page-id="masterPage" data-enable-video="true" data-bg-effect-name="" data-media-type=""
                            data-use-clip-path="" data-needs-clipping="" data-wix-video-layout="" class="strc1balata"
                            id="comp-jpkmjxg51balata">
                            <div
                              style="position:absolute;width:100%;height:100%;top:0;background-color:rgba(250, 250, 250, 1)"
                              class="bgColor" id="comp-jpkmjxg51balatabgcolor">
                              <div style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                id="comp-jpkmjxg51balatabgcoloroverlay" class="bgColoroverlay"></div>
                            </div>
                          </div>
                          <div class="strc1inlineContent" style="width:100%;position:relative;top:0;bottom:0"
                            id="comp-jpkmjxg51inlineContent">
                            <style id="comp-jpkmjxg51-mesh-styles">
                              #comp-jpkmjxg51inlineContent {
                                height: auto;
                                width: 100%;
                                position: relative;
                              }

                              #comp-jpkmjxg51inlineContent-gridWrapper {
                                pointer-events: none;
                              }

                              #comp-jpkmjxg51inlineContent-gridContainer {
                                position: static;
                                display: grid;
                                height: auto;
                                width: 100%;
                                min-height: auto;
                                grid-template-rows: 1fr;
                                grid-template-columns: 100%;
                              }

                              #comp-jpkmhymi {
                                position: relative;
                                margin: 10px 0px 10px calc((100% - 980px) * 0.5);
                                left: 302px;
                                grid-area: 1 / 1 / 2 / 2;
                                justify-self: start;
                                align-self: start;
                              }

                              #comp-jpkmjxg51centeredContent {
                                position: relative;
                              }

                              #comp-jpkmjxg51inlineContent-gridContainer>* {
                                pointer-events: auto;
                              }

                              #comp-jpkmjxg51inlineContent-gridContainer>[id$="-rotated-wrapper"] {
                                pointer-events: none;
                              }

                              #comp-jpkmjxg51inlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                                pointer-events: auto;
                              }
                            </style>
                            <div id="comp-jpkmjxg51inlineContent-gridWrapper" data-mesh-internal="true">
                              <div id="comp-jpkmjxg51inlineContent-gridContainer" data-mesh-internal="true">
                                <div data-packed="false"
                                  style="top:;bottom:;left:;right:;width:376px;height:auto;position:;min-height:25px;pointer-events:none"
                                  data-min-height="25" class="txtNew" id="comp-jpkmhymi">
                                  <p class="font_10" style="line-height:1.79em; text-align:center;"><span
                                      class="color_15">&copy;2019&nbsp;by Darryl Martin</span></p>
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </section>
                  </div>
                </div>
              </div>
            </div>
          </footer>
          <main tabindex="-1" data-is-mobile="false" data-is-mesh="true" data-site-width="980"
            style="left:0;margin-left:0;width:100%;min-width:980px;top:0;bottom:;right:;position:" class="pc1"
            data-state="" id="PAGES_CONTAINER">
            <div style="left:0" id="PAGES_CONTAINERscreenWidthBackground" class="pc1screenWidthBackground"></div>
            <div style="position:relative" id="PAGES_CONTAINERcenteredContent" class="pc1centeredContent">
              <div style="display:none" id="PAGES_CONTAINERbg" class="pc1bg"></div>
              <div style="position:relative" id="PAGES_CONTAINERinlineContent" class="pc1inlineContent">
                <div style="width:100%">
                  <div data-ismobile="false" data-is-mesh-layout="true"
                    style="height:100%;left:0;position:relative;top:;bottom:;right:" class="p2" id="jqtbi">
                    <div style="margin-left:calc((100% - 980px) / 2);width:980px" id="jqtbibg" class="p2bg"></div>
                    <div class="p2inlineContent" id="jqtbiinlineContent">
                      <style id="jqtbi-mesh-styles">
                        #jqtbiinlineContent {
                          height: auto;
                          width: 100%;
                          position: relative;
                        }

                        #jqtbiinlineContent-gridWrapper {
                          display: flex;
                          pointer-events: none;
                        }

                        #jqtbiinlineContent-gridContainer {
                          position: static;
                          display: grid;
                          height: auto;
                          width: 100%;
                          min-height: 531px;
                          margin-top: -31px;
                          grid-template-rows: min-content min-content min-content min-content min-content 1fr;
                          grid-template-columns: 100%;
                          padding-bottom: 0px;
                          box-sizing: border-box;
                        }

                        #comp-jpkn0sgr {
                          position: relative;
                          margin: 0px 0px 1px calc((100% - 980px) * 0.5);
                          left: 0px;
                          grid-area: 1 / 1 / 2 / 2;
                          justify-self: start;
                          align-self: start;
                        }

                        #comp-jqg4qgor {
                          position: relative;
                          margin: 0px 0px 0 calc((100% - 980px) * 0.5);
                          left: 0px;
                          grid-area: 2 / 1 / 3 / 2;
                          justify-self: start;
                          align-self: start;
                        }

                        #comp-jpkqjpxi {
                          position: relative;
                          margin: 0px 0px 0 calc((100% - 980px) * 0.5);
                          left: 0px;
                          grid-area: 3 / 1 / 4 / 2;
                          justify-self: start;
                          align-self: start;
                        }

                        #comp-k0se0v2k {
                          position: relative;
                          margin: 0px 0px 0 calc((100% - 980px) * 0.5);
                          left: 0px;
                          grid-area: 4 / 1 / 5 / 2;
                          justify-self: start;
                          align-self: start;
                        }

                        #comp-jpkmjxgi {
                          position: relative;
                          margin: 0px 0px 0 calc((100% - 980px) * 0.5);
                          left: 0px;
                          grid-area: 5 / 1 / 6 / 2;
                          justify-self: start;
                          align-self: start;
                        }

                        #comp-jpkmjxgi8 {
                          position: relative;
                          margin: 0px 0px 0 calc((100% - 980px) * 0.5);
                          left: 0px;
                          grid-area: 6 / 1 / 7 / 2;
                          justify-self: start;
                          align-self: start;
                        }

                        #jqtbicenteredContent {
                          position: relative;
                        }

                        #jqtbiinlineContent-gridContainer>* {
                          pointer-events: auto;
                        }

                        #jqtbiinlineContent-gridContainer>[id$="-rotated-wrapper"] {
                          pointer-events: none;
                        }

                        #jqtbiinlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                          pointer-events: auto;
                        }
                      </style>
                      <div id="jqtbiinlineContent-gridWrapper" data-mesh-internal="true">
                        <div id="jqtbiinlineContent-gridContainer" data-mesh-internal="true">
                          <section
                            style="left:0;width:100%;min-width:980px;height:auto;top:;bottom:;right:;position:;margin-left:0"
                            data-responsive="true" data-is-screen-width="true" data-col-margin="0" data-row-margin="0"
                            class="strc1" id="comp-jpkn0sgr">
                            <div
                              style="position:absolute;top:0;width:calc(100% - 0px);height:100%;overflow:hidden;pointer-events:auto;min-width:980px;left:0;right:0;bottom:0"
                              data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name="" data-media-type=""
                              data-use-clip-path="" data-needs-clipping="" data-wix-video-layout="" class="strc1balata"
                              id="comp-jpkn0sgrbalata">
                              <div style="position:absolute;width:100%;height:100%;top:0;background-color:transparent"
                                class="bgColor" id="comp-jpkn0sgrbalatabgcolor">
                                <div style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                  id="comp-jpkn0sgrbalatabgcoloroverlay" class="bgColoroverlay"></div>
                              </div>
                            </div>
                            <div style="position:relative;width:calc(100% - 0px);min-width:980px"
                              id="comp-jpkn0sgrinlineContent" class="strc1inlineContent">
                              <div
                                style="position:relative;width:100%;left:0;flex:980;margin-left:0;min-width:980px;top:0;margin-top:0;margin-bottom:0;height:;display:flex;bottom:;right:"
                                data-content-width="980" data-is-mesh="true" class="strc1" id="comp-jpkn0sgs">
                                <div
                                  style="position:absolute;top:0;width:100%;height:100%;overflow:hidden;pointer-events:auto;left:0;right:0;bottom:0"
                                  data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name=""
                                  data-media-type="Image" data-use-clip-path="" data-needs-clipping=""
                                  data-wix-video-layout="" class="strc1balata" id="comp-jpkn0sgsbalata">
                                  <div
                                    style="position:absolute;width:100%;height:100%;top:0;background-color:rgba(0, 0, 0, 1)"
                                    class="bgColor" id="comp-jpkn0sgsbalatabgcolor">
                                    <div
                                      style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                      id="comp-jpkn0sgsbalatabgcoloroverlay" class="bgColoroverlay"></div>
                                  </div>
                                  <div style="position:absolute;pointer-events:auto;width:100%;height:100%;top:0;left:0"
                                    data-has-bg-effect="" data-fitting="fill" data-align="center"
                                    data-container-id="comp-jpkn0sgs" data-page-id="jqtbi" data-media-comp-type="image"
                                    class="bgMedia" id="comp-jpkn0sgsbalatamedia">
                                    <wix-image style="width:100%;height:100%;position:absolute;top:0;left:0"
                                      data-has-bg-scroll-effect=""
                                      data-image-info="{&quot;imageData&quot;:{&quot;type&quot;:&quot;Image&quot;,&quot;id&quot;:&quot;dataItem-jqg2jtnf1&quot;,&quot;metaData&quot;:{&quot;pageId&quot;:&quot;jqtbi&quot;,&quot;isPreset&quot;:false,&quot;schemaVersion&quot;:&quot;1.0&quot;,&quot;isHidden&quot;:false},&quot;title&quot;:&quot;Circuit4.jpg&quot;,&quot;uri&quot;:&quot;0b209a_10feb1067c234e2ebc1e5eae8094838e~mv2.jpg&quot;,&quot;description&quot;:&quot;private/6b785ff3ed5246f7bfdc1437fcf34527&quot;,&quot;width&quot;:1366,&quot;height&quot;:768,&quot;alt&quot;:&quot;&quot;,&quot;artist&quot;:{&quot;id&quot;:&quot;&quot;,&quot;name&quot;:&quot;&quot;},&quot;displayMode&quot;:&quot;fill&quot;},&quot;containerId&quot;:&quot;comp-jpkn0sgs&quot;,&quot;alignType&quot;:&quot;center&quot;,&quot;displayMode&quot;:&quot;fill&quot;}"
                                      data-is-svg="false" data-type="image" id="comp-jpkn0sgsbalatamediaimage"
                                      class="bgImage"><img id="comp-jpkn0sgsbalatamediaimageimage"
                                        style="width:100%;height:100%;object-position:50% 50%;object-fit:cover" alt=""
                                        data-type="image" itemProp="image"
                                        src="bg1_full.webp" />
                                    </wix-image>
                                  </div>
                                </div>
                                <div class="strc1inlineContent" style="width:100%;position:relative;top:0;bottom:0"
                                  id="comp-jpkn0sgsinlineContent">
                                  <style id="comp-jpkn0sgs-mesh-styles">
                                    #comp-jpkn0sgsinlineContent {
                                      height: auto;
                                      width: 100%;
                                      position: relative;
                                    }

                                    #comp-jpkn0sgsinlineContent-gridWrapper {
                                      pointer-events: none;
                                    }

                                    #comp-jpkn0sgsinlineContent-gridContainer {
                                      position: static;
                                      display: grid;
                                      height: auto;
                                      width: 100%;
                                      min-height: auto;
                                      grid-template-rows: 1fr;
                                      grid-template-columns: 100%;
                                    }

                                    #comp-jpkn0sgs1 {
                                      position: relative;
                                      margin: 71px 0px 39px calc((100% - 980px) * 0.5);
                                      left: 100px;
                                      grid-area: 1 / 1 / 2 / 2;
                                      justify-self: start;
                                      align-self: start;
                                    }

                                    #comp-jpkn0sgscenteredContent {
                                      position: relative;
                                    }

                                    #comp-jpkn0sgsinlineContent-gridContainer>* {
                                      pointer-events: auto;
                                    }

                                    #comp-jpkn0sgsinlineContent-gridContainer>[id$="-rotated-wrapper"] {
                                      pointer-events: none;
                                    }

                                    #comp-jpkn0sgsinlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                                      pointer-events: auto;
                                    }
                                  </style>
                                  <div id="comp-jpkn0sgsinlineContent-gridWrapper" data-mesh-internal="true">
                                    <div id="comp-jpkn0sgsinlineContent-gridContainer" data-mesh-internal="true">
                                      <div data-packed="true"
                                        style="top:;bottom:;left:;right:;width:780px;height:auto;position:;pointer-events:none"
                                        class="txtNew" id="comp-jpkn0sgs1">
                                        <h2 class="font_6" style="line-height:1.35em; text-align:center;"><span
                                            style="font-weight:normal;"><span
                                              style="font-family:ebrima,sans-serif;"><span
                                                style="font-style:italic;">Leading&nbsp;Software&nbsp;Engineers&nbsp;to
                                                Excellence</span></span></span></h2>
                                      </div>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </section>
                          <section
                            style="left:0;width:100%;min-width:980px;height:auto;top:;bottom:;right:;position:;margin-left:0"
                            data-responsive="true" data-is-screen-width="true" data-col-margin="0" data-row-margin="0"
                            class="strc1" id="comp-jqg4qgor">
                            <div
                              style="position:absolute;top:0;width:calc(100% - 0px);height:100%;overflow:hidden;pointer-events:auto;min-width:980px;left:0;right:0;bottom:0"
                              data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name="" data-media-type=""
                              data-use-clip-path="" data-needs-clipping="" data-wix-video-layout="" class="strc1balata"
                              id="comp-jqg4qgorbalata">
                              <div style="position:absolute;width:100%;height:100%;top:0;background-color:transparent"
                                class="bgColor" id="comp-jqg4qgorbalatabgcolor">
                                <div style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                  id="comp-jqg4qgorbalatabgcoloroverlay" class="bgColoroverlay"></div>
                              </div>
                            </div>
                            <div style="position:relative;width:calc(100% - 0px);min-width:980px"
                              id="comp-jqg4qgorinlineContent" class="strc1inlineContent">
                              <div
                                style="position:relative;width:100%;left:0;flex:980;margin-left:0;min-width:980px;top:0;margin-top:0;margin-bottom:0;height:;display:flex;bottom:;right:"
                                data-content-width="980" data-is-mesh="true" class="mc1" id="comp-jqg4qgv8">
                                <div style="position:relative;height:100%;width:100%" id="comp-jqg4qgv8container"
                                  class="mc1container">
                                  <div
                                    style="position:absolute;top:0;width:100%;height:100%;overflow:hidden;pointer-events:auto;left:0;right:0;bottom:0"
                                    data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name=""
                                    data-media-type="" data-use-clip-path="" data-needs-clipping=""
                                    data-wix-video-layout="" class="mc1balata" id="comp-jqg4qgv8balata">
                                    <div
                                      style="position:absolute;width:100%;height:100%;top:0;background-color:rgba(250, 250, 250, 1)"
                                      class="bgColor" id="comp-jqg4qgv8balatabgcolor">
                                      <div
                                        style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                        id="comp-jqg4qgv8balatabgcoloroverlay" class="bgColoroverlay"></div>
                                    </div>
                                  </div>
                                  <div style="position:relative;left:0;right:0;top:0;bottom:0;width:100%;height:100%"
                                    id="comp-jqg4qgv8inlineContentParent" class="mc1inlineContentParent">
                                    <div class="mc1inlineContent" style="width:100%;position:relative;top:0;bottom:0"
                                      id="comp-jqg4qgv8inlineContent">
                                      <style id="comp-jqg4qgv8-mesh-styles">
                                        #comp-jqg4qgv8inlineContent {
                                          height: auto;
                                          width: 100%;
                                          position: relative;
                                        }

                                        #comp-jqg4qgv8inlineContent-gridWrapper {
                                          pointer-events: none;
                                        }

                                        #comp-jqg4qgv8inlineContent-gridContainer {
                                          position: static;
                                          display: grid;
                                          height: auto;
                                          width: 100%;
                                          min-height: auto;
                                          grid-template-rows: min-content min-content 1fr;
                                          grid-template-columns: 100%;
                                        }

                                        #comp-jqg4qgvg {
                                          position: relative;
                                          margin: 70px 0px 18px calc((100% - 980px) * 0.5);
                                          left: 228px;
                                          grid-area: 1 / 1 / 2 / 2;
                                          justify-self: start;
                                          align-self: start;
                                        }

                                        #comp-jqg4qgwo {
                                          position: relative;
                                          margin: 0px 0px 3px calc((100% - 980px) * 0.5);
                                          left: 472px;
                                          grid-area: 2 / 1 / 3 / 2;
                                          justify-self: start;
                                          align-self: start;
                                        }

                                        #comp-jqg4qgxd {
                                          position: relative;
                                          margin: 12px 0px 4px calc((100% - 980px) * 0.5);
                                          left: 0px;
                                          grid-area: 3 / 1 / 4 / 2;
                                          justify-self: start;
                                          align-self: start;
                                        }

                                        #comp-k0vpgq0d {
                                          position: relative;
                                          margin: 0px 0px 60px calc((100% - 980px) * 0.5);
                                          left: 949px;
                                          grid-area: 3 / 1 / 4 / 2;
                                          justify-self: start;
                                          align-self: start;
                                        }

                                        #comp-jqg4qgv8centeredContent {
                                          position: relative;
                                        }

                                        #comp-jqg4qgv8inlineContent-gridContainer>* {
                                          pointer-events: auto;
                                        }

                                        #comp-jqg4qgv8inlineContent-gridContainer>[id$="-rotated-wrapper"] {
                                          pointer-events: none;
                                        }

                                        #comp-jqg4qgv8inlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                                          pointer-events: auto;
                                        }
                                      </style>
                                      <div id="comp-jqg4qgv8inlineContent-gridWrapper" data-mesh-internal="true">
                                        <div id="comp-jqg4qgv8inlineContent-gridContainer" data-mesh-internal="true">
                                          <div data-packed="true"
                                            style="top:;bottom:;left:;right:;width:523px;height:auto;position:;pointer-events:none"
                                            class="txtNew" id="comp-jqg4qgvg">
                                            <h2 class="font_2" style="font-size:44px; text-align:center;"><span
                                                class="color_20"><span
                                                  style="font-family:ebrima,sans-serif;"><span
                                                    style="font-size:44px;">Profile</span></span></span></h2>
                                          </div>
                                          <div data-border-width="3"
                                            style="transform-origin:center 1.5px;top:;bottom:;left:;right:;width:32px;height:5px;position:"
                                            class="style-k0sb3z94" id="comp-jqg4qgwo"></div>
                                          <section
                                            style="left:0;width:980px;min-width:980px;height:auto;top:;bottom:;right:;position:"
                                            data-responsive="true" data-col-margin="0" data-row-margin="0" class="strc1"
                                            id="comp-jqg4qgxd">
                                            <div
                                              style="position:absolute;top:0;width:calc(100% - 0px);height:100%;overflow:hidden;pointer-events:auto;min-width:980px;left:0;right:0;bottom:0"
                                              data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name=""
                                              data-media-type="" data-use-clip-path="" data-needs-clipping=""
                                              data-wix-video-layout="" class="strc1balata" id="comp-jqg4qgxdbalata">
                                              <div
                                                style="position:absolute;width:100%;height:100%;top:0;background-color:transparent"
                                                class="bgColor" id="comp-jqg4qgxdbalatabgcolor">
                                                <div
                                                  style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                                  id="comp-jqg4qgxdbalatabgcoloroverlay" class="bgColoroverlay"></div>
                                              </div>
                                            </div>
                                            <div style="position:relative;width:calc(100% - 0px);min-width:980px"
                                              id="comp-jqg4qgxdinlineContent" class="strc1inlineContent">
                                              <div
                                                style="position:relative;width:100%;left:0;flex:334;margin-left:0;min-width:334px;top:0;margin-top:0;margin-bottom:0;height:;display:flex;bottom:;right:"
                                                data-content-width="334" data-is-mesh="true" class="mc1"
                                                id="comp-jqg4qgxk">
                                                <div style="position:relative;height:100%;width:100%"
                                                  id="comp-jqg4qgxkcontainer" class="mc1container">
                                                  <div
                                                    style="position:absolute;top:0;width:100%;height:100%;overflow:hidden;pointer-events:auto;left:0;right:0;bottom:0"
                                                    data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name=""
                                                    data-media-type="" data-use-clip-path="" data-needs-clipping=""
                                                    data-wix-video-layout="" class="mc1balata" id="comp-jqg4qgxkbalata">
                                                    <div
                                                      style="position:absolute;width:100%;height:100%;top:0;background-color:transparent"
                                                      class="bgColor" id="comp-jqg4qgxkbalatabgcolor">
                                                      <div
                                                        style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                                        id="comp-jqg4qgxkbalatabgcoloroverlay" class="bgColoroverlay">
                                                      </div>
                                                    </div>
                                                  </div>
                                                  <div
                                                    style="position:relative;left:0;right:0;top:0;bottom:0;width:100%;height:100%"
                                                    id="comp-jqg4qgxkinlineContentParent"
                                                    class="mc1inlineContentParent">
                                                    <div class="mc1inlineContent"
                                                      style="width:100%;position:relative;top:0;bottom:0"
                                                      id="comp-jqg4qgxkinlineContent">
                                                      <style id="comp-jqg4qgxk-mesh-styles">
                                                        #comp-jqg4qgxkinlineContent {
                                                          height: auto;
                                                          width: 100%;
                                                          position: relative;
                                                        }

                                                        #comp-jqg4qgxkinlineContent-gridWrapper {
                                                          pointer-events: none;
                                                        }

                                                        #comp-jqg4qgxkinlineContent-gridContainer {
                                                          position: static;
                                                          display: grid;
                                                          height: auto;
                                                          width: 100%;
                                                          min-height: 397px;
                                                          grid-template-rows: min-content 1fr;
                                                          grid-template-columns: 100%;
                                                        }

                                                        #comp-jqkcqljp {
                                                          position: relative;
                                                          margin: 46px 0px 12px calc((100% - 334px) * 0.5);
                                                          left: 28px;
                                                          grid-area: 1 / 1 / 2 / 2;
                                                          justify-self: start;
                                                          align-self: start;
                                                        }

                                                        #comp-jqg4qh0r {
                                                          position: relative;
                                                          margin: 0px 0px 10px calc((100% - 334px) * 0.5);
                                                          left: 28px;
                                                          grid-area: 2 / 1 / 3 / 2;
                                                          justify-self: start;
                                                          align-self: start;
                                                        }

                                                        #comp-jqg4qgxkcenteredContent {
                                                          position: relative;
                                                        }

                                                        #comp-jqg4qgxkinlineContent-gridContainer>* {
                                                          pointer-events: auto;
                                                        }

                                                        #comp-jqg4qgxkinlineContent-gridContainer>[id$="-rotated-wrapper"] {
                                                          pointer-events: none;
                                                        }

                                                        #comp-jqg4qgxkinlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                                                          pointer-events: auto;
                                                        }
                                                      </style>
                                                      <div id="comp-jqg4qgxkinlineContent-gridWrapper"
                                                        data-mesh-internal="true">
                                                        <div id="comp-jqg4qgxkinlineContent-gridContainer"
                                                          data-mesh-internal="true">
                                                          <div data-packed="true"
                                                            style="top:;bottom:;left:;right:;width:131px;height:auto;position:;pointer-events:none"
                                                            class="txtNew" id="comp-jqkcqljp">
                                                            <h3 class="font_3" style="font-size:27px;"><span
                                                                class="color_20"><span style="font-size:27px;">About
                                                                  Me</span></span></h3>
                                                          </div>
                                                          <div data-packed="false"
                                                            style="top:;bottom:;left:;right:;width:287px;height:auto;position:;min-height:195px;pointer-events:none"
                                                            data-min-height="195" class="txtNew" id="comp-jqg4qh0r">
                                                            <p class="font_8"
                                                              style="font-size:14px; line-height:1.3em;"><span
                                                                style="font-size:14px;"><span
                                                                  style="color:#000000;"><span
                                                                    style="font-family:helvetica-w01-light,helvetica-w02-light,sans-serif;">I
                                                                    have led software engineers for 14 years, after
                                                                    being an engineer myself. I&#39;ve lived up and down
                                                                    the west coast, the vast majority of time in Oregon.
                                                                    I&#39;m looking for a new opportunity in the
                                                                    Portland area.</span></span></span></p>

                                                            <p class="font_8"
                                                              style="font-size:14px; line-height:1.3em;">&nbsp;</p>

                                                            <p class="font_8"
                                                              style="font-size:14px; line-height:1.3em;"><span
                                                                style="font-size:14px;"><span
                                                                  style="color:#000000;"><span
                                                                    style="font-family:helvetica-w01-light,helvetica-w02-light,sans-serif;">If
                                                                    you&#39;re looking for someone who&nbsp;excels at
                                                                    coordinating tasks and projects, loves improving
                                                                    development processes and technology, and enjoys
                                                                    helping groups of engineers bond into trusting,
                                                                    solid, performing teams, please contact
                                                                    me.</span></span></span></p>
                                                          </div>
                                                        </div>
                                                      </div>
                                                    </div>
                                                  </div>
                                                </div>
                                              </div>
                                              <div
                                                style="position:relative;width:100%;left:0;flex:323;margin-left:0px;min-width:323px;top:0;margin-top:0;margin-bottom:0;height:;display:flex;bottom:;right:"
                                                data-content-width="323" data-is-mesh="true" class="mc1"
                                                id="comp-jqg4qh2x">
                                                <div style="position:relative;height:100%;width:100%"
                                                  id="comp-jqg4qh2xcontainer" class="mc1container">
                                                  <div
                                                    style="position:absolute;top:0;width:100%;height:100%;overflow:hidden;pointer-events:auto;left:0;right:0;bottom:0"
                                                    data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name=""
                                                    data-media-type="" data-use-clip-path="" data-needs-clipping=""
                                                    data-wix-video-layout="" class="mc1balata" id="comp-jqg4qh2xbalata">
                                                    <div
                                                      style="position:absolute;width:100%;height:100%;top:0;background-color:transparent"
                                                      class="bgColor" id="comp-jqg4qh2xbalatabgcolor">
                                                      <div
                                                        style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                                        id="comp-jqg4qh2xbalatabgcoloroverlay" class="bgColoroverlay">
                                                      </div>
                                                    </div>
                                                  </div>
                                                  <div
                                                    style="position:relative;left:0;right:0;top:0;bottom:0;width:100%;height:100%"
                                                    id="comp-jqg4qh2xinlineContentParent"
                                                    class="mc1inlineContentParent">
                                                    <div class="mc1inlineContent"
                                                      style="width:100%;position:relative;top:0;bottom:0"
                                                      id="comp-jqg4qh2xinlineContent">
                                                      <style id="comp-jqg4qh2x-mesh-styles">
                                                        #comp-jqg4qh2xinlineContent {
                                                          height: auto;
                                                          width: 100%;
                                                          position: relative;
                                                        }

                                                        #comp-jqg4qh2xinlineContent-gridWrapper {
                                                          pointer-events: none;
                                                        }

                                                        #comp-jqg4qh2xinlineContent-gridContainer {
                                                          position: static;
                                                          display: grid;
                                                          height: auto;
                                                          width: 100%;
                                                          min-height: auto;
                                                          grid-template-rows: min-content 1fr;
                                                          grid-template-columns: 100%;
                                                        }

                                                        #comp-jqg4qh6j {
                                                          position: relative;
                                                          margin: 46px 0px 29px calc((100% - 323px) * 0.5);
                                                          left: 69px;
                                                          grid-area: 1 / 1 / 2 / 2;
                                                          justify-self: start;
                                                          align-self: start;
                                                        }

                                                        #comp-jqg4qh4k {
                                                          position: relative;
                                                          margin: 0px 0px 63px calc((100% - 323px) * 0.5);
                                                          left: 142px;
                                                          grid-area: 2 / 1 / 3 / 2;
                                                          justify-self: start;
                                                          align-self: start;
                                                        }

                                                        #comp-jqg4qh2xcenteredContent {
                                                          position: relative;
                                                        }

                                                        #comp-jqg4qh2xinlineContent-gridContainer>* {
                                                          pointer-events: auto;
                                                        }

                                                        #comp-jqg4qh2xinlineContent-gridContainer>[id$="-rotated-wrapper"] {
                                                          pointer-events: none;
                                                        }

                                                        #comp-jqg4qh2xinlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                                                          pointer-events: auto;
                                                        }
                                                      </style>
                                                      <div id="comp-jqg4qh2xinlineContent-gridWrapper"
                                                        data-mesh-internal="true">
                                                        <div id="comp-jqg4qh2xinlineContent-gridContainer"
                                                          data-mesh-internal="true">
                                                          <div
                                                            style="top:;bottom:;left:;right:;width:189px;height:217px;position:"
                                                            title="guy4.jpg" data-is-responsive="false"
                                                            data-display-mode="fill" data-content-padding-horizontal="0"
                                                            data-content-padding-vertical="0" data-exact-height="217"
                                                            class="style-k0sb3z8k" id="comp-jqg4qh6j">
                                                            <div style="width:189px;height:217px" id="comp-jqg4qh6jlink"
                                                              class="style-k0sb3z8klink">
                                                              <wix-image style="width:189px;height:217px;top:0;left:0"
                                                                data-has-bg-scroll-effect=""
                                                                data-image-info="{&quot;imageData&quot;:{&quot;type&quot;:&quot;Image&quot;,&quot;id&quot;:&quot;dataItem-jqg4qh6k&quot;,&quot;metaData&quot;:{&quot;pageId&quot;:&quot;jqtbi&quot;,&quot;isPreset&quot;:false,&quot;schemaVersion&quot;:&quot;2.0&quot;,&quot;isHidden&quot;:false},&quot;title&quot;:&quot;guy4.jpg&quot;,&quot;uri&quot;:&quot;0b209a_25b630b75f6449f3bc3a92c8cc5768a1~mv2_d_2248_2582_s_2.jpg&quot;,&quot;description&quot;:&quot;&quot;,&quot;width&quot;:2248,&quot;height&quot;:2582,&quot;alt&quot;:&quot;IMG_20190101_211526840_BURST000_COVER-b.&quot;,&quot;name&quot;:&quot;IMG_20190101_211526840_BURST000_COVER-b.&quot;,&quot;displayMode&quot;:&quot;fill&quot;},&quot;containerId&quot;:&quot;comp-jqg4qh6j&quot;,&quot;displayMode&quot;:&quot;fill&quot;}"
                                                                data-is-svg="false" id="comp-jqg4qh6jimg"
                                                                class="style-k0sb3z8kimg"><img
                                                                  id="comp-jqg4qh6jimgimage"
                                                                  style="object-position:50% 50%;width:189px;height:217px;object-fit:cover"
                                                                  alt="IMG_20190101_211526840_BURST000_COVER-b."
                                                                  data-type="image" itemProp="image"
                                                                  src="IMG_20190101_211526840_BURST000_COVER-b_.jpg" />
                                                              </wix-image>
                                                            </div>
                                                          </div>
                                                          <div data-is-responsive="false"
                                                            style="width:42px;height:42px;top:;bottom:;left:;right:;position:"
                                                            data-hide-prejs="true" class="lb1" id="comp-jqg4qh4k">
                                                            <ul aria-label="Social bar" id="comp-jqg4qh4kitemsContainer"
                                                              class="lb1itemsContainer">
                                                              <li
                                                                style="width:42px;height:42px;margin-bottom:0;margin-right:7px;display:inline-block"
                                                                class="lb1imageItem" id="comp-jqg4qh4k0image"><a
                                                                  href="https://www.linkedin.com/in/darryl-martin/"
                                                                  target="_blank"
                                                                  data-content="https://www.linkedin.com/in/darryl-martin/"
                                                                  data-type="external" id="comp-jqg4qh4k0imagelink"
                                                                  class="lb1imageItemlink">
                                                                  <wix-image style="width:20px;height:20px;position:absolute" data-has-bg-scroll-effect="" 
                                                                    data-image-info="{&quot;imageData&quot;:{&quot;type&quot;:&quot;Image&quot;,&quot;id&quot;:&quot;dataItem-jpkmxxcf1&quot;,&quot;metaData&quot;:{&quot;pageId&quot;:&quot;masterPage&quot;,&quot;isPreset&quot;:false,&quot;schemaVersion&quot;:&quot;1.0&quot;,&quot;isHidden&quot;:false},&quot;title&quot;:&quot;&quot;,&quot;uri&quot;:&quot;6ea5b4a88f0b4f91945b40499aa0af00.png&quot;,&quot;description&quot;:&quot;&quot;,&quot;width&quot;:200,&quot;height&quot;:200,&quot;alt&quot;:&quot;&quot;,&quot;name&quot;:&quot;linkedin&quot;,&quot;link&quot;:{&quot;type&quot;:&quot;ExternalLink&quot;,&quot;id&quot;:&quot;dataItem-jpkmxxcf2&quot;,&quot;metaData&quot;:{&quot;pageId&quot;:&quot;masterPage&quot;,&quot;isPreset&quot;:false,&quot;schemaVersion&quot;:&quot;1.0&quot;,&quot;isHidden&quot;:false},&quot;url&quot;:&quot;https://www.linkedin.com/in/darryl-martin&quot;,&quot;target&quot;:&quot;_blank&quot;},&quot;displayMode&quot;:&quot;fill&quot;},&quot;containerId&quot;:&quot;comp-jpkmxxap&quot;,&quot;displayMode&quot;:&quot;fill&quot;}" 
                                                                    data-is-svg="false" id="comp-jpkmxxap0imageimage" class="lb1imageItemimage" 
                                                                    data-src="https://static.wixstatic.com/media/6ea5b4a88f0b4f91945b40499aa0af00.png/v1/fill/w_20,h_20,al_c,q_80,usm_0.66_1.00_0.01/linkedin.webp">
                                                                    <img id="comp-jpkmxxap0imageimageimage" alt="" data-type="image" itemprop="image" style="width: 20px; height: 20px; object-fit: cover;" 
                                                                    src="https://static.wixstatic.com/media/6ea5b4a88f0b4f91945b40499aa0af00.png/v1/fill/w_20,h_20,al_c,q_80,usm_0.66_1.00_0.01/linkedin.webp">
                                                                  </wix-image>
                                                                </a></li>
                                                            </ul>
                                                          </div>
                                                        </div>
                                                      </div>
                                                    </div>
                                                  </div>
                                                </div>
                                              </div>
                                              <div
                                                style="position:relative;width:100%;left:0;flex:323;margin-left:0px;min-width:323px;top:0;margin-top:0;margin-bottom:0;height:;display:flex;bottom:;right:"
                                                data-content-width="323" data-is-mesh="true" class="mc1"
                                                id="comp-jqg4qh81">
                                                <div style="position:relative;height:100%;width:100%"
                                                  id="comp-jqg4qh81container" class="mc1container">
                                                  <div
                                                    style="position:absolute;top:0;width:100%;height:100%;overflow:hidden;pointer-events:auto;left:0;right:0;bottom:0"
                                                    data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name=""
                                                    data-media-type="" data-use-clip-path="" data-needs-clipping=""
                                                    data-wix-video-layout="" class="mc1balata" id="comp-jqg4qh81balata">
                                                    <div
                                                      style="position:absolute;width:100%;height:100%;top:0;background-color:transparent"
                                                      class="bgColor" id="comp-jqg4qh81balatabgcolor">
                                                      <div
                                                        style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                                        id="comp-jqg4qh81balatabgcoloroverlay" class="bgColoroverlay">
                                                      </div>
                                                    </div>
                                                  </div>
                                                  <div
                                                    style="position:relative;left:0;right:0;top:0;bottom:0;width:100%;height:100%"
                                                    id="comp-jqg4qh81inlineContentParent"
                                                    class="mc1inlineContentParent">
                                                    <div class="mc1inlineContent"
                                                      style="width:100%;position:relative;top:0;bottom:0"
                                                      id="comp-jqg4qh81inlineContent">
                                                      <style id="comp-jqg4qh81-mesh-styles">
                                                        #comp-jqg4qh81inlineContent {
                                                          height: auto;
                                                          width: 100%;
                                                          position: relative;
                                                        }

                                                        #comp-jqg4qh81inlineContent-gridWrapper {
                                                          pointer-events: none;
                                                        }

                                                        #comp-jqg4qh81inlineContent-gridContainer {
                                                          position: static;
                                                          display: grid;
                                                          height: auto;
                                                          width: 100%;
                                                          min-height: 397px;
                                                          grid-template-rows: 1fr;
                                                          grid-template-columns: 100%;
                                                        }

                                                        #comp-jqkctex3 {
                                                          position: relative;
                                                          margin: 46px 0px 10px calc((100% - 323px) * 0.5);
                                                          left: 27px;
                                                          grid-area: 1 / 1 / 2 / 2;
                                                          justify-self: start;
                                                          align-self: start;
                                                        }

                                                        #comp-jqg4qh81centeredContent {
                                                          position: relative;
                                                        }

                                                        #comp-jqg4qh81inlineContent-gridContainer>* {
                                                          pointer-events: auto;
                                                        }

                                                        #comp-jqg4qh81inlineContent-gridContainer>[id$="-rotated-wrapper"] {
                                                          pointer-events: none;
                                                        }

                                                        #comp-jqg4qh81inlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                                                          pointer-events: auto;
                                                        }
                                                      </style>
                                                      <div id="comp-jqg4qh81inlineContent-gridWrapper"
                                                        data-mesh-internal="true">
                                                        <div id="comp-jqg4qh81inlineContent-gridContainer"
                                                          data-mesh-internal="true">
                                                          <div data-packed="false"
                                                            style="top:;bottom:;left:;right:;width:240px;height:auto;position:;min-height:245px;pointer-events:none"
                                                            data-min-height="245" class="txtNew" id="comp-jqkctex3">
                                                            <h3 class="font_3" style="font-size:27px;"><span
                                                                class="color_20"><span
                                                                  style="font-size:27px;">Details</span></span></h3>

                                                            <h3 class="font_3" style="font-size:14px;"><span
                                                                style="font-size:14px;"><span
                                                                  class="wixGuard">​</span></span></h3>

                                                            <h3 class="font_3" style="font-size:14px;"><span
                                                                style="font-family:helvetica-w01-light,helvetica-w02-light,sans-serif;"><span
                                                                  style="font-size:14px;"><span
                                                                    style="font-weight:bold;">Name:</span></span></span>
                                                            </h3>

                                                            <h3 class="font_3" style="font-size:14px;"><span
                                                                style="font-family:helvetica-w01-light,helvetica-w02-light,sans-serif;"><span
                                                                  style="font-size:14px;">Darryl Martin</span></span>
                                                            </h3>

                                                            <h3 class="font_3" style="font-size:14px;"><span
                                                                style="font-family:helvetica-w01-light,helvetica-w02-light,sans-serif;"><span
                                                                  style="font-size:14px;"><span
                                                                    class="wixGuard">​</span></span></span></h3>

                                                            <h3 class="font_3" style="font-size:14px;"><span
                                                                style="font-family:helvetica-w01-light,helvetica-w02-light,sans-serif;"><span
                                                                  style="font-weight:bold;"><span
                                                                    style="font-size:14px;">Location:</span></span></span>
                                                            </h3>

                                                            <h3 class="font_3" style="font-size:14px;"><span
                                                                style="font-family:helvetica-w01-light,helvetica-w02-light,sans-serif;"><span
                                                                  style="font-size:14px;">Oregon City,
                                                                  Oregon</span></span></h3>

                                                            <h3 class="font_3" style="font-size:14px;"><span
                                                                style="font-family:helvetica-w01-light,helvetica-w02-light,sans-serif;"><span
                                                                  style="font-size:14px;"><span
                                                                    class="wixGuard">​</span></span></span></h3>

                                                            <h3 class="font_3" style="font-size:14px;"><span
                                                                style="font-family:helvetica-w01-light,helvetica-w02-light,sans-serif;"><span
                                                                  style="font-weight:bold;"><span
                                                                    style="font-size:14px;">Description:</span></span></span>
                                                            </h3>

                                                            <h3 class="font_3" style="font-size:14px;"><span
                                                                style="font-family:helvetica-w01-light,helvetica-w02-light,sans-serif;"><span
                                                                  style="font-size:14px;">Husband, Father, Leader of
                                                                  software engineers and other technical
                                                                  folk.</span></span></h3>
                                                          </div>
                                                        </div>
                                                      </div>
                                                    </div>
                                                  </div>
                                                </div>
                                              </div>
                                            </div>
                                          </section>
<!-- Blog thumbnail                                         <div
                                            style="top:;bottom:;left:;right:;width:980px;height:353px;position:;overflow:hidden;visibility:;min-height:353px;min-width:980px"
                                            data-has-iframe="true" class="style-k0wq1doe" id="comp-k0vpgq0d"><iframe
                                              data-src="https://social-blog.wix.com/recent-posts-widget?cacheKiller=1572971148273&amp;compId=comp-k0vpgq0d&amp;currency=USD&amp;deviceType=desktop&amp;height=353&amp;instance=ktAQ9gBBotA4CAd5OpoqaWUsdMEpg9r3TYzhzuTRRB0.eyJpbnN0YW5jZUlkIjoiNTQwMWZhZWMtZWIzZS00NDJlLWIxMTAtZGJkOThkMzBhNjRhIiwiYXBwRGVmSWQiOiIxNGJjZGVkNy0wMDY2LTdjMzUtMTRkNy00NjZjYjNmMDkxMDMiLCJtZXRhU2l0ZUlkIjoiZDk5OTNlMzAtYTcxYy00MmVkLTg5YjItOWNlOWM2NWY1MWY4Iiwic2lnbkRhdGUiOiIyMDE5LTExLTA1VDE2OjM3OjUxLjIwNVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiJlZWRkZThkYS04ZjUwLTQxZmUtYTBmZC1mYWRhOWRlOWNmMzUiLCJhaWQiOiIyMDg4MmIxOC0wMzU2LTQwNGYtYmFjZC00ZmRhMjU5Zjk1NDQiLCJiaVRva2VuIjoiOGQ5OGM0ZGMtNGMyMi0wNmMzLTM4YTItNDczMDRiNmZmN2IyIiwic2l0ZU93bmVySWQiOiIwYjIwOWFlZC0wMGUyLTRiM2EtYjc4Mi0yM2EyZThlMjZjODgifQ&amp;locale=en&amp;pageId=jqtbi&amp;siteRevision=129&amp;tz=America%2FLos_Angeles&amp;viewMode=site&amp;width=980"
                                              scrolling="no" frameBorder="0"
                                              allow="autoplay; camera; microphone; geolocation; vr"
                                              allowtransparency="true" allowfullscreen="" name="comp-k0vpgq0d"
                                              style="width:980px;height:353px;min-height:353px;min-width:980px;display:block;position:absolute;z-index:"
                                              title="Wix Blog" aria-label="Wix Blog" id="comp-k0vpgq0diframe"
                                              class="style-k0wq1doeiframe"></iframe>
                                            <div id="comp-k0vpgq0doverlay" class="style-k0wq1doeoverlay"></div>
                                          </div>
-->
                                        </div>
                                      </div>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </section>
                          <section
                            style="left:0;width:100%;min-width:980px;height:auto;top:;bottom:;right:;position:;margin-left:0"
                            data-responsive="true" data-is-screen-width="true" data-col-margin="0" data-row-margin="0"
                            class="strc1" id="comp-jpkqjpxi">
                            <div
                              style="position:absolute;top:0;width:calc(100% - 0px);height:100%;overflow:hidden;pointer-events:auto;min-width:980px;left:0;right:0;bottom:0"
                              data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name="" data-media-type=""
                              data-use-clip-path="" data-needs-clipping="" data-wix-video-layout="" class="strc1balata"
                              id="comp-jpkqjpxibalata">
                              <div style="position:absolute;width:100%;height:100%;top:0;background-color:transparent"
                                class="bgColor" id="comp-jpkqjpxibalatabgcolor">
                                <div style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                  id="comp-jpkqjpxibalatabgcoloroverlay" class="bgColoroverlay"></div>
                              </div>
                            </div>
                            <div style="position:relative;width:calc(100% - 0px);min-width:980px"
                              id="comp-jpkqjpxiinlineContent" class="strc1inlineContent">
                              <div
                                style="position:relative;width:100%;left:0;flex:980;margin-left:0;min-width:980px;top:0;margin-top:0;margin-bottom:0;height:;display:flex;bottom:;right:"
                                data-content-width="980" data-is-mesh="true" class="strc1" id="comp-jpkqjpxi1">
                                <div
                                  style="position:absolute;top:0;width:100%;height:100%;overflow:hidden;pointer-events:auto;left:0;right:0;bottom:0"
                                  data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name=""
                                  data-media-type="" data-use-clip-path="" data-needs-clipping=""
                                  data-wix-video-layout="" class="strc1balata" id="comp-jpkqjpxi1balata">
                                  <div
                                    style="position:absolute;width:100%;height:100%;top:0;background-color:rgba(244, 236, 221, 1)"
                                    class="bgColor" id="comp-jpkqjpxi1balatabgcolor">
                                    <div
                                      style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                      id="comp-jpkqjpxi1balatabgcoloroverlay" class="bgColoroverlay"></div>
                                  </div>
                                </div>
                                <div class="strc1inlineContent" style="width:100%;position:relative;top:0;bottom:0"
                                  id="comp-jpkqjpxi1inlineContent">
                                  <style id="comp-jpkqjpxi1-mesh-styles">
                                    #comp-jpkqjpxi1inlineContent {
                                      height: auto;
                                      width: 100%;
                                      position: relative;
                                    }

                                    #comp-jpkqjpxi1inlineContent-gridWrapper {
                                      pointer-events: none;
                                    }

                                    #comp-jpkqjpxi1inlineContent-gridContainer {
                                      position: static;
                                      display: grid;
                                      height: auto;
                                      width: 100%;
                                      min-height: auto;
                                      grid-template-rows: 1fr;
                                      grid-template-columns: 100%;
                                    }

                                    #comp-jpkqjpxj1 {
                                      position: relative;
                                      margin: 72px 0px 0px calc((100% - 980px) * 0.5);
                                      left: 30px;
                                      grid-area: 1 / 1 / 2 / 2;
                                      justify-self: start;
                                      align-self: start;
                                    }

                                    #comp-jpkqjpxj2 {
                                      position: relative;
                                      margin: 129px 0px 10px calc((100% - 980px) * 0.5);
                                      left: 724px;
                                      grid-area: 1 / 1 / 2 / 2;
                                      justify-self: start;
                                      align-self: start;
                                    }

                                    #comp-jpkqjpxi1centeredContent {
                                      position: relative;
                                    }

                                    #comp-jpkqjpxi1inlineContent-gridContainer>* {
                                      pointer-events: auto;
                                    }

                                    #comp-jpkqjpxi1inlineContent-gridContainer>[id$="-rotated-wrapper"] {
                                      pointer-events: none;
                                    }

                                    #comp-jpkqjpxi1inlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                                      pointer-events: auto;
                                    }
                                  </style>
                                  <div id="comp-jpkqjpxi1inlineContent-gridWrapper" data-mesh-internal="true">
                                    <div id="comp-jpkqjpxi1inlineContent-gridContainer" data-mesh-internal="true">
                                      <div data-packed="false"
                                        style="top:;bottom:;left:;right:;width:921px;height:auto;position:;min-height:1583px;pointer-events:none"
                                        data-min-height="1583" class="txtNew" id="comp-jpkqjpxj1">
                                        <p class="font_9" style="line-height:1.875em; text-align:center;"><span
                                            style="font-style:normal;"><span
                                              style="font-family:ebrima,sans-serif;"><span
                                                style="font-weight:400;"><span style="font-size:40px;"><span
                                                    class="color_15">Professional Experience</span></span></span></span></span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="wixGuard">​</span>
                                        </p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="wixGuard">​</span>
                                        </p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="wixGuard">​</span>
                                        </p>

                                        <p class="font_9" style="line-height:1.875em;"><span
                                            class="color_15">&nbsp;<span
                                              style="font-weight:bold;">Vobile,&nbsp;</span></span><span
                                            style="font-weight:bold;"><span class="color_15">Portland,
                                              Oregon</span></span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="color_15"><span
                                              style="font-style:italic;">Executive Director of IT and
                                              Engineering</span>&nbsp;<span style="font-style:italic;">,&nbsp; November
                                              2015 &ndash; Present</span></span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="color_15"><span
                                              style="font-style:italic;"><span class="wixGuard">​</span></span></span>
                                        </p>

                                        <p class="font_9">&nbsp; &nbsp; At Vobile I am charge of everything related to
                                          software engineering, IT,&nbsp;and technical support in the Portland office.
                                          That includes&nbsp;maintaining a large legacy software system;&nbsp;building a
                                          new software foundation for modern products; providing technical support
                                          for&nbsp;customers, internal and external; and coordinating technical and
                                          business planning with all levels of&nbsp;management and with other American
                                          and Chinese offices.</p>

                                        <p class="font_9"><span class="wixGuard">​</span></p>

                                        <p class="font_9">&nbsp; &nbsp; I&#39;ve streamlined the engineering process
                                          while at Vobile, guiding the engineers to new programming platforms and
                                          processes. The legacy code is in C/Perl/Mason. I spearheaded the move to
                                          Python/Vue.js and switched from a semi-agile Scrum-like development process to
                                          a truly agile Kanban process.&nbsp;</p>

                                        <p class="font_9"><span class="wixGuard">​</span></p>

                                        <p class="font_9">&nbsp; &nbsp; While at Vobile I&nbsp;migrated the legacy
                                          system and SaaS products&nbsp;- which includes multiple Oracle and Postgres
                                          databases; thousands of programs; e-mail, application, and authentication
                                          services &ndash; from a third party hosted environment to a self-managed AWS
                                          environment. This cut infrastructure costs by 25% in addition to greatly
                                          increasing our flexibility.</p>

                                        <p class="font_9"><span class="wixGuard">​</span></p>

                                        <p class="font_9">&nbsp; &nbsp; At the same time, I moved the company from a
                                          third party hosted network and MSAD service to a self-hosted one, with no
                                          unexpected down time or complications. This cut infrastructure costs another
                                          15%.</p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="wixGuard">​</span>
                                        </p>

                                        <p class="font_9" style="line-height:1.875em;"><span
                                            style="font-weight:bold;"><span class="color_15">Rentrak,&nbsp;Portland,
                                              Oregon</span></span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span
                                            style="font-style:italic;"><span class="color_15">June 1994&nbsp;&ndash;
                                              October 2015</span></span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span
                                            style="font-style:italic;"><span class="wixGuard">​</span></span></p>

                                        <p class="font_9">&nbsp; &nbsp; I spent most of my career at Rentrak, before
                                          they became part of Comscore. I grew from a novice programmer to an
                                          engineering leader, trying out different roles along the way.</p>

                                        <p class="font_9" style="line-height:1.875em;"><span
                                            style="font-style:italic;"><span class="wixGuard">​</span></span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span
                                            style="font-style:italic;"><span class="color_15">Senior Manager Software
                                              Engineering &ndash; On Demand Entertainment, October 2012 &ndash; October
                                              2015</span></span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span
                                            style="font-style:italic;"><span class="wixGuard">​</span></span></p>

                                        <p class="font_9">&nbsp; &nbsp; When the company restructured I transferred to
                                          the On Demand division. There I led&nbsp;three engineering teams: a strategic
                                          projects team, a team of software architects, and a&nbsp;QlikView business
                                          intelligence programming team. We m<span class="color_15">aintained reporting
                                            systems that&nbsp;imported&nbsp;data from hundreds of dissimilar sources to
                                            track nine billion international financial transactions per year. We also
                                            e</span>xplored ways to adapt new technology, new&nbsp;architectures, and
                                          new processes to better our products and our development.</p>

                                        <p class="font_9"><span class="wixGuard">​</span></p>

                                        <p class="font_9">&nbsp; &nbsp; One result of that exploration was the adoption
                                          of QlikView.&nbsp;I l<span class="color_15">ed the design and development of a
                                            company-wide adoption of a QlikView business intelligence reporting system
                                            which we hosted on Amazon cloud services. This led to a decrease in report
                                            development time by a factor of 10.</span></p>

                                        <p class="font_9"><span class="wixGuard">​</span></p>

                                        <p class="font_9"><span class="color_15">&nbsp; &nbsp; One of my more important
                                            roles was&nbsp;as the primary liaison between engineering and other
                                            departments and sub-departments. I was the primary contact with the
                                            infrastructure group, information security, audit, and others. I served on
                                            and led several committees.</span></p>

                                        <p class="font_9"><span class="wixGuard">​</span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span
                                            style="font-style:italic;"><span class="color_15">Director of Information
                                              Services &ndash; Home Entertainment,&nbsp;October 2011 &ndash; October
                                              2012</span></span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="color_15">&nbsp;
                                            &nbsp; </span></p>

                                        <p class="font_9">&nbsp; &nbsp; As the Home Entertainment engineering director,
                                          I led two development teams and a&nbsp;development manager. My primary
                                          accomplishment was successfully converting/incorporating&nbsp;two large
                                          software acquisitions from Microsoft software stacks into modified forms of
                                          our software stack, cementing a relationship with a new major client.​</p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="wixGuard">​</span>
                                        </p>

                                        <p class="font_9" style="line-height:1.875em;"><span
                                            style="font-style:italic;"><span class="color_15">Software Development
                                              Manager &ndash; Home Entertainment, January 2005 &ndash; September
                                              2011</span></span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span
                                            style="font-style:italic;"><span class="wixGuard">​</span></span></p>

                                        <p class="font_9">&nbsp; &nbsp; In my initial management role I took over and
                                          grew the Home Entertainment engineering department. During that time,&nbsp;I
                                          <span class="color_15"><span class="color_15">built and maintained ERP
                                              software;&nbsp;</span></span>s<span class="color_15">uccessfully
                                            implemented the Scrum process and introduced it to the rest of the
                                            company;&nbsp;c<span class="color_15">oordinated a move from a single server
                                              environment to a multi-server, multi-tier environment; worked with IT Risk
                                              Compliance and external auditors as the Sarbanes-Oxley technical
                                              lead;&nbsp;and&nbsp;led the creation of the company&#39;s first online
                                              commerce web site.</span></span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="wixGuard">​</span>
                                        </p>

                                        <p class="font_9" style="line-height:1.875em;"><span
                                            style="font-style:italic;">Oracle Database Administrator&nbsp;<span
                                              class="color_15">&ndash; May 2002&nbsp;&ndash; January 2005</span></span>
                                        </p>

                                        <p class="font_9"><br />
                                          &nbsp; &nbsp; I served a stint as a DBA, performing&nbsp;database maintenance
                                          and administration on multiple Oracle databases, including Oracle versions 8,
                                          9, and 10.</p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="wixGuard">​</span>
                                        </p>

                                        <p class="font_9"><span style="font-style:italic;">Project Manager / Sr.
                                            Programmer / Programmer <span
                                              class="color_15">&ndash;&nbsp;&nbsp;</span>June 1994 &ndash; May
                                            2002</span></p>

                                        <p class="font_9">&nbsp;</p>

                                        <p class="font_9">&nbsp; &nbsp; In my first years at Rentrak, I filled whatever
                                          engineering role was needed. I programmed primarily in C and Perl with some
                                          Java. I managed several legacy conversion projects including a year 2000
                                          conversion involving 2000 separate programs.</p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="wixGuard">​</span>
                                        </p>

                                        <p class="font_9" style="line-height:1.875em;"><span
                                            style="font-weight:bold;"><span class="color_15">Pre-Rentrak</span></span>
                                        </p>

                                        <p class="font_9" style="line-height:1.875em;"><span
                                            style="font-weight:bold;"><span class="wixGuard">​</span></span></p>

                                        <p class="font_9">&nbsp; &nbsp; Between graduation and Rentrak I did contract
                                          development and programmed at Symbio Technologies.</p>

                                        <p class="font_9"><span class="wixGuard">​</span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="wixGuard">​</span>
                                        </p>
                                      </div>
                                      <div id="comp-jpkqjpxj2" data-align="left" data-disabled="false" data-margin="20"
                                        data-should-use-flex="true" data-width="250" data-height="45"
                                        style="top:;bottom:;left:;right:;width:250px;height:45px;position:"
                                        class="style-k0sb3z86" data-state="desktop shouldUseFlex left">
                                        <!-- resume pdf -->
                                        <a href="A_Darryl_Martin_Resume.pdf"
                                          target="_blank" data-type="document" id="comp-jpkqjpxj2link"
                                          class="g-transparent-a style-k0sb3z86link"><span style="margin-left:20px"
                                            id="comp-jpkqjpxj2label" class="style-k0sb3z86label">Download résumé in PDF
                                            format</span></a></div>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </section>
                          <section
                            style="left:0;width:100%;min-width:980px;height:auto;top:;bottom:;right:;position:;margin-left:0"
                            data-responsive="true" data-is-screen-width="true" data-col-margin="0" data-row-margin="0"
                            class="strc1" id="comp-k0se0v2k">
                            <div
                              style="position:absolute;top:0;width:calc(100% - 0px);height:100%;overflow:hidden;pointer-events:auto;min-width:980px;left:0;right:0;bottom:0"
                              data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name="" data-media-type=""
                              data-use-clip-path="" data-needs-clipping="" data-wix-video-layout="" class="strc1balata"
                              id="comp-k0se0v2kbalata">
                              <div style="position:absolute;width:100%;height:100%;top:0;background-color:transparent"
                                class="bgColor" id="comp-k0se0v2kbalatabgcolor">
                                <div style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                  id="comp-k0se0v2kbalatabgcoloroverlay" class="bgColoroverlay"></div>
                              </div>
                            </div>
                            <div style="position:relative;width:calc(100% - 0px);min-width:980px"
                              id="comp-k0se0v2kinlineContent" class="strc1inlineContent">
                              <div
                                style="position:relative;width:100%;left:0;flex:980;margin-left:0;min-width:980px;top:0;margin-top:0;margin-bottom:0;height:;display:flex;bottom:;right:"
                                data-content-width="980" data-is-mesh="true" class="strc1" id="comp-k0se0vaj">
                                <div
                                  style="position:absolute;top:0;width:100%;height:100%;overflow:hidden;pointer-events:auto;left:0;right:0;bottom:0"
                                  data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name=""
                                  data-media-type="" data-use-clip-path="" data-needs-clipping=""
                                  data-wix-video-layout="" class="strc1balata" id="comp-k0se0vajbalata">
                                  <div
                                    style="position:absolute;width:100%;height:100%;top:0;background-color:rgba(244, 236, 221, 1)"
                                    class="bgColor" id="comp-k0se0vajbalatabgcolor">
                                    <div
                                      style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                      id="comp-k0se0vajbalatabgcoloroverlay" class="bgColoroverlay"></div>
                                  </div>
                                </div>
                                <div class="strc1inlineContent" style="width:100%;position:relative;top:0;bottom:0"
                                  id="comp-k0se0vajinlineContent">
                                  <style id="comp-k0se0vaj-mesh-styles">
                                    #comp-k0se0vajinlineContent {
                                      height: auto;
                                      width: 100%;
                                      position: relative;
                                    }

                                    #comp-k0se0vajinlineContent-gridWrapper {
                                      pointer-events: none;
                                    }

                                    #comp-k0se0vajinlineContent-gridContainer {
                                      position: static;
                                      display: grid;
                                      height: auto;
                                      width: 100%;
                                      min-height: auto;
                                      grid-template-rows: 1fr;
                                      grid-template-columns: 100%;
                                    }

                                    #comp-k0se0vbg {
                                      position: relative;
                                      margin: 16px 0px 27px calc((100% - 980px) * 0.5);
                                      left: 30px;
                                      grid-area: 1 / 1 / 2 / 2;
                                      justify-self: start;
                                      align-self: start;
                                    }

                                    #comp-k0se0vajcenteredContent {
                                      position: relative;
                                    }

                                    #comp-k0se0vajinlineContent-gridContainer>* {
                                      pointer-events: auto;
                                    }

                                    #comp-k0se0vajinlineContent-gridContainer>[id$="-rotated-wrapper"] {
                                      pointer-events: none;
                                    }

                                    #comp-k0se0vajinlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                                      pointer-events: auto;
                                    }
                                  </style>
                                  <div id="comp-k0se0vajinlineContent-gridWrapper" data-mesh-internal="true">
                                    <div id="comp-k0se0vajinlineContent-gridContainer" data-mesh-internal="true">
                                      <div data-packed="false"
                                        style="top:;bottom:;left:;right:;width:921px;height:auto;position:;min-height:413px;pointer-events:none"
                                        data-min-height="413" class="txtNew" id="comp-k0se0vbg">
                                        <p class="font_9" style="line-height:1.875em; text-align:center;"><span
                                            style="font-style:normal;"><span
                                              style="font-family:ebrima,sans-serif;"><span
                                                style="font-weight:400;"><span style="font-size:40px;"><span
                                                    class="color_15">Education and
                                                    Skills</span></span></span></span></span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="wixGuard">​</span>
                                        </p>

                                        <p class="font_9">I graduated as a Presidential Scholar from <span
                                            style="font-weight:bold;">Oregon State University</span> with a B.S. in
                                          Computer Science.</p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="wixGuard">​</span>
                                        </p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="color_15"><span
                                              style="text-decoration:underline;">Some additional formal
                                              training:</span></span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="color_15"><span
                                              style="font-weight:bold;">Grant Thompson:</span> Leadership Training,
                                            Portland, Oregon</span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="color_15"><span
                                              style="font-weight:bold;">Dale Carnegie:</span> Effective Communications,
                                            Portland, Oregon</span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="color_15"><span
                                              style="font-weight:bold;">SkillPath Seminars:</span> Business Analysis
                                            Essentials, Portland, Oregon</span></p>

                                        <p class="font_9" style="line-height:1.875em;"><span class="wixGuard">​</span>
                                        </p>

                                        <p class="font_9" style="line-height:1.875em;">I am skilled in software
                                          engineering management, project management,&nbsp;<span
                                            class="color_15">strategic planning, problem resolution, agile processes,
                                            and SDLC. On the technical side I&#39;m skilled at SQL,&nbsp;cloud services
                                            and migration, cyber security, database design and management, Oracle and
                                            Postgres databases, C, Perl, and Python.</span></p>
                                      </div>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </section>
                          <section
                            style="left:0;width:100%;min-width:980px;height:auto;top:;bottom:;right:;position:;margin-left:0"
                            data-responsive="true" data-is-screen-width="true" data-col-margin="0" data-row-margin="0"
                            class="strc1" id="comp-jpkmjxgi">
                            <div
                              style="position:absolute;top:0;width:calc(100% - 0px);height:100%;overflow:hidden;pointer-events:auto;min-width:980px;left:0;right:0;bottom:0"
                              data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name="" data-media-type=""
                              data-use-clip-path="" data-needs-clipping="" data-wix-video-layout="" class="strc1balata"
                              id="comp-jpkmjxgibalata">
                              <div style="position:absolute;width:100%;height:100%;top:0;background-color:transparent"
                                class="bgColor" id="comp-jpkmjxgibalatabgcolor">
                                <div style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                  id="comp-jpkmjxgibalatabgcoloroverlay" class="bgColoroverlay"></div>
                              </div>
                            </div>
                            <div style="position:relative;width:calc(100% - 0px);min-width:980px"
                              id="comp-jpkmjxgiinlineContent" class="strc1inlineContent">
				      <!--    style="position:relative;width:100%;left:0;flex:490;margin-left:0;min-width:490px;top:0;margin-top:0;margin-bottom:0;height:;display:flex;bottom:;right:" -->
				      <!-- style="left:0;width:100%;min-width:980px;height:auto;top:;bottom:;right:;position:;margin-left:0" -->
                              <div style="position:relative;left:0;width:100%;min-width:980px;height:;top:0;bottom:;right:;margin-left:0;display:flex;flex:980"
                                data-content-width="980" data-is-mesh="true" class="style-k0sb3z6u" id="comp-jpkmjxgi1">
<!--                                <div style="position:absolute;height:100%;width:100%" id="comp-jpkmjxgi1container"
                                  class="style-k0sb3z6ucontainer">
-->                                  
                                  <div
                                    style="position:absolute;top:0;width:100%;height:100%;overflow:hidden;pointer-events:auto;left:0;right:0;bottom:0"
                                    data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name=""
                                    data-media-type="" data-use-clip-path="" data-needs-clipping=""
                                    data-wix-video-layout="" class="style-k0sb3z6ubalata" id="comp-jpkmjxgi1balata">
                                    <div style="position:absolute;width:100%;height:100%;top:0" class="bgColor"
                                      id="comp-jpkmjxgi1balatabgcolor">
                                      <div
                                        style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                        id="comp-jpkmjxgi1balatabgcoloroverlay" class="bgColoroverlay"></div>
                                    </div>
                                  </div>
                                  <div style="position:relative;left:0;right:0;top:0;bottom:0;width:100%;height:100%"
                                    id="comp-jpkmjxgi1inlineContentParent" class="style-k0sb3z6uinlineContentParent">
                                    <div class="style-k0sb3z6uinlineContent"
                                      style="width:100%;position:relative;top:0;bottom:0"
                                      id="comp-jpkmjxgi1inlineContent">
                                      <style id="comp-jpkmjxgi1-mesh-styles">
                                        #comp-jpkmjxgi1inlineContent {
                                          height: auto;
                                          width: 100%;
                                          position: relative;
                                        }

                                        #comp-jpkmjxgi1inlineContent-gridWrapper {
                                          pointer-events: none;
                                        }

                                        #comp-jpkmjxgi1inlineContent-gridContainer {
                                          position: static;
                                          display: grid;
                                          height: auto;
                                          width: 100%;
                                          min-height: auto;
                                          grid-template-rows: 1fr;
                                          grid-template-columns: 100%;
                                        }

                                        #comp-jpkmjxgi1 {
                                          position: relative;
                                          margin: 50px 0px 50px calc((100% - 500px) * 0.5);
                                          left: 30px;
                                          grid-area: 1 / 1 / 2 / 2;
                                          justify-self: start;
                                          align-self: start;
                                        }

                                        #comp-jpkmjxgi2 {
                                          position: relative;
                                          margin: 129px 0px 10px calc((100% - 980px) * 0.5);
                                          left: 724px;
                                          grid-area: 1 / 1 / 2 / 2;
                                          justify-self: start;
                                          align-self: start;
                                        }

                                        #comp-jpkmjxgi1centeredContent {
                                          position: relative;
                                        }

                                        #comp-jpkmjxgi1inlineContent-gridContainer>* {
                                          pointer-events: auto;
                                        }

                                        #comp-jpkmjxgi1inlineContent-gridContainer>[id$="-rotated-wrapper"] {
                                          pointer-events: none;
                                        }

                                        #comp-jpkmjxgi1inlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                                          pointer-events: auto;
                                        }
                                      </style>
                                      <div id="comp-jpkmjxgi1inlineContent-gridWrapper" data-mesh-internal="true">
                                        <div id="comp-jpkmjxgi1inlineContent-gridContainer" data-mesh-internal="true">
                                          <div data-packed="false"
                                            style="top:;bottom:;left:;right:;width:921px;height:auto;position:;pointer-events:none"
                                            class="txtNew" id="comp-jpkmjxgi1">
                                            <h2 class="font_6" style="text-align:center; line-height:1.35em;"><span
                                                class="color_15"><span style="text-transform:uppercase;">LET’S CONNECT</span></span></h2>
                                            <p class="font_9" style="line-height:1.875em; text-align:center;"><span
                                                class="color_15"><object height="0"><a class="auto-generated-link"
                                                   data-auto-recognition="true" data-content="darryl.martin@gmail.com"
                                                      href="mailto:darryl.martin@gmail.com"
                                                   data-type="mail">darryl.martin@gmail.com</a></object></span></p>
                                            <p class="font_9" style="line-height:1.875em; text-align:center;"><span
                                                class="color_15">503.451.0451</span></p>
                                          </div>
                                        </div>
                                      </div>
                                    </div>
                                <!-- </div> -->
                              </div>
                              <div
                                style="position:relative;width:100%;left:0;flex:980;margin-left:0px;min-width:490px;top:0;margin-top:0;margin-bottom:0;height:;display:flex;bottom:;right:"
                                data-content-width="490" data-is-mesh="true" class="style-k0sb3z6u" id="comp-jpkmjxgi6">
                                <div style="position:relative;height:100%;width:100%" id="comp-jpkmjxgi6container"
                                  class="style-k0sb3z6ucontainer">
                                  <div
                                    style="position:absolute;top:0;width:100%;height:100%;overflow:hidden;pointer-events:auto;left:0;right:0;bottom:0"
                                    data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name=""
                                    data-media-type="" data-use-clip-path="" data-needs-clipping=""
                                    data-wix-video-layout="" class="style-k0sb3z6ubalata" id="comp-jpkmjxgi6balata">
                                    <div style="position:absolute;width:100%;height:100%;top:0" class="bgColor"
                                      id="comp-jpkmjxgi6balatabgcolor">
                                      <div
                                        style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                        id="comp-jpkmjxgi6balatabgcoloroverlay" class="bgColoroverlay"></div>
                                    </div>
                                  </div>
                                  <div style="position:relative;left:0;right:0;top:0;bottom:0;width:100%;height:100%"
                                    id="comp-jpkmjxgi6inlineContentParent" class="style-k0sb3z6uinlineContentParent">
                                    <div class="style-k0sb3z6uinlineContent"
                                      style="width:100%;position:relative;top:0;bottom:0"
                                      id="comp-jpkmjxgi6inlineContent">
                                      <style id="comp-jpkmjxgi6-mesh-styles">
                                        #comp-jpkmjxgi6inlineContent {
                                          height: auto;
                                          width: 100%;
                                          position: relative;
                                        }

                                        #comp-jpkmjxgi6inlineContent-gridWrapper {
                                          pointer-events: none;
                                        }

                                        #comp-jpkmjxgi6inlineContent-gridContainer {
                                          position: static;
                                          display: grid;
                                          height: auto;
                                          width: 100%;
                                          min-height: auto;
                                          grid-template-rows: 1fr;
                                          grid-template-columns: 100%;
                                        }

                                        #comp-jpkmjxgi7 {
                                          position: relative;
                                          margin: 60px 0px 0px calc((100% - 490px) * 0.5);
                                          left: 16px;
                                          grid-area: 1 / 1 / 2 / 2;
                                          justify-self: start;
                                          align-self: start;
                                        }

                                        #comp-jpkmjxgi6centeredContent {
                                          position: relative;
                                        }

                                        #comp-jpkmjxgi6inlineContent-gridContainer>* {
                                          pointer-events: auto;
                                        }

                                        #comp-jpkmjxgi6inlineContent-gridContainer>[id$="-rotated-wrapper"] {
                                          pointer-events: none;
                                        }

                                        #comp-jpkmjxgi6inlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                                          pointer-events: auto;
                                        }
                                      </style>
				      <!---
                                      <div id="comp-jpkmjxgi6inlineContent-gridWrapper" data-mesh-internal="true">
                                        <div id="comp-jpkmjxgi6inlineContent-gridContainer" data-mesh-internal="true">
                                          <div style="top:;bottom:;left:;right:;width:460px;height:406px;position:"
                                            class="style-k0sb3z7a" data-state="      desktop left" id="comp-jpkmjxgi7">
                                            <form role="form" aria-label="contact form" novalidate=""
                                              id="comp-jpkmjxgi7form-wrapper" class="style-k0sb3z7aform-wrapper">
                                              <div id="comp-jpkmjxgi7wrapper" class="style-k0sb3z7awrapper">
                                                <div class="style-k0sb3z7a_first-row-wrapper"><input type="text"
                                                    id="field1" required="" aria-invalid="false" name="Name" value=""
                                                    class="style-k0sb3z7a_required" placeholder="Name *"
                                                    data-aid="nameField" /><input type="text" id="field2" required=""
                                                    aria-invalid="false" name="Email" value=""
                                                    class="style-k0sb3z7a_required" placeholder="Email *"
                                                    data-aid="emailField" /></div>
                                                <div><input type="text" id="field3" aria-invalid="false" name="Subject"
                                                    value="" class="" placeholder="Subject"
                                                    data-aid="subjectField" /><input type="tel" id="field4"
                                                    aria-invalid="false" name="Phone" value="" class=""
                                                    placeholder="Phone" data-aid="phoneField" /><input type="text"
                                                    id="field5" aria-invalid="false" name="Address" value="" class=""
                                                    placeholder="Address" data-aid="addressField" /></div><textarea
                                                  placeholder="Message" name="Message"
                                                  class="style-k0sb3z7afieldMessage" data-aid="messageField"
                                                  id="comp-jpkmjxgi7fieldMessage"></textarea><button type="submit"
                                                  id="comp-jpkmjxgi7submit" class="style-k0sb3z7asubmit">Send</button>
                                                <div aria-live="polite"
                                                  class="style-k0sb3z7a_success style-k0sb3z7anotifications"
                                                  id="comp-jpkmjxgi7notifications"></div>
                                              </div>
                                            </form>
                                          </div>
                                        </div>
                                      </div>
				    -->
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </section>
                          <section
                            style="left:0;width:100%;min-width:980px;height:auto;top:;bottom:;right:;position:;margin-left:0"
                            data-responsive="true" data-is-screen-width="true" data-col-margin="0" data-row-margin="0"
                            class="strc1" id="comp-jpkmjxgi8">
                            <div
                              style="position:absolute;top:0;width:calc(100% - 0px);height:100%;overflow:hidden;pointer-events:auto;min-width:980px;left:0;right:0;bottom:0"
                              data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name="" data-media-type=""
                              data-use-clip-path="" data-needs-clipping="" data-wix-video-layout="" class="strc1balata"
                              id="comp-jpkmjxgi8balata">
                              <div style="position:absolute;width:100%;height:100%;top:0;background-color:transparent"
                                class="bgColor" id="comp-jpkmjxgi8balatabgcolor">
                                <div style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                  id="comp-jpkmjxgi8balatabgcoloroverlay" class="bgColoroverlay"></div>
                              </div>
                            </div>
                            <div style="position:relative;width:calc(100% - 0px);min-width:980px"
                              id="comp-jpkmjxgi8inlineContent" class="strc1inlineContent">
                              <div
                                style="position:relative;width:100%;left:0;flex:980;margin-left:0;min-width:980px;top:0;margin-top:0;margin-bottom:0;height:;display:flex;bottom:;right:"
                                data-content-width="980" data-is-mesh="true" class="style-k0sb3z6u" id="comp-jpkmjxgi9">
                                <div style="position:relative;height:100%;width:100%" id="comp-jpkmjxgi9container"
                                  class="style-k0sb3z6ucontainer">
                                  <div
                                    style="position:absolute;top:0;width:100%;height:100%;overflow:hidden;pointer-events:auto;left:0;right:0;bottom:0"
                                    data-page-id="jqtbi" data-enable-video="true" data-bg-effect-name=""
                                    data-media-type="Image" data-use-clip-path="" data-needs-clipping=""
                                    data-wix-video-layout="" class="style-k0sb3z6ubalata" id="comp-jpkmjxgi9balata">
                                    <div style="position:absolute;width:100%;height:100%;top:0" class="bgColor"
                                      id="comp-jpkmjxgi9balatabgcolor">
                                      <div
                                        style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                        id="comp-jpkmjxgi9balatabgcoloroverlay" class="bgColoroverlay"></div>
                                    </div>
                                    <div
                                      style="position:absolute;pointer-events:auto;width:100%;height:100%;top:0;left:0"
                                      data-has-bg-effect="" data-fitting="fill" data-align="center"
                                      data-container-id="comp-jpkmjxgi9" data-page-id="jqtbi"
                                      data-media-comp-type="image" class="bgMedia" id="comp-jpkmjxgi9balatamedia">
                                     <wix-image style="width:100%;height:100%;position:absolute;top:0;left:0"
                                        data-has-bg-scroll-effect=""
                                        data-image-info="{&quot;imageData&quot;:{&quot;type&quot;:&quot;Image&quot;,&quot;id&quot;:&quot;dataItem-jqg3nwei1&quot;,&quot;metaData&quot;:{&quot;pageId&quot;:&quot;jqtbi&quot;,&quot;isPreset&quot;:false,&quot;schemaVersion&quot;:&quot;1.0&quot;,&quot;isHidden&quot;:false},&quot;title&quot;:&quot;crystal-wallpaper-2.jpg&quot;,&quot;uri&quot;:&quot;0b209a_d2beceef03db49be997817a879d6fc1f~mv2.jpg&quot;,&quot;description&quot;:&quot;private/6b785ff3ed5246f7bfdc1437fcf34527&quot;,&quot;width&quot;:1366,&quot;height&quot;:768,&quot;alt&quot;:&quot;&quot;,&quot;artist&quot;:{&quot;id&quot;:&quot;&quot;,&quot;name&quot;:&quot;&quot;},&quot;displayMode&quot;:&quot;fill&quot;},&quot;containerId&quot;:&quot;comp-jpkmjxgi9&quot;,&quot;alignType&quot;:&quot;center&quot;,&quot;displayMode&quot;:&quot;fill&quot;}"
                                        data-is-svg="false" data-type="image" id="comp-jpkmjxgi9balatamediaimage"
                                        class="bgImage"><img id="comp-jpkmjxgi9balatamediaimageimage"
                                          style="width:100%;height:100%;object-position:50% 50%;object-fit:cover" alt=""
                                          data-type="image" itemProp="image"
                                          src="bg2_full.webp" />
                                      </wix-image>
                                    </div>
                                  </div>
                                  <div style="position:relative;left:0;right:0;top:0;bottom:0;width:100%;height:100%"
                                    id="comp-jpkmjxgi9inlineContentParent" class="style-k0sb3z6uinlineContentParent">
                                    <div class="style-k0sb3z6uinlineContent"
                                      style="width:100%;position:relative;top:0;bottom:0"
                                      id="comp-jpkmjxgi9inlineContent">
                                      <style id="comp-jpkmjxgi9-mesh-styles">
                                        #comp-jpkmjxgi9inlineContent {
                                          height: 134px;
                                          width: 100%;
                                          min-height: ;
                                          position: relative;
                                        }

                                        #comp-jpkmjxgi9centeredContent {
                                          position: relative;
                                        }

                                        #comp-jpkmjxgi9inlineContent-gridWrapper {
                                          pointer-events: none;
                                        }

                                        #comp-jpkmjxgi9inlineContent-gridContainer>* {
                                          pointer-events: auto;
                                        }

                                        #comp-jpkmjxgi9inlineContent-gridContainer>[id$="-rotated-wrapper"] {
                                          pointer-events: none;
                                        }

                                        #comp-jpkmjxgi9inlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                                          pointer-events: auto;
                                        }
                                      </style>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </section>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </main>
          <header data-is-mobile="false" data-state="" data-site-width="980" data-header-top="0"
            style="position:relative;margin-top:0;left:0;margin-left:0;width:100%;min-width:980px;top:;bottom:;right:"
            class="hc1" id="SITE_HEADER">
            <div style="left:0;width:100%" id="SITE_HEADERscreenWidthBackground" class="hc1screenWidthBackground">
              <div class="hc1_bg"></div>
            </div>
            <div id="SITE_HEADERcenteredContent" class="hc1centeredContent">
              <div style="margin-left:calc((100% - 980px) / 2);width:980px" id="SITE_HEADERbg" class="hc1bg">
                <div class="hc1_bg-center"></div>
              </div>
              <div id="SITE_HEADERinlineContent" class="hc1inlineContent">
                <style id="SITE_HEADER-mesh-styles">
                  #SITE_HEADERinlineContent {
                    height: auto;
                    width: 100%;
                    position: relative;
                  }

                  #SITE_HEADERinlineContent-gridWrapper {
                    pointer-events: none;
                  }

                  #SITE_HEADERinlineContent-gridContainer {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: auto;
                    grid-template-rows: 1fr;
                    grid-template-columns: 100%;
                  }

                  #comp-jpkmxxao {
                    position: relative;
                    margin: 30px 0px 0px calc((100% - 980px) * 0.5);
                    left: 0px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start;
                  }

                  #SITE_HEADERcenteredContent {
                    position: relative;
                  }

                  #SITE_HEADERinlineContent-gridContainer>* {
                    pointer-events: auto;
                  }

                  #SITE_HEADERinlineContent-gridContainer>[id$="-rotated-wrapper"] {
                    pointer-events: none;
                  }

                  #SITE_HEADERinlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                    pointer-events: auto;
                  }
                </style>
                <div id="SITE_HEADERinlineContent-gridWrapper" data-mesh-internal="true">
                  <div id="SITE_HEADERinlineContent-gridContainer" data-mesh-internal="true">
                    <section
                      style="left:0;width:100%;min-width:860px;height:auto;top:;bottom:;right:;position:;margin-left:0"
                      data-responsive="true" data-is-screen-width="true" data-col-margin="0" data-row-margin="0"
                      class="strc1" id="comp-jpkmxxao">
                      <div
                        style="position:absolute;top:0;width:calc(100% - 120px);height:100%;overflow:hidden;pointer-events:auto;min-width:980px;left:0;right:0;bottom:0"
                        data-page-id="masterPage" data-enable-video="true" data-bg-effect-name="" data-media-type=""
                        data-use-clip-path="" data-needs-clipping="" data-wix-video-layout="" class="strc1balata"
                        id="comp-jpkmxxaobalata">
                        <div style="position:absolute;width:100%;height:100%;top:0;background-color:transparent"
                          class="bgColor" id="comp-jpkmxxaobalatabgcolor">
                          <div style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                            id="comp-jpkmxxaobalatabgcoloroverlay" class="bgColoroverlay"></div>
                        </div>
                      </div>
                      <div style="position:relative;width:calc(100% - 120px);min-width:980px"
                        id="comp-jpkmxxaoinlineContent" class="strc1inlineContent">
                        <div
                          style="position:relative;width:100%;left:0;flex:254;margin-left:0;min-width:254px;top:0;margin-top:0;margin-bottom:0;height:;display:flex;bottom:;right:"
                          data-content-width="254" data-is-mesh="true" class="style-k0sb3z5z" id="comp-jpkmxxao1">
                          <div style="position:relative;height:100%;width:100%" id="comp-jpkmxxao1container"
                            class="style-k0sb3z5zcontainer">
                            <div
                              style="position:absolute;top:0;width:100%;height:100%;overflow:hidden;pointer-events:auto;left:0;right:0;bottom:0"
                              data-page-id="masterPage" data-enable-video="true" data-bg-effect-name=""
                              data-media-type="" data-use-clip-path="" data-needs-clipping="" data-wix-video-layout=""
                              class="style-k0sb3z5zbalata" id="comp-jpkmxxao1balata">
                              <div style="position:absolute;width:100%;height:100%;top:0" class="bgColor"
                                id="comp-jpkmxxao1balatabgcolor">
                                <div style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                  id="comp-jpkmxxao1balatabgcoloroverlay" class="bgColoroverlay"></div>
                              </div>
                            </div>
                            <div style="position:relative;left:0;right:0;top:0;bottom:0;width:100%;height:100%"
                              id="comp-jpkmxxao1inlineContentParent" class="style-k0sb3z5zinlineContentParent">
                              <div class="style-k0sb3z5zinlineContent"
                                style="width:100%;position:relative;top:0;bottom:0" id="comp-jpkmxxao1inlineContent">
                                <style id="comp-jpkmxxao1-mesh-styles">
                                  #comp-jpkmxxao1inlineContent {
                                    height: auto;
                                    width: 100%;
                                    position: relative;
                                  }

                                  #comp-jpkmxxao1inlineContent-gridWrapper {
                                    pointer-events: none;
                                  }

                                  #comp-jpkmxxao1inlineContent-gridContainer {
                                    position: static;
                                    display: grid;
                                    height: auto;
                                    width: 100%;
                                    min-height: auto;
                                    grid-template-rows: 1fr;
                                    grid-template-columns: 100%;
                                  }

                                  #comp-jpkmxxao2 {
                                    position: relative;
                                    margin: 8px 0px 30px calc((100% - 254px) * 0);
                                    left: 20px;
                                    grid-area: 1 / 1 / 2 / 2;
                                    justify-self: start;
                                    align-self: start;
                                  }

                                  #comp-jpkmxxao1centeredContent {
                                    position: relative;
                                  }

                                  #comp-jpkmxxao1inlineContent-gridContainer>* {
                                    pointer-events: auto;
                                  }

                                  #comp-jpkmxxao1inlineContent-gridContainer>[id$="-rotated-wrapper"] {
                                    pointer-events: none;
                                  }

                                  #comp-jpkmxxao1inlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                                    pointer-events: auto;
                                  }
                                </style>
                                <div id="comp-jpkmxxao1inlineContent-gridWrapper" data-mesh-internal="true">
                                  <div id="comp-jpkmxxao1inlineContent-gridContainer" data-mesh-internal="true">
                                    <div data-packed="true"
                                      style="top:;bottom:;left:;right:;width:234px;height:auto;position:;pointer-events:none"
                                      class="txtNew" id="comp-jpkmxxao2">
                                      <h2 class="font_0" style="line-height:1.41em;"><span class="color_15"><span
                                            style="text-decoration:none;"><a href="https://www.darrylmartin.com"
                                              target="_self">ALAN DARRYL MARTIN</a></span></span></h2>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                        <div
                          style="position:relative;width:100%;left:0;flex:726;margin-left:0px;min-width:726px;top:0;margin-top:0;margin-bottom:0;height:;display:flex;bottom:;right:"
                          data-content-width="726" data-is-mesh="true" class="style-k0sb3z5z" id="comp-jpkmxxao3">
                          <div style="position:relative;height:100%;width:100%" id="comp-jpkmxxao3container"
                            class="style-k0sb3z5zcontainer">
                            <div
                              style="position:absolute;top:0;width:100%;height:100%;overflow:hidden;pointer-events:auto;left:0;right:0;bottom:0"
                              data-page-id="masterPage" data-enable-video="true" data-bg-effect-name=""
                              data-media-type="" data-use-clip-path="" data-needs-clipping="" data-wix-video-layout=""
                              class="style-k0sb3z5zbalata" id="comp-jpkmxxao3balata">
                              <div style="position:absolute;width:100%;height:100%;top:0" class="bgColor"
                                id="comp-jpkmxxao3balatabgcolor">
                                <div style="width:100%;height:100%;position:absolute;top:0;background-image:;opacity:1"
                                  id="comp-jpkmxxao3balatabgcoloroverlay" class="bgColoroverlay"></div>
                              </div>
                            </div>
                            <div style="position:relative;left:0;right:0;top:0;bottom:0;width:100%;height:100%"
                              id="comp-jpkmxxao3inlineContentParent" class="style-k0sb3z5zinlineContentParent">
                              <div class="style-k0sb3z5zinlineContent"
                                style="width:100%;position:relative;top:0;bottom:0" id="comp-jpkmxxao3inlineContent">
                                <style id="comp-jpkmxxao3-mesh-styles">
                                  #comp-jpkmxxao3inlineContent {
                                    height: auto;
                                    width: 100%;
                                    position: relative;
                                  }

                                  #comp-jpkmxxao3inlineContent-gridWrapper {
                                    pointer-events: none;
                                  }

                                  #comp-jpkmxxao3inlineContent-gridContainer {
                                    position: static;
                                    display: grid;
                                    height: auto;
                                    width: 100%;
                                    min-height: auto;
                                    grid-template-rows: 1fr;
                                    grid-template-columns: 100%;
                                  }

                                  #comp-jpkmxxz5 {
                                    position: relative;
                                    margin: 8px 0px 31px calc((100% - 726px) * 1);
                                    left: 96px;
                                    grid-area: 1 / 1 / 2 / 2;
                                    justify-self: start;
                                    align-self: start;
                                  }

                                  #comp-jpkmxxap {
                                    position: relative;
                                    margin: 13px 0px 36px calc((100% - 726px) * 1);
                                    left: 685px;
                                    grid-area: 1 / 1 / 2 / 2;
                                    justify-self: start;
                                    align-self: start;
                                  }

                                  #comp-jpkmxxao3centeredContent {
                                    position: relative;
                                  }

                                  #comp-jpkmxxao3inlineContent-gridContainer>* {
                                    pointer-events: auto;
                                  }

                                  #comp-jpkmxxao3inlineContent-gridContainer>[id$="-rotated-wrapper"] {
                                    pointer-events: none;
                                  }

                                  #comp-jpkmxxao3inlineContent-gridContainer>[id$="-rotated-wrapper"]>* {
                                    pointer-events: auto;
                                  }
                                </style>
                                <div id="comp-jpkmxxao3inlineContent-gridWrapper" data-mesh-internal="true">
                                  <div id="comp-jpkmxxao3inlineContent-gridContainer" data-mesh-internal="true">
                                    <div id="comp-jpkmxxz5" class="hidden-during-prewarmup style-k0sb3z5r"
                                      style="overflow-x:hidden;top:;bottom:;left:;right:;width:577px;height:30px;position:"
                                      data-stretch-buttons-to-menu-width="false" data-same-width-buttons="false"
                                      data-num-items="2" data-menuborder-y="0" data-menubtn-border="0"
                                      data-ribbon-els="0" data-label-pad="0" data-ribbon-extra="0" data-drophposition=""
                                      data-dropalign="right" dir="ltr" data-state="right notMobile">
                                      <nav aria-label="Site navigation" id="comp-jpkmxxz5navContainer"
                                        class="style-k0sb3z5rnavContainer">
                                        <ul style="text-align:right" id="comp-jpkmxxz5itemsContainer"
                                          class="style-k0sb3z5ritemsContainer">
                                          <li data-direction="ltr" data-listposition="center"
                                            data-data-id="dataItem-jpkmf79k" class="style-k0sb3z5rrepeaterButton"
                                            data-state="menu selected idle link notMobile" id="comp-jpkmxxz50"><a
                                              aria-haspopup="false" data-listposition="center"
                                              href="https://www.darrylmartin.com" target="_self"
                                              id="comp-jpkmxxz50linkElement"
                                              class="style-k0sb3z5rrepeaterButtonlinkElement">
                                              <div class="style-k0sb3z5rrepeaterButton_gapper">
                                                <div style="text-align:right" id="comp-jpkmxxz50bg"
                                                  class="style-k0sb3z5rrepeaterButtonbg">
                                                  <p style="text-align:right" id="comp-jpkmxxz50label"
                                                    class="style-k0sb3z5rrepeaterButtonlabel">Home</p>
                                                </div>
                                              </div>
                                            </a></li>
                                          <li data-direction="ltr" data-listposition="right"
                                            data-data-id="dataItem-jpkqbr2b" class="style-k0sb3z5rrepeaterButton"
                                            data-state="menu  idle link notMobile" id="comp-jpkmxxz51"><a
                                              aria-haspopup="false" data-listposition="right"
                                              href="https://www.darrylmartin.com/blog" target="_self"
                                              id="comp-jpkmxxz51linkElement"
                                              class="style-k0sb3z5rrepeaterButtonlinkElement">
                                              <div class="style-k0sb3z5rrepeaterButton_gapper">
                                                <div style="text-align:right" id="comp-jpkmxxz51bg"
                                                  class="style-k0sb3z5rrepeaterButtonbg">
                                                  <p style="text-align:right" id="comp-jpkmxxz51label"
                                                    class="style-k0sb3z5rrepeaterButtonlabel">Blog</p>
                                                </div>
                                              </div>
                                            </a></li>

                                        </ul>
                                        <div id="comp-jpkmxxz5moreButton" class="style-k0sb3z5rmoreButton"></div>
                                        <nav style="visibility:visible" data-drophposition="" data-dropalign="right"
                                          id="comp-jpkmxxz5dropWrapper" class="style-k0sb3z5rdropWrapper">
                                          <ul style="visibility:visible" id="comp-jpkmxxz5moreContainer"
                                            class="style-k0sb3z5rmoreContainer"></ul>
                                        </nav>
                                      </nav>
                                    </div>
                                    <div data-is-responsive="false"
                                      style="width:20px;height:20px;top:;bottom:;left:;right:;position:"
                                      data-hide-prejs="false" class="lb1" id="comp-jpkmxxap">
                                      <ul aria-label="Social bar" id="comp-jpkmxxapitemsContainer"
                                        class="lb1itemsContainer">
                                        <li
                                          style="width:20px;height:20px;margin-bottom:0;margin-right:10px;display:inline-block"
                                          class="lb1imageItem" id="comp-jpkmxxap0image"><a
                                            href="https://www.linkedin.com/in/darryl-martin" target="_blank"
                                            data-content="https://www.linkedin.com/in/darryl-martin"
                                            data-type="external" id="comp-jpkmxxap0imagelink" class="lb1imageItemlink">
                                            <wix-image style="width:20px;height:20px;position:absolute" data-has-bg-scroll-effect="" data-image-info="{&quot;imageData&quot;:{&quot;type&quot;:&quot;Image&quot;,&quot;id&quot;:&quot;dataItem-jpkmxxcf1&quot;,&quot;metaData&quot;:{&quot;pageId&quot;:&quot;masterPage&quot;,&quot;isPreset&quot;:false,&quot;schemaVersion&quot;:&quot;1.0&quot;,&quot;isHidden&quot;:false},&quot;title&quot;:&quot;&quot;,&quot;uri&quot;:&quot;6ea5b4a88f0b4f91945b40499aa0af00.png&quot;,&quot;description&quot;:&quot;&quot;,&quot;width&quot;:200,&quot;height&quot;:200,&quot;alt&quot;:&quot;&quot;,&quot;name&quot;:&quot;linkedin&quot;,&quot;link&quot;:{&quot;type&quot;:&quot;ExternalLink&quot;,&quot;id&quot;:&quot;dataItem-jpkmxxcf2&quot;,&quot;metaData&quot;:{&quot;pageId&quot;:&quot;masterPage&quot;,&quot;isPreset&quot;:false,&quot;schemaVersion&quot;:&quot;1.0&quot;,&quot;isHidden&quot;:false},&quot;url&quot;:&quot;https://www.linkedin.com/in/darryl-martin&quot;,&quot;target&quot;:&quot;_blank&quot;},&quot;displayMode&quot;:&quot;fill&quot;},&quot;containerId&quot;:&quot;comp-jpkmxxap&quot;,&quot;displayMode&quot;:&quot;fill&quot;}" data-is-svg="false" id="comp-jpkmxxap0imageimage" class="lb1imageItemimage" data-src="https://static.wixstatic.com/media/6ea5b4a88f0b4f91945b40499aa0af00.png/v1/fill/w_20,h_20,al_c,q_80,usm_0.66_1.00_0.01/linkedin.webp"><img id="comp-jpkmxxap0imageimageimage" alt="" data-type="image" itemprop="image" style="width: 20px; height: 20px; object-fit: cover;" src="https://static.wixstatic.com/media/6ea5b4a88f0b4f91945b40499aa0af00.png/v1/fill/w_20,h_20,al_c,q_80,usm_0.66_1.00_0.01/linkedin.webp"></wix-image>
                                          </a></li>
                                      </ul>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </section>
                  </div>
                </div>
              </div>
            </div>
          </header>
        </div>
      </div>
<!--      <div id="aspectCompsContainer" class="siteAspectsContainer">
        <div style="position:absolute" id="popoverLayer"></div>
        <div style="top:;bottom:;left:;right:;position:;overflow:hidden;visibility:hidden" data-has-iframe="true"
          class="s_DtaksTPAWidgetSkin" id="tpaWorker_11"><iframe
            data-src="https://progallery.wix.com/worker.html?cacheKiller=1572971148273&amp;compId=tpaWorker_11&amp;currency=USD&amp;deviceType=desktop&amp;endpointType=worker&amp;instance=yVct08ZQcrqGEPjtNFpkM947YXrjY6oxKy4gCCccZ7k.eyJpbnN0YW5jZUlkIjoiMmE5ZTY3NzAtNjk3OS00Mjc4LThjOTUtYTM0YThlZWZiZGJhIiwiYXBwRGVmSWQiOiIxNDI3MWQ2Zi1iYTYyLWQwNDUtNTQ5Yi1hYjk3MmFlMWY3MGUiLCJtZXRhU2l0ZUlkIjoiZDk5OTNlMzAtYTcxYy00MmVkLTg5YjItOWNlOWM2NWY1MWY4Iiwic2lnbkRhdGUiOiIyMDE5LTExLTA1VDE2OjM3OjUxLjIwNVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiIxMDIxMmJmMy0zNjdlLTQzMWUtOTRhNy1jMWY5Y2U5MDJhNzAiLCJhaWQiOiIyMDg4MmIxOC0wMzU2LTQwNGYtYmFjZC00ZmRhMjU5Zjk1NDQiLCJiaVRva2VuIjoiZjMwNzU5NDAtY2U2NS0wMDk1LTA1MjctM2ZhMzQ4YjBlYzQyIiwic2l0ZU93bmVySWQiOiIwYjIwOWFlZC0wMGUyLTRiM2EtYjc4Mi0yM2EyZThlMjZjODgifQ&amp;locale=en&amp;siteRevision=129&amp;tz=America%2FLos_Angeles&amp;viewMode=site"
            scrolling="no" frameBorder="0" allow="autoplay; camera; microphone; geolocation; vr"
            allowtransparency="true" allowfullscreen="" name="tpaWorker_11"
            style="display:none;position:absolute;z-index:" title="Wix Pro Gallery" aria-label="Wix Pro Gallery"
            id="tpaWorker_11iframe" class="s_DtaksTPAWidgetSkiniframe"></iframe>
          <div id="tpaWorker_11overlay" class="s_DtaksTPAWidgetSkinoverlay"></div>
        </div>
        <div style="top:;bottom:;left:;right:;position:;overflow:hidden;visibility:" data-has-iframe="true"
          class="s_DtaksTPAWidgetSkin" id="tpaWorker_12"><iframe
            data-src="https://ding.wix.com/asdk/dispatcher.html?cacheKiller=1572971148273&amp;compId=tpaWorker_12&amp;currency=USD&amp;deviceType=desktop&amp;endpointType=worker&amp;instance=ktAQ9gBBotA4CAd5OpoqaWUsdMEpg9r3TYzhzuTRRB0.eyJpbnN0YW5jZUlkIjoiNTQwMWZhZWMtZWIzZS00NDJlLWIxMTAtZGJkOThkMzBhNjRhIiwiYXBwRGVmSWQiOiIxNGJjZGVkNy0wMDY2LTdjMzUtMTRkNy00NjZjYjNmMDkxMDMiLCJtZXRhU2l0ZUlkIjoiZDk5OTNlMzAtYTcxYy00MmVkLTg5YjItOWNlOWM2NWY1MWY4Iiwic2lnbkRhdGUiOiIyMDE5LTExLTA1VDE2OjM3OjUxLjIwNVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiJlZWRkZThkYS04ZjUwLTQxZmUtYTBmZC1mYWRhOWRlOWNmMzUiLCJhaWQiOiIyMDg4MmIxOC0wMzU2LTQwNGYtYmFjZC00ZmRhMjU5Zjk1NDQiLCJiaVRva2VuIjoiOGQ5OGM0ZGMtNGMyMi0wNmMzLTM4YTItNDczMDRiNmZmN2IyIiwic2l0ZU93bmVySWQiOiIwYjIwOWFlZC0wMGUyLTRiM2EtYjc4Mi0yM2EyZThlMjZjODgifQ&amp;locale=en&amp;siteRevision=129&amp;tz=America%2FLos_Angeles&amp;viewMode=site"
            scrolling="no" frameBorder="0" allow="autoplay; camera; microphone; geolocation; vr"
            allowtransparency="true" allowfullscreen="" name="tpaWorker_12"
            style="display:none;position:absolute;z-index:" title="Wix Blog" aria-label="Wix Blog"
            id="tpaWorker_12iframe" class="s_DtaksTPAWidgetSkiniframe"></iframe>
          <div id="tpaWorker_12overlay" class="s_DtaksTPAWidgetSkinoverlay"></div>
        </div>
      </div>
-->      <script id="partiallyVisibleBeat">
        if (window.wixBiSession) {
          wixBiSession.isUsingMesh = true;
        }
      </script>
    </div>
    <div class="font-ruler-container"
      style="overflow:hidden;visibility:hidden;max-height:0;max-width:0;position:absolute">
      <style>
        .font-ruler-content::after {
          content: "@#$%%^&*~IAO"
        }
      </style>
      <div style="position:absolute;overflow:hidden;font-size:1200px;left:-2000px;visibility:hidden">
        <div style="position:relative;white-space:nowrap;font-family:serif">
          <div style="position:absolute;width:100%;height:100%;overflow:hidden">
            <div></div>
          </div><span class="font-ruler-content"></span>
        </div>
      </div>
      <div style="position:absolute;overflow:hidden;font-size:1200px;left:-2000px;visibility:hidden">
        <div style="position:relative;white-space:nowrap;font-family:serif">
          <div style="position:absolute;width:100%;height:100%;overflow:hidden">
            <div></div>
          </div><span class="font-ruler-content"></span>
        </div>
      </div>
      <div style="position:absolute;overflow:hidden;font-size:1200px;left:-2000px;visibility:hidden">
        <div style="position:relative;white-space:nowrap;font-family:serif">
          <div style="position:absolute;width:100%;height:100%;overflow:hidden">
            <div></div>
          </div><span class="font-ruler-content"></span>
        </div>
      </div>
      <div style="position:absolute;overflow:hidden;font-size:1200px;left:-2000px;visibility:hidden">
        <div style="position:relative;white-space:nowrap;font-family:serif">
          <div style="position:absolute;width:100%;height:100%;overflow:hidden">
            <div></div>
          </div><span class="font-ruler-content"></span>
        </div>
      </div>
    </div>
  </div>

  <script type="text/javascript">
    var warmupData = {
      "layoutData": {
        "displayedPagesData": {
          "masterPage": {
            "structure": {
              "DESKTOP": {
                "SITE_FOOTER": {
                  "id": "SITE_FOOTER",
                  "type": "Container",
                  "metaData": {
                    "pageId": "masterPage"
                  },
                  "parent": "masterPage",
                  "componentType": "wysiwyg.viewer.components.FooterContainer",
                  "skin": "wysiwyg.viewer.skins.screenwidthcontainer.TransparentScreen",
                  "connectionQuery": "connection-jq9xa3jx",
                  "layout": {
                    "width": 980,
                    "height": 120,
                    "x": 0,
                    "y": 3140,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "fc1",
                  "components": ["comp-jpkmjxg5"]
                },
                "comp-jpkmjxg5": {
                  "id": "comp-jpkmjxg5",
                  "type": "Container",
                  "metaData": {
                    "pageId": "masterPage"
                  },
                  "parent": "SITE_FOOTER",
                  "componentType": "wysiwyg.viewer.components.StripColumnsContainer",
                  "connectionQuery": "connection-jq9xa3iy",
                  "propertyQuery": "propItem-jpkmjxph",
                  "layout": {
                    "width": 1607,
                    "height": 45,
                    "x": 0,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jpkqr8re2",
                  "styleId": "strc1",
                  "components": ["comp-jpkmjxg51"]
                },
                "SITE_HEADER": {
                  "id": "SITE_HEADER",
                  "type": "Container",
                  "metaData": {
                    "pageId": "masterPage"
                  },
                  "parent": "masterPage",
                  "componentType": "wysiwyg.viewer.components.HeaderContainer",
                  "skin": "wysiwyg.viewer.skins.screenwidthcontainer.TransparentScreen",
                  "connectionQuery": "connection-jq9xa3j7",
                  "layout": {
                    "width": 980,
                    "height": 99,
                    "x": 0,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "hc1",
                  "components": ["comp-jpkmxxao"]
                },
                "comp-jpkmxxao": {
                  "id": "comp-jpkmxxao",
                  "type": "Container",
                  "metaData": {
                    "pageId": "masterPage"
                  },
                  "parent": "SITE_HEADER",
                  "componentType": "wysiwyg.viewer.components.StripColumnsContainer",
                  "skin": "wysiwyg.viewer.skins.stripContainer.DefaultStripContainer",
                  "connectionQuery": "connection-jq9xa3ip",
                  "propertyQuery": "propItem-jpkmxxbx",
                  "layout": {
                    "width": 1487,
                    "height": 69,
                    "x": 0,
                    "y": 30,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jpkqr8re5",
                  "styleId": "strc1",
                  "components": ["comp-jpkmxxao1", "comp-jpkmxxao3"]
                },
                "comp-jpkmjxg51": {
                  "id": "comp-jpkmjxg51",
                  "type": "Container",
                  "metaData": {
                    "pageId": "masterPage"
                  },
                  "parent": "comp-jpkmjxg5",
                  "componentType": "wysiwyg.viewer.components.Column",
                  "connectionQuery": "connection-jq9xa3hy",
                  "propertyQuery": "propItem-jpkmjxpo",
                  "layout": {
                    "width": 980,
                    "height": 45,
                    "x": -1,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jpkmjxpo1",
                  "styleId": "strc1",
                  "components": ["comp-jpkmhymi"]
                },
                "comp-jpkmxxao1": {
                  "id": "comp-jpkmxxao1",
                  "type": "Container",
                  "metaData": {
                    "pageId": "masterPage"
                  },
                  "parent": "comp-jpkmxxao",
                  "componentType": "wysiwyg.viewer.components.Column",
                  "skin": "wysiwyg.viewer.skins.mediaContainer.DefaultMediaContainer",
                  "connectionQuery": "connection-jq9xa3hq",
                  "propertyQuery": "propItem-jpkmxxc2",
                  "layout": {
                    "width": 254,
                    "height": 69,
                    "x": -254,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jpkmxxc21",
                  "styleId": "style-k0sb3z5z",
                  "components": ["comp-jpkmxxao2"]
                },
                "comp-jpkmxxao3": {
                  "id": "comp-jpkmxxao3",
                  "type": "Container",
                  "metaData": {
                    "pageId": "masterPage"
                  },
                  "parent": "comp-jpkmxxao",
                  "componentType": "wysiwyg.viewer.components.Column",
                  "skin": "wysiwyg.viewer.skins.mediaContainer.DefaultMediaContainer",
                  "connectionQuery": "connection-jq9xa3hh",
                  "propertyQuery": "propItem-jpkmxxcb",
                  "layout": {
                    "width": 726,
                    "height": 69,
                    "x": 507,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jpkmxxcb1",
                  "styleId": "style-k0sb3z5z",
                  "components": ["comp-jpkmxxz5", "comp-jpkmxxap"]
                },
                "comp-jpkmxxap": {
                  "id": "comp-jpkmxxap",
                  "type": "Component",
                  "metaData": {
                    "pageId": "masterPage"
                  },
                  "parent": "comp-jpkmxxao3",
                  "componentType": "wysiwyg.viewer.components.LinkBar",
                  "skin": "wysiwyg.viewer.skins.LinkBarNoBGSkin",
                  "dataQuery": "#dataItem-jpkmxxcf",
                  "connectionQuery": "connection-jq9xa3h9",
                  "propertyQuery": "propItem-jpkmxxch",
                  "layout": {
                    "width": 20,
                    "height": 20,
                    "x": 685,
                    "y": 13,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "lb1"
                },
                "comp-jpkmhymi": {
                  "id": "comp-jpkmhymi",
                  "type": "Component",
                  "metaData": {
                    "pageId": "masterPage"
                  },
                  "parent": "comp-jpkmjxg51",
                  "componentType": "wysiwyg.viewer.components.WRichText",
                  "skin": "wysiwyg.viewer.skins.WRichTextNewSkin",
                  "dataQuery": "#dataItem-jpkmhyr3",
                  "connectionQuery": "connection-jq9xa3ig",
                  "propertyQuery": "propItem-jpkmhyr4",
                  "layout": {
                    "width": 376,
                    "height": 25,
                    "x": 302,
                    "y": 10,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "txtNew"
                },
                "comp-jpkmxxao2": {
                  "id": "comp-jpkmxxao2",
                  "type": "Component",
                  "metaData": {
                    "pageId": "masterPage"
                  },
                  "parent": "comp-jpkmxxao1",
                  "componentType": "wysiwyg.viewer.components.WRichText",
                  "skin": "wysiwyg.viewer.skins.WRichTextNewSkin",
                  "dataQuery": "#dataItem-jpkmxxc7",
                  "connectionQuery": "connection-jq9xa3i8",
                  "propertyQuery": "propItem-jpkmxxc71",
                  "layout": {
                    "width": 234,
                    "height": 31,
                    "x": 20,
                    "y": 8,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "txtNew"
                },
                "comp-jpkmxxz5": {
                  "id": "comp-jpkmxxz5",
                  "type": "Component",
                  "metaData": {
                    "pageId": "masterPage"
                  },
                  "parent": "comp-jpkmxxao3",
                  "componentType": "wysiwyg.viewer.components.menus.DropDownMenu",
                  "skin": "wysiwyg.common.components.dropdownmenu.viewer.skins.TextOnlyMenuButtonSkin",
                  "dataQuery": "#dataItem-jpkmxyhl",
                  "connectionQuery": "connection-jq9xa3gz",
                  "propertyQuery": "propItem-jpkmxyhm",
                  "layout": {
                    "width": 577,
                    "height": 30,
                    "x": 96,
                    "y": 8,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "style-k0sb3z5r"
                },
                "SITE_BACKGROUND": {
                  "id": "SITE_BACKGROUND",
                  "metaData": {
                    "pageId": "masterPage"
                  },
                  "parent": "BOLT_SITE",
                  "componentType": "wysiwyg.viewer.components.SiteBackground",
                  "skin": "wysiwyg.viewer.skins.siteBackgroundSkin",
                  "layout": {},
                  "styleId": "siteBackground"
                },
                "masterPage": {
                  "id": "masterPage",
                  "type": "Document",
                  "metaData": {
                    "version": 1,
                    "pageId": "masterPage"
                  },
                  "componentType": "mobile.core.components.MasterPage",
                  "dataQuery": "#masterPage",
                  "layout": {
                    "y": 0,
                    "rotationInDegrees": 0,
                    "anchors": [{
                      "distance": 0,
                      "type": "BOTTOM_TOP",
                      "locked": false,
                      "targetComponent": "PAGES_CONTAINER"
                    }]
                  },
                  "components": ["SITE_FOOTER", "PAGES_CONTAINER", "SITE_HEADER"]
                },
                "PAGES_CONTAINER": {
                  "id": "PAGES_CONTAINER",
                  "type": "Container",
                  "metaData": {
                    "pageId": "masterPage"
                  },
                  "parent": "masterPage",
                  "componentType": "wysiwyg.viewer.components.PagesContainer",
                  "skin": "wysiwyg.viewer.skins.screenwidthcontainer.BlankScreen",
                  "connectionQuery": "connection-jq9xa3jo",
                  "layout": {
                    "width": 980,
                    "height": 3041,
                    "x": 0,
                    "y": 99,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "pc1",
                  "components": ["SITE_PAGES"]
                },
                "SITE_PAGES": {
                  "id": "SITE_PAGES",
                  "type": "Container",
                  "metaData": {
                    "pageId": "masterPage"
                  },
                  "parent": "PAGES_CONTAINER",
                  "componentType": "wysiwyg.viewer.components.PageGroup",
                  "skin": "wysiwyg.viewer.skins.PageGroupSkin",
                  "connectionQuery": "connection-jq9xa3jg",
                  "propertyQuery": "SITE_PAGES",
                  "layout": {
                    "width": 980,
                    "height": 3041,
                    "x": 0,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "components": []
                }
              }
            },
            "data": {
              "behaviors_data": {},
              "connections_data": {},
              "document_data": {
                "masterPage": {
                  "type": "Document",
                  "id": "masterPage",
                  "metaData": {
                    "pageId": "masterPage",
                    "isPreset": true,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "siteName": "Template Base",
                  "mainPage": {
                    "type": "Page",
                    "id": "jqtbi",
                    "metaData": {
                      "pageId": "masterPage",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "title": "Home",
                    "hideTitle": true,
                    "icon": "",
                    "descriptionSEO": "Darryl Martin, experienced director of software engineering, leading web and data processing engineers for 14 years. Passion for solving tough problems, improving processes, expanding technology options, and coordinating people and teams.",
                    "metaKeywordsSEO": "",
                    "pageTitleSEO": "Director of Software Engineering | Alan Darryl Martin | Portland, Ore",
                    "pageUriSEO": "home-1",
                    "hidePage": false,
                    "isMobileLandingPage": false,
                    "underConstruction": false,
                    "tpaApplicationId": 0,
                    "pageSecurity": {
                      "requireLogin": false,
                      "passwordDigest": "",
                      "dialogLanguage": ""
                    },
                    "isPopup": false,
                    "indexable": true,
                    "isLandingPage": false,
                    "pageBackgrounds": {
                      "desktop": {
                        "custom": true,
                        "ref": {
                          "type": "BackgroundMedia",
                          "id": "jqtbi_k0wqhpqw_bg",
                          "metaData": {
                            "pageId": "masterPage",
                            "isPreset": false,
                            "schemaVersion": "2.0",
                            "isHidden": false
                          },
                          "color": "#FAFAFA",
                          "alignType": "center",
                          "fittingType": "fill",
                          "scrollType": "fixed",
                          "colorOverlay": "",
                          "colorOverlayOpacity": 0
                        },
                        "isPreset": true
                      },
                      "mobile": {
                        "custom": true,
                        "ref": {
                          "type": "BackgroundMedia",
                          "id": "jqtbi_mobile_bg",
                          "metaData": {
                            "pageId": "masterPage",
                            "isPreset": false,
                            "schemaVersion": "2.0",
                            "isHidden": false
                          },
                          "color": "#FAFAFA",
                          "alignType": "center",
                          "fittingType": "fill",
                          "scrollType": "fixed",
                          "colorOverlay": "",
                          "colorOverlayOpacity": 0
                        },
                        "isPreset": true,
                        "mediaSizing": "viewport"
                      }
                    },
                    "translationData": {
                      "uriSEOTranslated": false
                    },
                    "advancedSeoData": "{\"tags\":[{\"type\":\"meta\",\"props\":{\"name\":\"keywords\",\"content\":\"My, Portfolio\"},\"custom\":true},{\"type\":\"title\",\"children\":\"Director of Software Engineering | Alan Darryl Martin | Portland, Ore\"},{\"type\":\"meta\",\"props\":{\"name\":\"description\",\"content\":\"Darryl Martin, experienced director of software engineering, leading web and data processing engineers for 14 years. Passion for solving tough problems, improving processes, expanding technology options, and coordinating people and teams.\"}}]}"
                  },
                  "mainPageId": "jqtbi",
                  "renderModifiers": {
                    "pageAutoShrink": true
                  },
                  "characterSets": ["hebrew", "arabic", "latin"],
                  "usedFonts": [],
                  "accessibilitySettings": {
                    "visualFocusDisabled": false
                  },
                  "layoutSettings": {
                    "useDesktopSectionsLayout": true,
                    "mechanism": "mesh",
                    "soapCompsAroundPagesContainer": true
                  },
                  "styleSettings": {
                    "stylesPerPage": "1.0"
                  },
                  "mobileSettings": {
                    "animationsEnabled": false
                  }
                },
                "jqtbi": {
                  "type": "Page",
                  "id": "jqtbi",
                  "metaData": {
                    "pageId": "masterPage",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "title": "Home",
                  "hideTitle": true,
                  "icon": "",
                  "descriptionSEO": "Darryl Martin, experienced director of software engineering, leading web and data processing engineers for 14 years. Passion for solving tough problems, improving processes, expanding technology options, and coordinating people and teams.",
                  "metaKeywordsSEO": "",
                  "pageTitleSEO": "Director of Software Engineering | Alan Darryl Martin | Portland, Ore",
                  "pageUriSEO": "home-1",
                  "hidePage": false,
                  "isMobileLandingPage": false,
                  "underConstruction": false,
                  "tpaApplicationId": 0,
                  "pageSecurity": {
                    "requireLogin": false,
                    "passwordDigest": "",
                    "dialogLanguage": ""
                  },
                  "isPopup": false,
                  "indexable": true,
                  "isLandingPage": false,
                  "pageBackgrounds": {
                    "desktop": {
                      "custom": true,
                      "ref": {
                        "type": "BackgroundMedia",
                        "id": "jqtbi_k0wqhpqw_bg",
                        "metaData": {
                          "pageId": "masterPage",
                          "isPreset": false,
                          "schemaVersion": "2.0",
                          "isHidden": false
                        },
                        "color": "#FAFAFA",
                        "alignType": "center",
                        "fittingType": "fill",
                        "scrollType": "fixed",
                        "colorOverlay": "",
                        "colorOverlayOpacity": 0
                      },
                      "isPreset": true
                    },
                    "mobile": {
                      "custom": true,
                      "ref": {
                        "type": "BackgroundMedia",
                        "id": "jqtbi_mobile_bg",
                        "metaData": {
                          "pageId": "masterPage",
                          "isPreset": false,
                          "schemaVersion": "2.0",
                          "isHidden": false
                        },
                        "color": "#FAFAFA",
                        "alignType": "center",
                        "fittingType": "fill",
                        "scrollType": "fixed",
                        "colorOverlay": "",
                        "colorOverlayOpacity": 0
                      },
                      "isPreset": true,
                      "mediaSizing": "viewport"
                    }
                  },
                  "translationData": {
                    "uriSEOTranslated": false
                  },
                  "advancedSeoData": "{\"tags\":[{\"type\":\"meta\",\"props\":{\"name\":\"keywords\",\"content\":\"My, Portfolio\"},\"custom\":true},{\"type\":\"title\",\"children\":\"Director of Software Engineering | Alan Darryl Martin | Portland, Ore\"},{\"type\":\"meta\",\"props\":{\"name\":\"description\",\"content\":\"Darryl Martin, experienced director of software engineering, leading web and data processing engineers for 14 years. Passion for solving tough problems, improving processes, expanding technology options, and coordinating people and teams.\"}}]}"
                }
              },
              "design_data": {
                "dataItem-jpkqr8re2": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jpkqr8re2",
                  "metaData": {
                    "pageId": "masterPage",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jpkqr8re1",
                    "metaData": {
                      "pageId": "masterPage",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "#FFFFFF",
                    "colorOpacity": 0,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 1
                  }
                },
                "dataItem-jpkqr8re5": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jpkqr8re5",
                  "metaData": {
                    "pageId": "masterPage",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jpkqr8re4",
                    "metaData": {
                      "pageId": "masterPage",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "#FFFFFF",
                    "colorOpacity": 0,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 1
                  }
                },
                "dataItem-jpkmjxpo1": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jpkmjxpo1",
                  "metaData": {
                    "pageId": "masterPage",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jpkmxkjs1",
                    "metaData": {
                      "pageId": "masterPage",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "#FAFAFA",
                    "colorOpacity": 1,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 0,
                    "showOverlayForMediaType": "WixVideo"
                  },
                  "charas": "design-k0wqm4nh",
                  "dataChangeBehaviors": []
                },
                "dataItem-jpkmxxc21": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jpkmxxc21",
                  "metaData": {
                    "pageId": "masterPage",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jpkmxxc22",
                    "metaData": {
                      "pageId": "masterPage",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "",
                    "colorOpacity": 0,
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 0
                  }
                },
                "dataItem-jpkmxxcb1": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jpkmxxcb1",
                  "metaData": {
                    "pageId": "masterPage",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jpkmxxcb2",
                    "metaData": {
                      "pageId": "masterPage",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "",
                    "colorOpacity": 0,
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 0
                  }
                }
              },
              "mobile_hints": {},
              "component_properties": {},
              "breakpoints_data": {},
              "layout_data": {},
              "theme_data": {}
            }
          },
          "jqtbi": {
            "structure": {
              "DESKTOP": {
                "jqtbi": {
                  "id": "jqtbi",
                  "type": "Page",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "componentType": "mobile.core.components.Page",
                  "skin": "wysiwyg.viewer.skins.page.BasicPageSkin",
                  "dataQuery": "#jqtbi",
                  "connectionQuery": "connection-jq9xa3f9",
                  "layout": {
                    "width": 1607,
                    "height": 3418,
                    "x": 0,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "p2",
                  "components": ["comp-jpkn0sgr", "comp-jqg4qgor", "comp-jpkqjpxi", "comp-k0se0v2k", "comp-jpkmjxgi",
                    "comp-jpkmjxgi8"
                  ]
                },
                "comp-jpkn0sgr": {
                  "id": "comp-jpkn0sgr",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "jqtbi",
                  "componentType": "wysiwyg.viewer.components.StripColumnsContainer",
                  "connectionQuery": "connection-jq9xa32m",
                  "propertyQuery": "propItem-jpkn0st8",
                  "layout": {
                    "width": 1607,
                    "height": 164,
                    "x": 0,
                    "y": -31,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jpkqr8rn8",
                  "styleId": "strc1",
                  "components": ["comp-jpkn0sgs"]
                },
                "comp-jqg4qgor": {
                  "id": "comp-jqg4qgor",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "jqtbi",
                  "componentType": "wysiwyg.viewer.components.StripColumnsContainer",
                  "connectionQuery": "connection-jqg4qgwb",
                  "propertyQuery": "propItem-jqg4qgtl",
                  "layout": {
                    "width": 1607,
                    "height": 573,
                    "x": 0,
                    "y": 134,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jqg4qgtr",
                  "styleId": "strc1",
                  "components": ["comp-jqg4qgv8"]
                },
                "comp-jpkqjpxi": {
                  "id": "comp-jpkqjpxi",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "jqtbi",
                  "componentType": "wysiwyg.viewer.components.StripColumnsContainer",
                  "connectionQuery": "connection-jq9xa32a",
                  "propertyQuery": "propItem-jpkqjpxn",
                  "layout": {
                    "width": 1607,
                    "height": 1655,
                    "x": 0,
                    "y": 707,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jpkqr8rn11",
                  "styleId": "strc1",
                  "components": ["comp-jpkqjpxi1"]
                },
                "comp-k0se0v2k": {
                  "id": "comp-k0se0v2k",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "jqtbi",
                  "componentType": "wysiwyg.viewer.components.StripColumnsContainer",
                  "connectionQuery": "connection-k0se0v9n",
                  "propertyQuery": "propItem-k0se0v8w",
                  "layout": {
                    "width": 1607,
                    "height": 456,
                    "x": 0,
                    "y": 2362,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-k0se0v8y",
                  "styleId": "strc1",
                  "components": ["comp-k0se0vaj"]
                },
                "comp-jpkmjxgi": {
                  "id": "comp-jpkmjxgi",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "jqtbi",
                  "componentType": "wysiwyg.viewer.components.StripColumnsContainer",
                  "skin": "wysiwyg.viewer.skins.stripContainer.DefaultStripContainer",
                  "connectionQuery": "connection-jq9xa2za",
                  "propertyQuery": "propItem-jpkmjy1s",
                  "layout": {
                    "width": 1607,
                    "height": 466,
                    "x": 0,
                    "y": 2818,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jpkqr8ro5",
                  "styleId": "strc1",
                  "components": ["comp-jpkmjxgi1", "comp-jpkmjxgi6"]
                },
                "comp-jpkmjxgi8": {
                  "id": "comp-jpkmjxgi8",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "jqtbi",
                  "componentType": "wysiwyg.viewer.components.StripColumnsContainer",
                  "skin": "wysiwyg.viewer.skins.stripContainer.DefaultStripContainer",
                  "connectionQuery": "connection-jq9xa2z1",
                  "propertyQuery": "propItem-jpkmjy3h",
                  "layout": {
                    "width": 1607,
                    "height": 134,
                    "x": 0,
                    "y": 3284,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jpkqr8ro8",
                  "styleId": "strc1",
                  "components": ["comp-jpkmjxgi9"]
                },
                "comp-jpkn0sgs": {
                  "id": "comp-jpkn0sgs",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jpkn0sgr",
                  "componentType": "wysiwyg.viewer.components.Column",
                  "connectionQuery": "connection-jq9xa2y2",
                  "propertyQuery": "propItem-jpkn0sv6",
                  "layout": {
                    "width": 980,
                    "height": 164,
                    "x": -1,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jpkn0sv7",
                  "styleId": "strc1",
                  "components": ["comp-jpkn0sgs1"]
                },
                "comp-jqg4qgv8": {
                  "id": "comp-jqg4qgv8",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jqg4qgor",
                  "componentType": "wysiwyg.viewer.components.Column",
                  "connectionQuery": "connection-jqg4qgw6",
                  "propertyQuery": "propItem-jqg4qgva",
                  "layout": {
                    "width": 980,
                    "height": 573,
                    "x": -1,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jqg4qgvd",
                  "styleId": "mc1",
                  "components": ["comp-jqg4qgvg", "comp-jqg4qgwo", "comp-jqg4qgxd", "comp-k0vpgq0d"]
                },
                "comp-jpkqjpxi1": {
                  "id": "comp-jpkqjpxi1",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jpkqjpxi",
                  "componentType": "wysiwyg.viewer.components.Column",
                  "connectionQuery": "connection-jq9xa2xx",
                  "propertyQuery": "propItem-jpkqjq0m",
                  "layout": {
                    "width": 980,
                    "height": 1655,
                    "x": -1,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jpkqjq0o",
                  "styleId": "strc1",
                  "components": ["comp-jpkqjpxj1", "comp-jpkqjpxj2"]
                },
                "comp-k0se0vaj": {
                  "id": "comp-k0se0vaj",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-k0se0v2k",
                  "componentType": "wysiwyg.viewer.components.Column",
                  "connectionQuery": "connection-k0se0vb91",
                  "propertyQuery": "propItem-k0se0vb6",
                  "layout": {
                    "width": 980,
                    "height": 456,
                    "x": -1,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-k0se0vb7",
                  "styleId": "strc1",
                  "components": ["comp-k0se0vbg"]
                },
                "comp-jpkmjxgi1": {
                  "id": "comp-jpkmjxgi1",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jpkmjxgi",
                  "componentType": "wysiwyg.viewer.components.Column",
                  "skin": "wysiwyg.viewer.skins.mediaContainer.DefaultMediaContainer",
                  "connectionQuery": "connection-jq9xa2ue",
                  "propertyQuery": "propItem-jpkmjy22",
                  "layout": {
                    "width": 490,
                    "height": 466,
                    "x": -158,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jpkmjy221",
                  "styleId": "style-k0sb3z6u",
                  "components": ["comp-jpkmjxgi2", "comp-jpkmjxgi3", "comp-jpkmjxgi4", "comp-jpkmjxgi5"]
                },
                "comp-jpkmjxgi6": {
                  "id": "comp-jpkmjxgi6",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jpkmjxgi",
                  "componentType": "wysiwyg.viewer.components.Column",
                  "skin": "wysiwyg.viewer.skins.mediaContainer.DefaultMediaContainer",
                  "connectionQuery": "connection-jq9xa2u6",
                  "propertyQuery": "propItem-jpkmjy2z",
                  "layout": {
                    "width": 490,
                    "height": 466,
                    "x": 646,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jpkmjy2z1",
                  "styleId": "style-k0sb3z6u",
                  "components": ["comp-jpkmjxgi7"]
                },
                "comp-jpkmjxgi9": {
                  "id": "comp-jpkmjxgi9",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jpkmjxgi8",
                  "componentType": "wysiwyg.viewer.components.Column",
                  "skin": "wysiwyg.viewer.skins.mediaContainer.DefaultMediaContainer",
                  "connectionQuery": "connection-jq9xa2tt",
                  "propertyQuery": "propItem-jpkmjy3s",
                  "layout": {
                    "width": 980,
                    "height": 134,
                    "x": -1,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jpkmjy3s1",
                  "styleId": "style-k0sb3z6u",
                  "components": []
                },
                "comp-jpkn0sgs1": {
                  "id": "comp-jpkn0sgs1",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jpkn0sgs",
                  "componentType": "wysiwyg.viewer.components.WRichText",
                  "skin": "wysiwyg.viewer.skins.WRichTextNewSkin",
                  "dataQuery": "#dataItem-jpkn0svf",
                  "connectionQuery": "connection-jq9xa3cn",
                  "propertyQuery": "propItem-jpkn0svg",
                  "layout": {
                    "width": 780,
                    "height": 54,
                    "x": 100,
                    "y": 71,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "txtNew"
                },
                "comp-jqg4qgvg": {
                  "id": "comp-jqg4qgvg",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jqg4qgv8",
                  "componentType": "wysiwyg.viewer.components.WRichText",
                  "dataQuery": "#dataItem-jqg4qgvg1",
                  "connectionQuery": "connection-jqg4qgw0",
                  "propertyQuery": "propItem-jqg4qgvh",
                  "layout": {
                    "width": 523,
                    "height": 64,
                    "x": 228,
                    "y": 70,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "txtNew"
                },
                "comp-jqg4qgwo": {
                  "id": "comp-jqg4qgwo",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jqg4qgv8",
                  "componentType": "wysiwyg.viewer.components.FiveGridLine",
                  "skin": "wysiwyg.viewer.skins.line.SolidLine",
                  "connectionQuery": "connection-jqg4qgx2",
                  "propertyQuery": "propItem-jqg4qgwp",
                  "layout": {
                    "width": 32,
                    "height": 5,
                    "x": 472,
                    "y": 152,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "style-k0sb3z94"
                },
                "comp-jqg4qgxd": {
                  "id": "comp-jqg4qgxd",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jqg4qgv8",
                  "componentType": "wysiwyg.viewer.components.StripColumnsContainer",
                  "connectionQuery": "connection-jqg4qgzg",
                  "propertyQuery": "propItem-jqg4qgxe",
                  "layout": {
                    "width": 980,
                    "height": 397,
                    "x": 0,
                    "y": 172,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jqg4qgxf",
                  "styleId": "strc1",
                  "components": ["comp-jqg4qgxk", "comp-jqg4qh2x", "comp-jqg4qh81"]
                },
                "comp-k0vpgq0d": {
                  "id": "comp-k0vpgq0d",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jqg4qgv8",
                  "componentType": "wysiwyg.viewer.components.tpapps.TPAWidget",
                  "skin": "wysiwyg.viewer.skins.TPAWidgetSkin",
                  "dataQuery": "#dataItem-k0vpgq3s",
                  "connectionQuery": "connection-k0vpgq4v",
                  "layout": {
                    "width": 980,
                    "height": 353,
                    "x": 949,
                    "y": 160,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "style-k0wq1doe"
                },
                "comp-jpkqjpxj1": {
                  "id": "comp-jpkqjpxj1",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jpkqjpxi1",
                  "componentType": "wysiwyg.viewer.components.WRichText",
                  "skin": "wysiwyg.viewer.skins.WRichTextNewSkin",
                  "dataQuery": "#dataItem-jpkqjq17",
                  "connectionQuery": "connection-jq9xa3bj",
                  "propertyQuery": "propItem-jpkqjq171",
                  "layout": {
                    "width": 921,
                    "height": 1583,
                    "x": 30,
                    "y": 72,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "txtNew"
                },
                "comp-jpkqjpxj2": {
                  "id": "comp-jpkqjpxj2",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jpkqjpxi1",
                  "componentType": "wysiwyg.viewer.components.SiteButton",
                  "skin": "wysiwyg.viewer.skins.button.BasicButton",
                  "dataQuery": "#dataItem-jpkqjq1i",
                  "connectionQuery": "connection-jq9xa3eu",
                  "propertyQuery": "propItem-jpkqjq1i2",
                  "layout": {
                    "width": 250,
                    "height": 45,
                    "x": 724,
                    "y": 129,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "style-k0sb3z86"
                },
                "comp-k0se0vbg": {
                  "id": "comp-k0se0vbg",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-k0se0vaj",
                  "componentType": "wysiwyg.viewer.components.WRichText",
                  "skin": "wysiwyg.viewer.skins.WRichTextNewSkin",
                  "dataQuery": "#dataItem-k0se0vbp",
                  "connectionQuery": "connection-k0se0vbv",
                  "propertyQuery": "propItem-k0se0vbr",
                  "layout": {
                    "width": 921,
                    "height": 413,
                    "x": 30,
                    "y": 16,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "txtNew"
                },
                "comp-jpkmjxgi2": {
                  "id": "comp-jpkmjxgi2",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jpkmjxgi1",
                  "componentType": "wysiwyg.viewer.components.WRichText",
                  "skin": "wysiwyg.viewer.skins.WRichTextNewSkin",
                  "dataQuery": "#dataItem-jpkmjy28",
                  "connectionQuery": "connection-jq9xa349",
                  "propertyQuery": "propItem-jpkmjy281",
                  "layout": {
                    "width": 460,
                    "height": 54,
                    "x": 16,
                    "y": 60,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "txtNew"
                },
                "comp-jpkmjxgi3": {
                  "id": "comp-jpkmjxgi3",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jpkmjxgi1",
                  "componentType": "wysiwyg.viewer.components.WRichText",
                  "skin": "wysiwyg.viewer.skins.WRichTextNewSkin",
                  "dataQuery": "#dataItem-jpkmjy2d",
                  "connectionQuery": "connection-jq9xa343",
                  "propertyQuery": "propItem-jpkmjy2d1",
                  "layout": {
                    "width": 460,
                    "height": 28,
                    "x": 16,
                    "y": 134,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "txtNew"
                },
                "comp-jpkmjxgi4": {
                  "id": "comp-jpkmjxgi4",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jpkmjxgi1",
                  "componentType": "wysiwyg.viewer.components.WRichText",
                  "skin": "wysiwyg.viewer.skins.WRichTextNewSkin",
                  "dataQuery": "#dataItem-jpkmjy2j",
                  "connectionQuery": "connection-jq9xa33y",
                  "propertyQuery": "propItem-jpkmjy2k",
                  "layout": {
                    "width": 460,
                    "height": 28,
                    "x": 16,
                    "y": 182,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "txtNew"
                },
                "comp-jpkmjxgi5": {
                  "id": "comp-jpkmjxgi5",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jpkmjxgi1",
                  "componentType": "wysiwyg.viewer.components.WRichText",
                  "skin": "wysiwyg.viewer.skins.WRichTextNewSkin",
                  "dataQuery": "#dataItem-jpkmjy2o",
                  "connectionQuery": "connection-jq9xa33k",
                  "propertyQuery": "propItem-jpkmjy2p",
                  "layout": {
                    "width": 460,
                    "height": 28,
                    "x": 16,
                    "y": 230,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "txtNew"
                },
                "comp-jpkmjxgi7": {
                  "id": "comp-jpkmjxgi7",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jpkmjxgi6",
                  "componentType": "wysiwyg.viewer.components.DynamicContactForm",
                  "skin": "contactform.LineOnlySkin",
                  "dataQuery": "#dataItem-jpkmjy38",
                  "connectionQuery": "connection-jq9xa33b",
                  "layout": {
                    "width": 460,
                    "height": 406,
                    "x": 16,
                    "y": 60,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "style-k0sb3z7a"
                },
                "comp-jqg4qgxk": {
                  "id": "comp-jqg4qgxk",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jqg4qgxd",
                  "componentType": "wysiwyg.viewer.components.Column",
                  "connectionQuery": "connection-jqg4qgyz",
                  "propertyQuery": "propItem-jqg4qgxr",
                  "layout": {
                    "width": 334,
                    "height": 397,
                    "x": -1,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jqg4qgxr1",
                  "styleId": "mc1",
                  "components": ["comp-jqkcqljp", "comp-jqg4qh0r"]
                },
                "comp-jqg4qh2x": {
                  "id": "comp-jqg4qh2x",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jqg4qgxd",
                  "componentType": "wysiwyg.viewer.components.Column",
                  "connectionQuery": "connection-jqg4qh3t",
                  "propertyQuery": "propItem-jqg4qh2z",
                  "layout": {
                    "width": 323,
                    "height": 397,
                    "x": 333,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jqg4qh30",
                  "styleId": "mc1",
                  "components": ["comp-jqg4qh6j", "comp-jqg4qh4k"]
                },
                "comp-jqg4qh81": {
                  "id": "comp-jqg4qh81",
                  "type": "Container",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jqg4qgxd",
                  "componentType": "wysiwyg.viewer.components.Column",
                  "connectionQuery": "connection-jqg4qh8y",
                  "propertyQuery": "propItem-jqg4qh82",
                  "layout": {
                    "width": 323,
                    "height": 397,
                    "x": 656,
                    "y": 0,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "designQuery": "#dataItem-jqg4qh83",
                  "styleId": "mc1",
                  "components": ["comp-jqkctex3"]
                },
                "comp-jqkcqljp": {
                  "id": "comp-jqkcqljp",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jqg4qgxk",
                  "componentType": "wysiwyg.viewer.components.WRichText",
                  "skin": "wysiwyg.viewer.skins.WRichTextNewSkin",
                  "dataQuery": "#dataItem-jqkcqlm9",
                  "connectionQuery": "connection-jqkcqln1",
                  "propertyQuery": "propItem-jqkcqlp1",
                  "layout": {
                    "width": 131,
                    "height": 38,
                    "x": 28,
                    "y": 46,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "txtNew"
                },
                "comp-jqg4qh0r": {
                  "id": "comp-jqg4qh0r",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jqg4qgxk",
                  "componentType": "wysiwyg.viewer.components.WRichText",
                  "dataQuery": "#dataItem-jqg4qh0r1",
                  "connectionQuery": "connection-jqg4qh1b",
                  "propertyQuery": "propItem-jqg4qh0r2",
                  "layout": {
                    "width": 287,
                    "height": 227,
                    "x": 28,
                    "y": 96,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "txtNew"
                },
                "comp-jqg4qh6j": {
                  "id": "comp-jqg4qh6j",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jqg4qh2x",
                  "componentType": "wysiwyg.viewer.components.WPhoto",
                  "skin": "wysiwyg.viewer.skins.photo.CirclePhoto",
                  "dataQuery": "#dataItem-jqg4qh6k",
                  "connectionQuery": "connection-jqg4qh75",
                  "propertyQuery": "propItem-jqg4qh6k1",
                  "layout": {
                    "width": 189,
                    "height": 217,
                    "x": 69,
                    "y": 46,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "style-k0sb3z8k"
                },
                "comp-jqg4qh4k": {
                  "id": "comp-jqg4qh4k",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jqg4qh2x",
                  "componentType": "wysiwyg.viewer.components.LinkBar",
                  "skin": "wysiwyg.viewer.skins.LinkBarNoBGSkin",
                  "dataQuery": "#dataItem-jqg4qh4l",
                  "connectionQuery": "connection-jqg4qh56",
                  "propertyQuery": "propItem-jqg4qh4l3",
                  "layout": {
                    "width": 42,
                    "height": 42,
                    "x": 142,
                    "y": 292,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "lb1"
                },
                "comp-jqkctex3": {
                  "id": "comp-jqkctex3",
                  "type": "Component",
                  "metaData": {
                    "pageId": "jqtbi"
                  },
                  "parent": "comp-jqg4qh81",
                  "componentType": "wysiwyg.viewer.components.WRichText",
                  "skin": "wysiwyg.viewer.skins.WRichTextNewSkin",
                  "dataQuery": "#dataItem-jqkcteyr",
                  "connectionQuery": "connection-jqkcteys",
                  "propertyQuery": "propItem-jqkcteyr1",
                  "layout": {
                    "width": 240,
                    "height": 245,
                    "x": 27,
                    "y": 46,
                    "scale": 1,
                    "rotationInDegrees": 0,
                    "fixedPosition": false
                  },
                  "styleId": "txtNew"
                }
              }
            },
            "data": {
              "behaviors_data": {},
              "connections_data": {},
              "document_data": {
                "dataItem-jqg4qh6k": {
                  "type": "Image",
                  "id": "dataItem-jqg4qh6k",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "2.0",
                    "isHidden": false
                  },
                  "title": "headshot.jpg",
                  "uri": "0b209a_25b630b75f6449f3bc3a92c8cc5768a1~mv2_d_2248_2582_s_2.jpg",
                  "description": "",
                  "width": 2248,
                  "height": 2582,
                  "alt": "IMG_20190101_211526840_BURST000_COVER-b.",
                  "name": "IMG_20190101_211526840_BURST000_COVER-b.",
                  "displayMode": "fill"
                },
                "dataItem-k0vpgq3s": {
                  "type": "TPAWidget",
                  "id": "dataItem-k0vpgq3s",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "applicationId": "12",
                  "appDefinitionId": "14bcded7-0066-7c35-14d7-466cb3f09103",
                  "widgetId": "14e5b36b-e545-88a0-1475-2487df7e9206"
                }
              },
              "design_data": {
                "dataItem-jpkmjy221": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jpkmjy221",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jpkmjy222",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "",
                    "colorOpacity": 0,
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 0
                  }
                },
                "dataItem-jpkmjy2z1": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jpkmjy2z1",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jpkmjy2z2",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "",
                    "colorOpacity": 0,
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 0
                  }
                },
                "dataItem-jpkmjy3s1": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jpkmjy3s1",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jpkmjy3t",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "mediaRef": {
                      "type": "Image",
                      "id": "dataItem-jqg3nwei1",
                      "metaData": {
                        "pageId": "jqtbi",
                        "isPreset": false,
                        "schemaVersion": "1.0",
                        "isHidden": false
                      },
                      "title": "crystal-wallpaper-2.jpg",
                      "uri": "0b209a_d2beceef03db49be997817a879d6fc1f~mv2.jpg",
                      "description": "private\/6b785ff3ed5246f7bfdc1437fcf34527",
                      "width": 1366,
                      "height": 768,
                      "alt": "",
                      "artist": {
                        "id": "",
                        "name": ""
                      }
                    },
                    "color": "",
                    "colorOpacity": 0,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 0,
                    "showOverlayForMediaType": "WixVideo"
                  },
                  "charas": "design-jqg3nwei",
                  "dataChangeBehaviors": []
                },
                "dataItem-jpkn0sv7": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jpkn0sv7",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jpkn0sv71",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "mediaRef": {
                      "type": "Image",
                      "id": "dataItem-jqg2jtnf1",
                      "metaData": {
                        "pageId": "jqtbi",
                        "isPreset": false,
                        "schemaVersion": "1.0",
                        "isHidden": false
                      },
                      "title": "Circuit4.jpg",
                      "uri": "0b209a_10feb1067c234e2ebc1e5eae8094838e~mv2.jpg",
                      "description": "private\/6b785ff3ed5246f7bfdc1437fcf34527",
                      "width": 1366,
                      "height": 768,
                      "alt": "",
                      "artist": {
                        "id": "",
                        "name": ""
                      }
                    },
                    "color": "{color_15}",
                    "colorOpacity": 1,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 0,
                    "showOverlayForMediaType": "WixVideo"
                  },
                  "charas": "design-jqg2jtnf",
                  "dataChangeBehaviors": []
                },
                "dataItem-jpkqjq0o": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jpkqjq0o",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jpkqjq0o1",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "{color_17}",
                    "colorOpacity": 1,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 0,
                    "showOverlayForMediaType": "WixVideo"
                  },
                  "charas": "design-jqg3ja2v",
                  "dataChangeBehaviors": []
                },
                "dataItem-jpkqr8rn11": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jpkqr8rn11",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jpkqr8rn10",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "#FFFFFF",
                    "colorOpacity": 0,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 1
                  }
                },
                "dataItem-jpkqr8rn8": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jpkqr8rn8",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jpkqr8rn7",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "#FFFFFF",
                    "colorOpacity": 0,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 1
                  }
                },
                "dataItem-jpkqr8ro5": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jpkqr8ro5",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jpkqr8ro4",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "#FFFFFF",
                    "colorOpacity": 0,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 1
                  }
                },
                "dataItem-jpkqr8ro8": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jpkqr8ro8",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jpkqr8ro7",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "#FFFFFF",
                    "colorOpacity": 0,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 1
                  }
                },
                "dataItem-jqg4qgtr": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jqg4qgtr",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jqg4qgtt",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "#FFFFFF",
                    "colorOpacity": 0,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 1
                  }
                },
                "dataItem-jqg4qgvd": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jqg4qgvd",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jqg4qgve",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "#FAFAFA",
                    "colorOpacity": 1,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 0
                  }
                },
                "dataItem-jqg4qgxf": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jqg4qgxf",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jqg4qgxf1",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "#FFFFFF",
                    "colorOpacity": 0,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 1
                  }
                },
                "dataItem-jqg4qgxr1": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jqg4qgxr1",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jqg4qgxr2",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "#FFFFFF",
                    "colorOpacity": 0,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 1
                  }
                },
                "dataItem-jqg4qh30": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jqg4qh30",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jqg4qh31",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "#FFFFFF",
                    "colorOpacity": 0,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 1
                  }
                },
                "dataItem-jqg4qh83": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-jqg4qh83",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-jqg4qh831",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "#FFFFFF",
                    "colorOpacity": 0,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 1
                  }
                },
                "dataItem-k0se0v8y": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-k0se0v8y",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-k0se0v8z",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "#FFFFFF",
                    "colorOpacity": 0,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 1
                  }
                },
                "dataItem-k0se0vb7": {
                  "type": "MediaContainerDesignData",
                  "id": "dataItem-k0se0vb7",
                  "metaData": {
                    "pageId": "jqtbi",
                    "isPreset": false,
                    "schemaVersion": "1.0",
                    "isHidden": false
                  },
                  "background": {
                    "type": "BackgroundMedia",
                    "id": "dataItem-k0se0vb8",
                    "metaData": {
                      "pageId": "jqtbi",
                      "isPreset": false,
                      "schemaVersion": "1.0",
                      "isHidden": false
                    },
                    "color": "{color_17}",
                    "colorOpacity": 1,
                    "alignType": "center",
                    "fittingType": "fill",
                    "scrollType": "none",
                    "colorOverlay": "",
                    "colorOverlayOpacity": 0,
                    "showOverlayForMediaType": "WixVideo"
                  },
                  "charas": "design-jqg3ja2v",
                  "dataChangeBehaviors": []
                }
              },
              "mobile_hints": {},
              "component_properties": {},
              "breakpoints_data": {},
              "layout_data": {},
              "theme_data": {}
            }
          }
        },
        "anchorsMap": null,
        "ssr": {
          "shouldRenderPage": true,
          "aspectsComponentStructures": {
            "POPOVER_LAYER": {
              "componentType": "PopoverLayer",
              "metaData": {
                "pageId": "PopoverAspect"
              },
              "layout": {},
              "parent": "aspectCompsContainer"
            },
            "tpaWorker_11": {
              "componentType": "tpa.viewer.classes.TPAWorker",
              "skin": "wysiwyg.viewer.skins.TPAWidgetSkin",
              "type": "Component",
              "id": "tpaWorker_11",
              "metaData": {
                "pageId": "tpaPostMessageAspect"
              },
              "layout": {},
              "parent": "aspectCompsContainer"
            },
            "tpaWorker_12": {
              "componentType": "tpa.viewer.classes.TPAWorker",
              "skin": "wysiwyg.viewer.skins.TPAWidgetSkin",
              "type": "Component",
              "id": "tpaWorker_12",
              "metaData": {
                "pageId": "tpaPostMessageAspect"
              },
              "layout": {},
              "parent": "aspectCompsContainer"
            }
          }
        },
        "currentUrl": {
          "full": "https:\/\/www.darrylmartin.com",
          "protocol": "https:",
          "host": "www.darrylmartin.com",
          "hostname": "www.darrylmartin.com",
          "port": "",
          "path": "\/",
          "search": "",
          "hash": "",
          "query": {}
        },
        "isMobileView": false,
        "siteMemberDetails": null,
        "isPageAllowed": true,
        "browserFlags": {
          "highlightAnchorsInMenu": true,
          "fixedSiteBackground": true,
          "animateRevealScrubAction": false,
          "animateParallaxScrubAction": false,
          "animateTinyMenuIcon": true,
          "preserve3DParallaxScrubAction": true,
          "fixedBackgroundColorBalata": true,
          "forceOverflowScroll": false,
          "doubleResetMobileViewport": false,
          "shouldDisableSmoothScrolling": true,
          "mixBlendModeSupported": true,
          "cssGridSupported": true,
          "svgImageOnLoadEvent": true,
          "cssFiltersSupported": true,
          "webpImageSupported": true,
          "webglCrossOriginSupported": true,
          "webglVideoTextureSupported": true
        }
      },
      "svgShapes": {
        "3d84bae5ad4d4d8a96de15e9f4b79a08.svg": {
          "content": "<svg data-bbox=\"0 0 50 50\" data-type=\"shape\" xmlns=\"http:\/\/www.w3.org\/2000\/svg\" width=\"50\" height=\"50\" viewBox=\"0 0 50 50\">\n    <g>\n        <path d=\"M25 48.077c-5.924 0-11.31-2.252-15.396-5.921 2.254-5.362 7.492-8.267 15.373-8.267 7.889 0 13.139 3.044 15.408 8.418-4.084 3.659-9.471 5.77-15.385 5.77m.278-35.3c4.927 0 8.611 3.812 8.611 8.878 0 5.21-3.875 9.456-8.611 9.456s-8.611-4.246-8.611-9.456c0-5.066 3.684-8.878 8.611-8.878M25 0C11.193 0 0 11.193 0 25c0 .915.056 1.816.152 2.705.032.295.091.581.133.873.085.589.173 1.176.298 1.751.073.338.169.665.256.997.135.515.273 1.027.439 1.529.114.342.243.675.37 1.01.18.476.369.945.577 1.406.149.331.308.657.472.98.225.446.463.883.714 1.313.182.312.365.619.56.922.272.423.56.832.856 1.237.207.284.41.568.629.841.325.408.671.796 1.02 1.182.22.244.432.494.662.728.405.415.833.801 1.265 1.186.173.154.329.325.507.475l.004-.011A24.886 24.886 0 0 0 25 50a24.881 24.881 0 0 0 16.069-5.861.126.126 0 0 1 .003.01c.172-.144.324-.309.49-.458.442-.392.88-.787 1.293-1.209.228-.232.437-.479.655-.72.352-.389.701-.78 1.028-1.191.218-.272.421-.556.627-.838.297-.405.587-.816.859-1.24a26.104 26.104 0 0 0 1.748-3.216c.208-.461.398-.93.579-1.406.127-.336.256-.669.369-1.012.167-.502.305-1.014.44-1.53.087-.332.183-.659.256-.996.126-.576.214-1.164.299-1.754.042-.292.101-.577.133-.872.095-.89.152-1.791.152-2.707C50 11.193 38.807 0 25 0\"\/>\n    <\/g>\n<\/svg>\n",
          "info": {
            "svgType": "shape",
            "viewBox": "0 0 50 50",
            "bbox": "0 0 50 50"
          },
          "boxBoundaries": {}
        }
      },
      "animationData": {},
      "rootNavigationInfo": {
        "format": "slash",
        "pageId": "jqtbi",
        "title": "home-1"
      },
      "currentUrl": {
        "full": "https:\/\/www.darrylmartin.com",
        "protocol": "https:",
        "host": "www.darrylmartin.com",
        "hostname": "www.darrylmartin.com",
        "port": "",
        "path": "\/",
        "search": "",
        "hash": "",
        "query": {}
      },
      "userWarmup": {},
      "runtime": {
        "data": {
          "behaviors_data": {},
          "connections_data": {},
          "document_data": {},
          "design_data": {},
          "mobile_hints": {},
          "component_properties": {},
          "breakpoints_data": {},
          "layout_data": {},
          "theme_data": {}
        },
        "state": {}
      },
      "wixappsCoreWarmup": {
        "appbuilder": {},
        "faq": {},
        "news": {},
        "menu": {},
        "blog": {}
      },
      "wixappsClassicsWarmup": {
        "warmup": {
          "failedRequests": {}
        },
        "metadata": {
          "items": {},
          "descriptor": {},
          "isCategoriesLoaded": false,
          "videoThumbnails": {}
        }
      },
      "listBuilderWarmup": {
        "warmup": {
          "requestFailed": false
        },
        "metadata": {
          "items": {}
        }
      },
      "tpaWidgetNativeInitData": {},
      "externalScripts": {},
      "seoDebugInfo": []
    };
  </script>

  <!-- No Footer -->

  <!--body end html embeds start-->

  <!--body end html embeds end-->

  <script type="text/javascript">
    var timeSpentInSSR = 499;
  </script>

  <script type="text/javascript">
    var ssrInfo = {
      "timeSpentInSSR": 499,
      "platformOnPage": true,
      "workerStarted": true,
      "platformAppsOnPage": ["675bbcef-18d8-41f5-800e-131ec9e08762"],
      "userCode": true,
      "useBoltush": false,
      "sessionId": "e6dc90ba-bde3-41bd-96d6-206f77adaa20",
      "cacheExclusionReason": "User Code"
    };
  </script>

</body>

</html>
