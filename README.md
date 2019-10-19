```html
<!DOCTYPE html>
<!-- saved from url=(0065)https://www.hackerrank.com/test/3fmff7cgcpe/questions/46hcjfcfs00 -->
<html style="--font-family-text:OpenSans, Arial, Helvetica, sans-serif; --font-family-input:SourceCodePro, monaco, Courier, monospace;"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <script type="text/javascript" data-cfasync="false" charset="UTF-8" async="" defer="" src="./HackerRank_files/auryc.lib.js.download"></script><script type="text/javascript" async="" src="./HackerRank_files/analytics.js.download"></script><script type="text/javascript" async="" src="./HackerRank_files/gtm.js.download"></script><script async="" src="./HackerRank_files/gtm.js(1).download"></script><script>
            (function headInitializer() {
        var dataLayerObject = {
          company_unique_id: 'gitea4l77fa',
          test_unique_id: '3fmff7cgcpe'
        };
                  dataLayerObject['gaUserId'] = '19d3ce9b2d009aff630f4e4382794d3ff5d2f4c2'
          dataLayerObject['attempt_id'] = 11409770
                window.dataLayer = [dataLayerObject];
        window.userAgent = {"family":"Chrome","major":"77","minor":"0","patch":"3865","device":{"family":"Other","major":"0","minor":"0","patch":"0"},"os":{"family":"Windows","major":"10","minor":"0","patch":"0"}};
      })();
    </script>

    
    
    
    <link rel="dns-prefetch" href="https://cdn.userty.com/">
    <script>
      //HR namespace
      HR = window.HR || {};
      HR.enable_auryc = true;
      HR.auryc_container = 'https://cdn.userty.com/207-hackerrankcom/container.js';
    </script>
    

      
  
  <title> HackerRank </title><meta name="description" id="meta-description" content="Join over 5 million developers in solving code challenges on HackerRank, one of the best ways to prepare for programming interviews."><meta property="og:title" id="meta-og-title" content="HackerRank"><meta property="og:image" id="meta-og-image" content="https://hrcdn.net/og/default.jpg"><meta property="og:description" id="meta-og-description" content="Join over 5 million developers in solving code challenges on HackerRank, one of the best ways to prepare for programming interviews."><meta property="og:site_name" id="meta-og-site" content="HackerRank"><meta property="og:type" id="meta-og-type" content="website"><meta property="article:author" content="https://www.facebook.com/hackerrank"><meta name="twitter:card" id="meta-twitter-card" content="summary"><meta name="twitter:site" id="meta-twitter-site" content="@hackerrank"><meta name="twitter:title" id="meta-twitter-title" content="HackerRank"><meta property="fb:app_id" id="meta-fb-id" content="347499128655783"><meta content="authenticity_token" name="csrf-param" id="csrf-param"><meta content="pu28O+TwghAvxlnlez5mS1jUPD2PbPVg+EXnMSAnO29bxJ/iuEjkbxQpfkaqoB2n2pHug/5h6ike3xQQ57LooA==" name="csrf-token" id="csrf-token">
  <script>
    window.BACKEND_ENDPOINT = 'https://www.hackerrank.com/';
    window.MANIFEST_VERSION = '26cf25f680';
  </script>

  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="icon" type="image/png" href="https://hrcdn.net/candidate-site/assets/favicon-62bdd46faf.png">

  <!-- Prefetch dns on production -->
  
    <link rel="dns-prefetch" href="https://hrcdn.net/">
    <link rel="dns-prefetch" href="https://d3keuzeb2crhkn.cloudfront.net/">
    <link rel="dns-prefetch" href="https://notifications.hackerrank.com/">
    <link rel="dns-prefetch" href="https://api.mixpanel.com/">
    <link rel="dns-prefetch" href="https://metrics.hackerrank.com/">
  

  
    <link rel="stylesheet" type="text/css" href="./HackerRank_files/hackerrank_r_modules_app-a75e6e3b.css"><link rel="stylesheet" href="./HackerRank_files/hackerrank_r_modules_app-a75e6e3b.css"><link rel="stylesheet" href="./HackerRank_files/hackerrank_r_modules_app-a75e6e3b.css">
  
    <link rel="stylesheet" type="text/css" href="./HackerRank_files/hackerrank_r_app-b14245ed.css">
  
    <link rel="stylesheet" type="text/css" href="./HackerRank_files/hackerrank_r_modules_login_view_testbase_instructions_coding_question_view_frontend_question_view_test_case_ui-888b272e.css">
  
    <link rel="stylesheet" type="text/css" href="./HackerRank_files/hackerrank_r_modules_login_view_testbase_questionlist_basequestion_coding_question_view_rba_question_view-645524ab.css">
  
    <link rel="stylesheet" type="text/css" href="./HackerRank_files/hackerrank_r_modules_login_view_testbase-5d7d0115.css">
  
    <link rel="stylesheet" type="text/css" href="./HackerRank_files/hackerrank_r_modules_testbase-2f1123d9.css">
  
    <link rel="stylesheet" type="text/css" href="./HackerRank_files/hackerrank_r_commons_login_view_testbase_subjective_question_view_diagram_question_view-36ac7024.css">
  
    <link rel="stylesheet" type="text/css" href="./HackerRank_files/hackerrank_r_commons_login_view_testbase-016a296c.css">
  
    <link rel="stylesheet" type="text/css" href="./HackerRank_files/testbase-da166dd5.css">
  
    <link rel="stylesheet" type="text/css" href="./HackerRank_files/hackerrank_r_modules_login_view_testbase_questionlist_basequestion_coding_question_view_rba_question_view-645524ab.css">
  
    <link rel="stylesheet" type="text/css" href="./HackerRank_files/questionlist-adb0bb4e.css">
  

  <!-- Prefetch / preload assets on production -->
  

    <!-- preload scripts required on the same page -->
    <link rel="preload" as="script" href="./HackerRank_files/hackerrank_r_vendor-377deede8f.js.download">
    <link rel="preload" as="script" href="./HackerRank_files/hackerrank_r_client-78526b5f.js.download">
    <link rel="preload" as="script" href="./HackerRank_files/runtime-a4ab5b9c.js.download">

    
      <link rel="preload" as="script" href="./HackerRank_files/hackerrank_r_app-83555e64.js.download">
    
      <link rel="preload" as="script" href="./HackerRank_files/hackerrank_r_modules_app-f1f971d3.js.download">
    
      <link rel="preload" as="script" href="./HackerRank_files/hackerrank_r_vendors_app-37cfd9e0.js.download">
    
      <link rel="preload" as="script" href="./HackerRank_files/hackerrank_r_modules_login_view_testbase_instructions_coding_question_view_frontend_question_view_test_case_ui-12058fa1.js.download">
    
      <link rel="preload" as="script" href="./HackerRank_files/hackerrank_r_modules_login_view_testbase_questionlist_basequestion_coding_question_view_rba_question_view-88024da9.js.download">
    
      <link rel="preload" as="script" href="./HackerRank_files/hackerrank_r_commons_login_view_testbase_subjective_question_view_diagram_question_view-9d374937.js.download">
    
      <link rel="preload" as="script" href="./HackerRank_files/hackerrank_r_commons_login_view_testbase-71765ea3.js.download">
    
      <link rel="preload" as="script" href="./HackerRank_files/hackerrank_r_modules_login_view_testbase-ad4c2f8e.js.download">
    
      <link rel="preload" as="script" href="./HackerRank_files/hackerrank_r_modules_testbase-4f4995b6.js.download">
    
      <link rel="preload" as="script" href="./HackerRank_files/testbase-bbe23c51.js.download">
    
      <link rel="preload" as="script" href="./HackerRank_files/hackerrank_r_modules_login_view_testbase_questionlist_basequestion_coding_question_view_rba_question_view-88024da9.js.download">
    
      <link rel="preload" as="script" href="./HackerRank_files/questionlist-95c95142.js.download">
    
    <!-- preload scripts end -->

  

  <!-- Load promise polyfill for the non-believers -->
  <script>
    (window.Promise && window.Promise.prototype.finally) || document.write('<script src="https://hrcdn.net/candidate-site/assets/polyfill-d05a380d50.min.js" type="text\/javascript"><\/script>');
  </script>
  <!-- Added for GTM and sentry -->
  

<script>
  window.dataLayer = window.dataLayer || [];
</script>


<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-PBPFQ7N');</script>




<script>
  var errorQueue = [];
  (function(window) {
    function errorListener(event) {
      if (event.type === 'unhandledrejection' && !event.reason) {
        return;
      }
      errorQueue.push(event);
    }
    window.addEventListener('error', errorListener);
    window.addEventListener('unhandledrejection', errorListener);
    window.removeInitialErrorListeners = function() {
      window.removeEventListener('error', errorListener);
      window.removeEventListener('unhandledrejection', errorListener);
    };
    window.getSentryConfig = function () {
      return {
        token: "76b68c9f9470440faa544a0602206fe9",
        projectID: "1393856",
      };
    };
  })(window);
</script>


  <script charset="utf-8" src="./HackerRank_files/hackerrank_r_modules_app-f1f971d3.js.download"></script><script charset="utf-8" src="./HackerRank_files/hackerrank_r_vendors_app-37cfd9e0.js.download"></script><script charset="utf-8" src="./HackerRank_files/hackerrank_r_app-83555e64.js.download"></script><script src="./HackerRank_files/container.js.download" async="" defer="" data-cfasync="false" data-role="container" data-vendor="userty"></script><script charset="utf-8" src="./HackerRank_files/hackerrank_r_modules_login_view_testbase_questionlist_basequestion_coding_question_view_rba_question_view-88024da9.js.download"></script><script charset="utf-8" src="./HackerRank_files/hackerrank_r_modules_login_view_testbase_instructions_coding_question_view_frontend_question_view_test_case_ui-12058fa1.js.download"></script><script charset="utf-8" src="./HackerRank_files/hackerrank_r_modules_login_view_testbase-ad4c2f8e.js.download"></script><script charset="utf-8" src="./HackerRank_files/hackerrank_r_modules_testbase-4f4995b6.js.download"></script><script charset="utf-8" src="./HackerRank_files/hackerrank_r_commons_login_view_testbase_subjective_question_view_diagram_question_view-9d374937.js.download"></script><script charset="utf-8" src="./HackerRank_files/hackerrank_r_commons_login_view_testbase-71765ea3.js.download"></script><script charset="utf-8" src="./HackerRank_files/testbase-bbe23c51.js.download"></script><script charset="utf-8" src="./HackerRank_files/questionlist-95c95142.js.download"></script><style>
html.scroll-hidden,html.scroll-hidden body{
  overflow: hidden;
  height:100vh;
}
html.scroll-hidden.pad-adjustment body{
    padding-right : 19px;
}
html.scroll-hidden.pad-adjustment .fixed-elm{
    padding-right : 19px;
}</style><script charset="utf-8" src="./HackerRank_files/lib_offlinejs-4c4ca9a2.js.download"></script><style id="auryc_style">@charset "UTF-8";@font-face{font-family:AurycFontAwesome;font-weight:400;font-style:normal;src:url(//cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.eot);src:url(//cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.eot#iefix) format("embedded-opentype"),url(//cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.ttf) format("truetype"),url(//cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.woff) format("woff"),url(//cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.woff2) format("woff2"),url(//cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/fonts/fontawesome-webfont.svg#fontawesomeregular) format("svg")}@font-face{font-family:Open Sans;font-style:normal;font-weight:400;src:local("Open Sans Regular"),local("OpenSans-Regular"),url(https://fonts.gstatic.com/s/opensans/v17/mem8YaGs126MiZpBA-UFWJ0bf8pkAp6a.woff2) format("woff2");unicode-range:u+0460-052f,u+1c80-1c88,u+20b4,u+2de0-2dff,u+a640-a69f,u+fe2e-fe2f}@font-face{font-family:Open Sans;font-style:normal;font-weight:400;src:local("Open Sans Regular"),local("OpenSans-Regular"),url(https://fonts.gstatic.com/s/opensans/v17/mem8YaGs126MiZpBA-UFUZ0bf8pkAp6a.woff2) format("woff2");unicode-range:u+0400-045f,u+0490-0491,u+04b0-04b1,u+2116}@font-face{font-family:Open Sans;font-style:normal;font-weight:400;src:local("Open Sans Regular"),local("OpenSans-Regular"),url(https://fonts.gstatic.com/s/opensans/v17/mem8YaGs126MiZpBA-UFWZ0bf8pkAp6a.woff2) format("woff2");unicode-range:u+1f??}@font-face{font-family:Open Sans;font-style:normal;font-weight:400;src:local("Open Sans Regular"),local("OpenSans-Regular"),url(https://fonts.gstatic.com/s/opensans/v17/mem8YaGs126MiZpBA-UFVp0bf8pkAp6a.woff2) format("woff2");unicode-range:u+0370-03ff}@font-face{font-family:Open Sans;font-style:normal;font-weight:400;src:local("Open Sans Regular"),local("OpenSans-Regular"),url(https://fonts.gstatic.com/s/opensans/v17/mem8YaGs126MiZpBA-UFWp0bf8pkAp6a.woff2) format("woff2");unicode-range:u+0102-0103,u+0110-0111,u+1ea0-1ef9,u+20ab}@font-face{font-family:Open Sans;font-style:normal;font-weight:400;src:local("Open Sans Regular"),local("OpenSans-Regular"),url(https://fonts.gstatic.com/s/opensans/v17/mem8YaGs126MiZpBA-UFW50bf8pkAp6a.woff2) format("woff2");unicode-range:u+0100-024f,u+0259,u+1e??,u+2020,u+20a0-20ab,u+20ad-20cf,u+2113,u+2c60-2c7f,u+a720-a7ff}@font-face{font-family:Open Sans;font-style:normal;font-weight:400;src:local("Open Sans Regular"),local("OpenSans-Regular"),url(https://fonts.gstatic.com/s/opensans/v17/mem8YaGs126MiZpBA-UFVZ0bf8pkAg.woff2) format("woff2");unicode-range:u+00??,u+0131,u+0152-0153,u+02bb-02bc,u+02c6,u+02da,u+02dc,u+2000-206f,u+2074,u+20ac,u+2122,u+2191,u+2193,u+2212,u+2215,u+feff,u+fffd}@font-face{font-family:Open Sans;font-style:normal;font-weight:600;src:local("Open Sans SemiBold"),local("OpenSans-SemiBold"),url(https://fonts.gstatic.com/s/opensans/v17/mem5YaGs126MiZpBA-UNirkOX-hpKKSTj5PW.woff2) format("woff2");unicode-range:u+0460-052f,u+1c80-1c88,u+20b4,u+2de0-2dff,u+a640-a69f,u+fe2e-fe2f}@font-face{font-family:Open Sans;font-style:normal;font-weight:600;src:local("Open Sans SemiBold"),local("OpenSans-SemiBold"),url(https://fonts.gstatic.com/s/opensans/v17/mem5YaGs126MiZpBA-UNirkOVuhpKKSTj5PW.woff2) format("woff2");unicode-range:u+0400-045f,u+0490-0491,u+04b0-04b1,u+2116}@font-face{font-family:Open Sans;font-style:normal;font-weight:600;src:local("Open Sans SemiBold"),local("OpenSans-SemiBold"),url(https://fonts.gstatic.com/s/opensans/v17/mem5YaGs126MiZpBA-UNirkOXuhpKKSTj5PW.woff2) format("woff2");unicode-range:u+1f??}@font-face{font-family:Open Sans;font-style:normal;font-weight:600;src:local("Open Sans SemiBold"),local("OpenSans-SemiBold"),url(https://fonts.gstatic.com/s/opensans/v17/mem5YaGs126MiZpBA-UNirkOUehpKKSTj5PW.woff2) format("woff2");unicode-range:u+0370-03ff}@font-face{font-family:Open Sans;font-style:normal;font-weight:600;src:local("Open Sans SemiBold"),local("OpenSans-SemiBold"),url(https://fonts.gstatic.com/s/opensans/v17/mem5YaGs126MiZpBA-UNirkOXehpKKSTj5PW.woff2) format("woff2");unicode-range:u+0102-0103,u+0110-0111,u+1ea0-1ef9,u+20ab}@font-face{font-family:Open Sans;font-style:normal;font-weight:600;src:local("Open Sans SemiBold"),local("OpenSans-SemiBold"),url(https://fonts.gstatic.com/s/opensans/v17/mem5YaGs126MiZpBA-UNirkOXOhpKKSTj5PW.woff2) format("woff2");unicode-range:u+0100-024f,u+0259,u+1e??,u+2020,u+20a0-20ab,u+20ad-20cf,u+2113,u+2c60-2c7f,u+a720-a7ff}@font-face{font-family:Open Sans;font-style:normal;font-weight:600;src:local("Open Sans SemiBold"),local("OpenSans-SemiBold"),url(https://fonts.gstatic.com/s/opensans/v17/mem5YaGs126MiZpBA-UNirkOUuhpKKSTjw.woff2) format("woff2");unicode-range:u+00??,u+0131,u+0152-0153,u+02bb-02bc,u+02c6,u+02da,u+02dc,u+2000-206f,u+2074,u+20ac,u+2122,u+2191,u+2193,u+2212,u+2215,u+feff,u+fffd}.auryc-feedback *{font-family:Open Sans,sans-serif!important;float:none!important;text-transform:none!important;height:auto}.auryc-feedback{display:block;font-size:10px!important;line-height:1.599!important;padding:2em!important;text-align:left!important;border-radius:5px!important;resize:both!important}.auryc-fbmodal-wrapper,.auryc-feedback{font-family:Open Sans,sans-serif!important;color:#4a4a4a}.auryc-fbmodal-wrapper{display:block;position:fixed!important;z-index:2147483647!important;width:100%!important;height:100%!important;left:0!important;top:0!important;padding:0!important;margin:0!important;display:table}.auryc-fbmodal-bground{opacity:0!important}.auryc-fbmodal-bground,.auryc-fbmodal-bground-enabled{width:100%!important;height:100%!important;left:0!important;top:0!important;padding:0!important;margin:0!important;position:fixed!important;z-index:900!important}.auryc-fbmodal-bground-enabled{opacity:.79!important;-webkit-transition:opacity .4s!important;transition:opacity .4s!important;background:#292d33}.auryc-fbmodal-container{width:100%!important;height:100%!important;left:0!important;top:0!important;position:fixed!important;overflow:scroll!important;padding:0!important;margin:0!important;z-index:2147483647!important}.auryc-fbmodal-content{display:block;font-size:18px!important;margin:0 auto 100px!important;text-align:left!important;padding:9.5px!important;height:100%!important;width:calc(99vw - 19px)!important;-webkit-font-smoothing:antialiased!important;-moz-osx-font-smoothing:grayscale!important;outline:none!important;-webkit-box-sizing:unset!important;box-sizing:unset!important}.auryc-fbmodal-content:focus{border-radius:0!important;outline:none!important;-webkit-box-shadow:none!important;box-shadow:none!important;background-color:none!important;border:0!important}@media (min-width:480px){.auryc-fbmodal-content{max-width:540px!important}}.auryc-fbmodal-body{display:block;opacity:0!important;width:100%!important}.auryc-fbmodal-body-enabled{background:#fff;-webkit-box-shadow:0 0 39px 0 rgba(0,0,0,.3)!important;box-shadow:0 0 39px 0 rgba(0,0,0,.3)!important;display:block;border-radius:4.9px!important;opacity:1!important;-webkit-transition:opacity .4s ease!important;transition:opacity .4s ease!important;width:100%!important;text-align:center!important}@media screen and (-ms-high-contrast:active),screen and (-ms-high-contrast:none){.auryc-fbmodal-body-enabled{-webkit-transition:none!important;transition:none!important}}.auryc-fbmodal-head{opacity:0!important}.auryc-fbmodal-head,.auryc-fbmodal-head-enabled{width:100%!important;display:block;clear:both!important}.auryc-fbmodal-head-enabled{opacity:1!important;-webkit-transition:opacity .4s ease!important;transition:opacity .4s ease!important;z-index:1!important}.auryc-fb-modal-closebtn{position:relative!important;right:10px!important;float:right!important;top:15px!important;background:none!important;outline:none!important;border:none!important;cursor:pointer!important;font-size:20px!important;font-weight:700!important;color:#505673!important;letter-spacing:normal!important;padding:0!important;padding:initial!important;width:auto!important}.auryc-fb-modal-closebtn:hover{color:#292e3f!important}.auryc-fb-modal-closebtn:focus{-webkit-box-shadow:0 0 2px #503bff!important;box-shadow:0 0 2px #503bff!important}#auryc-feedback-canvas{margin-top:15px!important;position:relative!important;text-align:right!important;width:100%!important}.auryc-feedback-fbquestiongroup{display:none}.auryc-feedback-fbquestiongroup-shown{display:block}#auryc-feedback-tab.auryc-feedback-tab-loc-br-horizontal{margin-right:.59em!important;left:auto!important;right:0!important;position:fixed!important;top:auto!important;display:block;-webkit-box-sizing:border-box!important;box-sizing:border-box!important;bottom:.59em;overflow:hidden!important}#auryc-feedback-tab.auryc-feedback-tab-loc-br-horizontal .auryc-feedback-tab-label{padding-left:.29em!important}#auryc-feedback-tab.auryc-feedback-tab-loc-br{margin-right:.29em!important;left:auto!important;right:0!important;top:auto!important;bottom:.59em;-webkit-transform:rotate(-90deg) translate(100%,22%)!important;transform:rotate(-90deg) translate(100%,22%)!important;-webkit-transform-origin:100% 100%!important;transform-origin:100% 100%!important;border-radius:5px 5px 0 0!important;-webkit-box-shadow:0 -2px 4px rgba(0,0,0,.1)!important;box-shadow:0 -2px 4px rgba(0,0,0,.1)!important}#auryc-feedback-tab.auryc-feedback-tab-loc-bl-horizontal{margin-right:.59em!important;position:fixed!important;right:auto!important;-webkit-box-sizing:border-box!important;box-sizing:border-box!important;overflow:hidden!important;margin-left:.59em!important;top:auto!important;display:block;bottom:1.19em!important}#auryc-feedback-tab.auryc-feedback-tab-loc-bl-horizontal .auryc-feedback-tab-label{padding-right:.29em!important;padding-left:.29em!important}#auryc-feedback-tab.auryc-feedback-tab-loc-bl{right:auto!important;margin-left:.59em!important;top:auto!important;bottom:1.2em!important;-webkit-transform:translate(-8%,100%) rotate(-90deg)!important;transform:translate(-8%,100%) rotate(-90deg)!important;-webkit-transform-origin:0 0!important;transform-origin:0 0!important;border-radius:0 0 5px 5px!important;-webkit-box-shadow:0 -2px 4px rgba(0,0,0,.1)!important;box-shadow:0 -2px 4px rgba(0,0,0,.1)!important}#auryc-feedback-tab.auryc-feedback-tab-loc-tr-horizontal{margin-right:.59em!important;position:fixed!important;left:auto!important;right:0!important;top:.59em!important;-webkit-box-sizing:border-box!important;box-sizing:border-box!important;overflow:hidden!important;margin-left:.59em!important;display:block;bottom:auto!important}#auryc-feedback-tab.auryc-feedback-tab-loc-tr-horizontal .auryc-feedback-tab-label{padding-left:.29em!important}#auryc-feedback-tab.auryc-feedback-tab-loc-tr{-webkit-transform:rotate(-90deg) translateY(-78%)!important;transform:rotate(-90deg) translateY(-78%)!important;-webkit-transform-origin:100% 0!important;transform-origin:100% 0!important;border-radius:5px 5px 0 0!important;-webkit-box-shadow:0 -2px 4px rgba(0,0,0,.1)!important;box-shadow:0 -2px 4px rgba(0,0,0,.1)!important;left:auto!important;right:0!important;top:.59em!important;position:fixed!important;margin-right:.29em!important}#auryc-feedback-tab.auryc-feedback-tab-loc-tr .auryc-feedback-tab-label:before{content:"";font-family:AurycFontAwesome!important;padding-left:5px!important}#auryc-feedback-tab.auryc-feedback-tab-loc-tl-horizontal{position:fixed!important;left:0!important;right:auto!important;top:.59em!important;-webkit-box-sizing:border-box!important;box-sizing:border-box!important;overflow:hidden!important;margin-left:.59em!important;display:block;bottom:auto!important}#auryc-feedback-tab.auryc-feedback-tab-loc-tl-horizontal .auryc-feedback-tab-label{padding-right:.29em!important;padding-left:.29em!important}#auryc-feedback-tab.auryc-feedback-tab-loc-tl{-webkit-transform:rotate(-90deg) translate(-100%,-22%)!important;transform:rotate(-90deg) translate(-100%,-22%)!important;-webkit-transform-origin:0 0!important;transform-origin:0 0!important;border-radius:0 0 5px 5px!important;-webkit-box-shadow:0 -2px 4px rgba(0,0,0,.1)!important;box-shadow:0 -2px 4px rgba(0,0,0,.1)!important;right:auto!important;margin-left:.29em!important;top:.59em!important}#auryc-feedback-tab.auryc-feedback-tab-loc-cl-horizontal{position:fixed!important;left:0!important;right:auto!important;top:50%!important;-webkit-box-sizing:border-box!important;box-sizing:border-box!important;overflow:hidden!important;margin-left:.59em!important;display:block;bottom:auto!important}#auryc-feedback-tab.auryc-feedback-tab-loc-cl-horizontal .auryc-feedback-tab-label{padding-right:.29em!important;padding-left:.29em!important}#auryc-feedback-tab.auryc-feedback-tab-loc-cl{right:auto!important;margin-left:.29em!important;top:50%!important;-webkit-transform:rotate(-90deg) translate(-50%,-22%)!important;transform:rotate(-90deg) translate(-50%,-22%)!important;-webkit-transform-origin:0 0!important;transform-origin:0 0!important;border-radius:0 0 5px 5px!important;-webkit-box-shadow:0 -2px 4px rgba(0,0,0,.1)!important;box-shadow:0 -2px 4px rgba(0,0,0,.1)!important}#auryc-feedback-tab.auryc-feedback-tab-loc-cr-horizontal{position:fixed!important;left:auto!important;right:0!important;top:50%!important;-webkit-box-sizing:border-box!important;box-sizing:border-box!important;overflow:hidden!important;margin-left:.59em!important;display:block;bottom:auto!important}#auryc-feedback-tab.auryc-feedback-tab-loc-cr-horizontal .auryc-feedback-tab-label{padding-left:.29em!important}#auryc-feedback-tab.auryc-feedback-tab-loc-cr{-webkit-transform:rotate(-90deg) translate(50%,-78%)!important;transform:rotate(-90deg) translate(50%,-78%)!important;-webkit-transform-origin:100% 0!important;transform-origin:100% 0!important;border-radius:5px 5px 0 0!important;-webkit-box-shadow:0 -2px 4px rgba(0,0,0,.1)!important;box-shadow:0 -2px 4px rgba(0,0,0,.1)!important;position:fixed!important;left:auto!important;right:0!important;top:50%!important;-webkit-box-sizing:border-box!important;box-sizing:border-box!important;overflow:hidden!important;margin-right:.29em!important;display:block;bottom:auto!important}.auryc-fb-validation-msg-section{font-family:Open Sans,sans-serif!important;font-size:14px!important;color:#db2d43;border-radius:.49em!important;margin-bottom:.49em!important;margin-top:2em!important;display:none;text-align:left!important}#auryc-feedback-tab{position:fixed!important;top:0!important;left:0!important;display:block;background:#692893;opacity:.85!important;cursor:pointer!important;-webkit-box-sizing:border-box!important;box-sizing:border-box!important;z-index:2147483647!important;font-size:80%!important;-webkit-font-smoothing:antialiased!important;-moz-osx-font-smoothing:grayscale!important}.auryc-feedback-tab-label{font-family:Open Sans,sans-serif!important;color:#fff;font-size:13px!important;z-index:5!important;font-weight:600!important;line-height:30px!important;letter-spacing:normal!important}.auryc-feedback div,.auryc-feedback fieldset,.auryc-feedback h1,.auryc-feedback h2,.auryc-feedback img,.auryc-feedback label,.auryc-feedback p,.auryc-feedback span{margin:0!important;font:inherit!important;padding:0!important;border:0!important;vertical-align:baseline!important}#auryc-feedback-tab.auryc-feedback-tab-dt-desktop,#auryc-feedback-tab.auryc-feedback-tab-dt-tablet{height:30px!important;display:block;border-radius:100px;-webkit-box-shadow:0 1px 2px 1px rgba(41,46,63,.26)!important;box-shadow:0 1px 2px 1px rgba(41,46,63,.26)!important;padding:0 12px!important;overflow:hidden!important}#auryc-feedback-tab.auryc-feedback-tab-dt-smartphone{width:40px!important;height:40px!important;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-align:center!important;-ms-flex-align:center!important;align-items:center!important;-webkit-box-pack:center!important;-ms-flex-pack:center!important;justify-content:center!important;background:#2f8cff;border-radius:50%!important;cursor:pointer!important;fill:#fff;-webkit-box-shadow:0 1px 5px rgba(0,0,0,.06),0 2px 30px rgba(0,0,0,.12)!important;box-shadow:0 1px 5px rgba(0,0,0,.06),0 2px 30px rgba(0,0,0,.12)!important;bottom:40px;margin-right:10px}@media print{#auryc-feedback-tab.auryc-feedback-tab-dt-desktop,#auryc-feedback-tab.auryc-feedback-tab-dt-tablet{display:none!important}}.auryc-feedback-spinner{display:block;top:1!important;left:1!important;position:absolute!important;z-index:2147483647!important}.auryc-fbmodal-body-selection{color:#4a4a4a;text-align:left!important;padding:25px 15px 15px!important}.auryc-fbmodal-body-selection .auryc-fbmodal-body-selection_title{font-size:18px!important;font-weight:600!important;line-height:24px!important}.auryc-fbmodal-body-selection .auryc-feedback-general,.auryc-fbmodal-body-selection .auryc-feedback-screenshot{background-color:#f6f6f6;border:1px solid #cfcfcf;border-radius:3px!important;-webkit-box-sizing:border-box!important;box-sizing:border-box!important;cursor:default!important;display:table;margin-top:10px!important;padding:5px!important;white-space:nowrap!important;width:100%!important}.auryc-fbmodal-body-selection .auryc-feedback-general .auryc-feedback_option_row,.auryc-fbmodal-body-selection .auryc-feedback-screenshot .auryc-feedback_option_row{display:table-row;height:60px!important}.auryc-fbmodal-body-selection .auryc-feedback-general .auryc-feedback_option_column,.auryc-fbmodal-body-selection .auryc-feedback-screenshot .auryc-feedback_option_column{display:table-cell;vertical-align:middle!important}.auryc-fbmodal-body-selection .auryc-feedback-general .auryc-feedback-selection__label1,.auryc-fbmodal-body-selection .auryc-feedback-screenshot .auryc-feedback-selection__label1{font-size:16px!important;font-weight:600!important;line-height:22px!important}.auryc-fbmodal-body-selection .auryc-feedback-general .auryc-feedback-selection__label2,.auryc-fbmodal-body-selection .auryc-feedback-screenshot .auryc-feedback-selection__label2{font-size:14px!important;font-weight:400!important;line-height:19px!important;white-space:normal!important}.auryc-fbmodal-body-selection .auryc-feedback-general .auryc-feedback-selection__labels,.auryc-fbmodal-body-selection .auryc-feedback-screenshot .auryc-feedback-selection__labels{padding-left:5px!important;vertical-align:middle!important}.auryc-fbmodal-body-selection .auryc-feedback-general .auryc-feedback_option_image,.auryc-fbmodal-body-selection .auryc-feedback-screenshot .auryc-feedback_option_image{width:50px!important}.auryc-fbmodal-body-selection .auryc-feedback-general img,.auryc-fbmodal-body-selection .auryc-feedback-screenshot img{vertical-align:middle!important;padding:0 5px!important}.auryc-fbmodal-body-selection .auryc-feedback-general:hover,.auryc-fbmodal-body-selection .auryc-feedback-screenshot:hover{background-color:#e4ecfc!important}div [dataType=auryc-fbq]>p{display:block;font-size:14px!important;text-align:center!important;font-weight:400!important;color:#4a4a4a;letter-spacing:0!important}.auryc-fbmodal-body-fbform,.auryc-fbmodal-body-selection{display:none}@media (min-width:1024px){.auryc-feedback{text-align:left!important}.auryc-feedback .auryc-fb-starrating-field{font-size:15px!important}}.auryc-feedback .auryc-feedback-fbform-headtag{font-family:light,Open Sans,sans-serif!important;margin-bottom:10px!important;line-height:1.2!important;color:#4a4a4a;letter-spacing:-.1px!important;background:transparent none repeat 0 0/auto auto padding-box border-box scroll!important;background:initial!important}.auryc-feedback .auryc-feedback-fbform-headtag-h1{font-size:25px!important;font-family:Open Sans,sans-serif!important;font-weight:400!important;text-align:center!important;width:inherit!important;text-transform:none!important}.auryc-feedback .auryc-feedback-fbform-headtag-h2{font-size:2.4em!important}.auryc-feedback .auryc-feedback-fblabel p{font-weight:600!important;font-size:14px!important;color:#4a4a4a;letter-spacing:0!important}.auryc-feedback p{font-size:1.2em!important;line-height:1.2!important;margin-bottom:.2em!important}.auryc-feedback .auryc-feedback-title-section{font-family:Open Sans,sans-serif!important;text-align:center!important;font-size:14px!important;margin-bottom:20px!important}.auryc-feedback .auryc-feedback-title-section .auryc-feedback-fblogo{height:3.49em!important;margin:0 auto 1.7em!important;display:block;max-height:144px!important;width:auto!important}.auryc-feedback .auryc-fb-starrating-field{width:96%!important;color:#cfcfcf!important;display:block;margin:0 auto!important;text-align:center!important;text-indent:0!important;white-space:nowrap!important}.auryc-feedback .auryc-fb-starrating-field label{color:#cfcfcf;float:none!important;height:auto!important;min-width:0!important;max-width:none!important}.auryc-fbmodal-body-fbform-enabled{display:block}#post-fb-resp-button{display:inline-block;background:#22c6f3;border:.9px solid #20c8f7;border-radius:2.9px!important;padding:.02em 4.49em!important;color:#555;resize:none!important;width:199px!important;height:35px!important;margin-top:19px!important;font-size:14px!important;letter-spacing:normal!important}.auryc-feedback .auryc-starrating-section{margin-bottom:.49em!important;font-size:18px!important;display:block;margin-top:10px!important}div[dataType=auryc-fbq]{display:block;margin-top:10px!important}.auryc-feedback-fbquestion,.auryc-feedback-fbquestion-dropdown{display:block}.auryc-feedback .auryc-feedback-fblabel{display:block;text-align:center!important;font-size:12px!important;font-family:Open Sans,sans-serif!important;color:#4a4a4a;font-weight:600!important;margin-bottom:0!important;float:none!important;height:auto!important;border:0!important;position:static!important;letter-spacing:0!important}.auryc-feedback div[dataType=auryc-feedback-checkbox]>fieldset>label,.auryc-feedback div[dataType=auryc-feedback-checkbox]>label,.auryc-feedback div[dataType=auryc-feedback-radio]>fieldset>label,.auryc-feedback div[dataType=auryc-feedback-radio]>label{border:1px solid #979797!important;border-radius:3px!important}.auryc-feedback .auryc-feedback-fbemail,.auryc-feedback div[dataType=auryc-feedback-checkbox]>fieldset>label,.auryc-feedback div[dataType=auryc-feedback-checkbox]>label,.auryc-feedback div[dataType=auryc-feedback-radio]>fieldset>label,.auryc-feedback div[dataType=auryc-feedback-radio]>label{position:relative!important;background:#fff!important;width:100%!important;font-size:1.4em!important;resize:none!important;padding:.49em!important;-webkit-box-sizing:border-box!important;box-sizing:border-box!important;text-align:left!important;-webkit-appearance:none!important;-moz-appearance:none!important;-ms-appearance:none!important;-o-appearance:none!important;appearance:none!important}.auryc-feedback .auryc-feedback-fbemail{outline:none!important;border:1px solid #d0d7e6!important;color:#292e3f!important;border-radius:3px!important;letter-spacing:normal!important}.auryc-feedback .auryc-feedback-fbemail:focus{border:1px solid #838aa4!important}.auryc-feedback ::-webkit-input-placeholder{color:#505673!important;font-family:inherit!important;text-align:left!important;font-size:inherit!important}.auryc-feedback ::-moz-placeholder{color:#505673!important;font-family:inherit!important;text-align:left!important;font-size:inherit!important}.auryc-feedback ::-ms-input-placeholder{color:#505673!important;font-family:inherit!important;text-align:left!important;font-size:inherit!important}.auryc-feedback .auryc-feedback-question-textarea{position:relative!important;border-radius:3px!important;background:#fff!important;color:#292e3f!important;width:100%!important;font-size:1.4em!important;resize:none!important;padding:.49em!important;-webkit-box-sizing:border-box!important;box-sizing:border-box!important;text-align:left!important;-webkit-appearance:none!important;-moz-appearance:none!important;-ms-appearance:none!important;-o-appearance:none!important;appearance:none!important;height:54px!important;border:1px solid #d0d7e6!important}.auryc-feedback .auryc-feedback-fbtarea{display:block;position:relative!important;margin:0!important;text-align:right!important}.auryc-feedback .auryc-feedback-fbtarea .auryc-feedback-fbctrl{padding-bottom:1.2em!important;margin:0!important;max-width:100%!important}.auryc-feedback .auryc-feedback-question-dropdown-choose,.auryc-feedback .auryc-feedback-question-select-choose{position:relative!important;border-radius:none!important;background:#fff!important;width:100%!important;font-size:1.4em!important;resize:none!important;padding:.49em!important;-webkit-box-sizing:border-box!important;box-sizing:border-box!important;text-align:left!important;-webkit-appearance:none!important;-moz-appearance:none!important;-ms-appearance:none!important;-o-appearance:none!important;appearance:none!important;border:none!important;outline:none!important;color:#313943!important}.PoweredByAuryc{text-decoration:none!important}.PoweredByAuryc:hover span{text-decoration:underline!important}.PoweredByAuryc:focus{outline:none!important;border:1px solid #4d90fe!important;-webkit-box-shadow:0 0 5px #4d90fe!important;box-shadow:0 0 5px #4d90fe!important}.auryc-feedback .auryc-feedback-footer-section{display:block;position:relative!important;text-align:center!important}.auryc-feedback .auryc-feedback-footer-section .auryc-fbmodal-footer{background:inherit!important;position:relative!important;left:1px!important;display:table;font-size:10px!important;color:#4a4a4a!important;letter-spacing:-.35px!important;z-index:3!important;width:100%!important}.auryc-fbmodal-footer span{display:inline;color:#292e3f!important;font-size:11px!important;font-weight:400!important}.auryc-feedback .auryc-feedback-footer-section .auryc-fbmodal-footer img{display:inline;position:relative!important;top:-1px!important;left:1px!important;vertical-align:middle!important}.auryc-feedback .auryc-feedback-question-dropdown-choose:after,.auryc-feedback .auryc-feedback-question-select-choose:after{position:absolute!important;top:30%!important;right:1em!important;content:"";padding-left:5px!important;color:inherit!important;pointer-events:none!important;font-family:AurycFontAwesome!important;line-height:1!important;-moz-osx-font-smoothing:grayscale!important;font-weight:400!important;font-stretch:normal!important;-webkit-font-feature-settings:normal!important;font-feature-settings:normal!important;font-variant:normal!important;font-size:inherit!important;text-rendering:auto!important;-webkit-font-smoothing:antialiased!important}.auryc-feedback .auryc-feedback-question-select-choose .auryc-fb-question-selector,.auryc-feedback .auryc-feedback-question-select-choose .auryc-fb-questiongroup-selector{padding:4px 30px 4px 4px!important;z-index:auto!important;letter-spacing:normal!important;min-height:36px!important;white-space:normal!important}.auryc-feedback .auryc-feedback-question-dropdown-choose .auryc-fb-dropdown-selector,.auryc-feedback .auryc-feedback-question-select-choose .auryc-fb-question-selector,.auryc-feedback .auryc-feedback-question-select-choose .auryc-fb-questiongroup-selector{position:absolute!important;left:0!important;top:0!important;width:100%!important;text-transform:none!important;cursor:pointer!important;font-size:14px!important;border:1px solid #d0d7e6!important;border-radius:3px!important;background:#fff!important;font-weight:600!important;color:#292e3f!important;-webkit-appearance:none!important;-moz-appearance:none!important;-ms-appearance:none!important;-o-appearance:none!important;appearance:none!important}.auryc-feedback .auryc-feedback-question-dropdown-choose .auryc-fb-dropdown-selector{padding:4px!important}.auryc-fb-question-selector::-ms-expand,.auryc-fb-questiongroup-selector::-ms-expand{display:none}.auryc-fb-questiongroup-selector:focus .auryc-fb-question-selector:focus{-webkit-box-shadow:0 0 1px 1px #23c6f5!important;box-shadow:0 0 1px 1px #23c6f5!important}.auryc-feedback .auryc-close-btn{width:222px!important;height:36px!important;position:relative!important;padding:.29em 1.9em!important;font-family:Open Sans,sans-serif!important;font-size:18px!important;line-height:0!important;text-align:center!important;color:#555!important;font-weight:400!important;display:inline-block;overflow:hidden!important;text-overflow:ellipsis!important;white-space:nowrap!important;border-radius:0!important;background-color:#464c55;border:1px solid #464c55;cursor:pointer!important;margin:0 auto!important}.auryc-feedback .auryc-feedback-select-button{font-family:Open Sans,sans-serif!important;font-size:14px!important;font-weight:400!important;color:transparent!important;text-align:left!important}.auryc-feedback .post-fb-resp-button{padding:.49em .6999em!important;line-height:1.618!important;width:100%!important}.auryc-feedback .auryc-feedback-btn,.auryc-feedback .post-fb-resp-button{display:inline-block;overflow:hidden!important;text-overflow:ellipsis!important;white-space:nowrap!important;border-radius:0!important;background-color:#464c55;border:1px solid #464c55;cursor:pointer!important;color:#fff;font-size:1.7em!important;text-align:center!important;font-weight:400!important;-webkit-transition:all .14s ease!important;transition:all .14s ease!important;margin:0 auto!important}.auryc-feedback .auryc-feedback-btn{padding:.49em .69999em!important;line-height:1.599!important;outline:0!important}.auryc-feedback .auryc-fb-starrating-field .auryc-fb-starrating-field-staricon{font-size:6em!important;cursor:pointer!important;border:0!important}.auryc-feedback .auryc-fb-starrating-field .auryc-fb-starrating-field-staricon:before{font-family:Open Sans,sans-serif!important;content:""}.auryc-feedback .auryc-fb-starrating-field--disabled{color:#eaebec!important}.auryc-feedback .auryc-fb-starrating-field--disabled .auryc-fb-starrating-field-staricon{cursor:default!important;border:0!important}.auryc-feedback .auryc-fb-starrating-field input[type=radio]{position:absolute!important;left:-10000px!important;display:block}.auryc-feedback input[type=text],.auryc-feedback textarea{font-family:Open Sans,sans-serif!important;height:100%!important;float:none!important;height:auto!important;min-height:auto!important}.auryc-feedback .auryc-fb-starrating-field .auryc-fb-starrating-field-staricon:before,.auryc-feedback .auryc-fb-starrating-field label:before,.auryc-feedback .auryc-feedback-checkbox:before,.auryc-feedback .auryc-feedback-radio:before{font-family:AurycFontAwesome!important;line-height:1!important;font-style:normal!important;font-weight:400!important;font-stretch:normal!important;-webkit-font-feature-settings:normal!important;font-feature-settings:normal!important;font-variant:normal!important;font-size:inherit!important;text-rendering:auto!important;margin:0!important;-webkit-font-smoothing:antialiased!important;-moz-osx-font-smoothing:grayscale!important;-webkit-box-sizing:unset!important;box-sizing:unset!important}.auryc-feedback .auryc-fb-starrating-field input.auryc-fb-starrating-field-staricon+label{padding:0!important;font-size:2em!important;cursor:pointer!important;display:inline-block;margin:0!important;border:0!important;position:static!important}.auryc-feedback .auryc-fb-starrating-field label:before{-webkit-transition:color .15s ease!important;transition:color .15s ease!important;content:"★";background:0 0!important;height:auto!important;width:auto!important;top:0!important;margin:0!important}.auryc-feedback .auryc-fb-starrating-field input.auryc-fb-starrating-field-staricon:checked+label:before{content:"★";color:#ffaf40;background:0 0!important}.auryc-feedback .auryc-fb-starrating-field label.auryc-ratings-chosen:before{color:#ffaf40;content:"★"}.auryc-feedback .auryc-nps__container{border:1px solid #f6f7f9!important;border-radius:5px!important;padding:10px 0!important;background-color:transparent!important}@media (max-width:360px) and (orientation:portrait){.auryc-feedback .auryc-nps__container{padding:10px 0 0!important}}.auryc-feedback .auryc-nps__container .nps-rating{padding:10px 10px 0!important;margin:auto auto 10px!important;min-height:35px!important;text-align:justify!important}.auryc-feedback .auryc-nps__container .nps-rating .nps-rating__labels{display:block}.auryc-feedback .auryc-nps__container .nps-rating .nps_rating_left_label,.auryc-feedback .auryc-nps__container .nps-rating .nps_rating_right_label{font-size:12px;color:#505673}.auryc-feedback .auryc-nps__container .nps-rating .nps_rating_left_label{float:left!important}.auryc-feedback .auryc-nps__container .nps-rating .nps_rating_right_label{float:right!important}.auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges{display:block;text-align:center!important;min-height:30px!important}.auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges label{padding:0!important;cursor:pointer!important;display:inline;margin:0!important;border:0!important}.auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges label:before{display:none}.auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges label:hover{color:#fff;background-color:#23c6f5}.auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges .nps-rating__badge{border-radius:50%!important;width:28px!important;padding:2px!important;font-size:12px!important;line-height:1em!important;position:relative!important;background:#f6f7f9;border:1px solid #d0d7e6;display:inline-block;-webkit-box-sizing:border-box!important;box-sizing:border-box!important;bottom:auto!important;top:auto!important;left:auto!important;right:auto!important}.auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges .aurycNpsRatingChecked,.auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges input[type=radio]:checked+label{color:#fff;background-color:#23c6f5}.auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges .nps-rating__badge .nps-rating__height_fix{margin-top:100%!important}.auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges .nps-rating__badge .nps-rating__num{position:absolute!important;left:0!important;top:50%!important;height:100%!important;width:100%!important;text-align:center!important;margin-top:-6px!important}.auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges .stretch{width:100%!important;display:inline-block;font-size:0!important;line-height:0!important;padding:0!important;margin:0!important;height:0!important}.auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges input[type=radio]{position:absolute!important;left:-10000px!important;display:block}@media (max-width:420px) and (orientation:portrait){.auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges .nps-rating__badge{width:20px!important}}.auryc-feedback .auryc-feedback-checkbox,.auryc-feedback .auryc-feedback-radio{text-align:left!important;display:block;cursor:pointer!important;padding:4px 10px!important;bottom:auto!important;top:auto!important;left:auto!important;right:auto!important}.auryc-feedback .auryc-feedback-checkbox:focus,.auryc-feedback .auryc-feedback-radio:focus{background:#f6f7f9!important}.auryc-feedback .auryc-feedback-checkbox:nth-child(1n+2),.auryc-feedback .auryc-feedback-radio:nth-child(1n+2){margin-top:.49em!important}.auryc-feedback .auryc-feedback-checkbox input,.auryc-feedback .auryc-feedback-radio input{display:none}.auryc-feedback .auryc-feedback-checkbox:before{content:"";padding-left:.29em!important;padding-right:.29em!important;color:inherit;opacity:.3}.auryc-feedback .auryc-feedback-checkbox.aurycChecked:before{content:"";opacity:1;color:#23c6f5}.auryc-feedback .auryc-feedback-radio:before{padding-left:.29em!important;padding-right:.29em!important;color:inherit;opacity:.3;content:"\f10c"}.auryc-feedback .auryc-feedback-radio.aurycChecked:before{content:"\f111";opacity:1;color:#23c6f5}.aurycIsRequired{color:#db2d43!important}.fb-desktop:not(.user-is-tabing) button:focus,.fb-desktop:not(.user-is-tabing) input:focus,.fb-desktop:not(.user-is-tabing) select:focus,.fb-desktop:not(.user-is-tabing) textarea:focus{outline:none!important}.fb-desktop .auryc-feedback div[dataType=auryc-feedback-checkbox]>fieldset>label,.fb-desktop .auryc-feedback div[dataType=auryc-feedback-radio]>fieldset>label{border:1px solid transparent!important;vertical-align:middle!important;background:transparent!important}.fb-desktop.user-is-tabing .auryc-feedback div[dataType=auryc-feedback-checkbox]>fieldset>label.focus,.fb-desktop.user-is-tabing .auryc-feedback div[dataType=auryc-feedback-radio]>fieldset>label.focus,.fb-desktop.user-is-tabing button:focus,.fb-desktop.user-is-tabing input:focus,.fb-desktop.user-is-tabing select:focus,.fb-desktop.user-is-tabing textarea:focus{outline:none!important;border:1px solid #4d90fe!important;-webkit-box-shadow:0 0 5px #4d90fe!important;box-shadow:0 0 5px #4d90fe!important}.fb-desktop .auryc-feedback div[dataType=auryc-feedback-checkbox]>fieldset>input,.fb-desktop .auryc-feedback div[dataType=auryc-feedback-radio]>fieldset>input{position:absolute!important;left:-10000px!important}.auryc-feedback .auryc-fb-starrating-field input.auryc-fb-starrating-field-staricon+label{border:1px solid hsla(0,0%,100%,.5)!important}.fb-desktop.user-is-tabing .auryc-feedback .auryc-fb-starrating-field input.auryc-fb-starrating-field-staricon+label.focus{outline:none!important;border:1px solid #4d90fe!important;-webkit-box-shadow:0 0 5px #4d90fe!important;box-shadow:0 0 5px #4d90fe!important}.fb-desktop .auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges .nps-rating__badge{border:1px solid transparent!important}.fb-desktop.user-is-tabing .auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges .nps-rating__badge.focus{outline:none!important;border:1px solid #4d90fe!important;-webkit-box-shadow:0 0 5px #4d90fe!important;box-shadow:0 0 5px #4d90fe!important}.fb-desktop .auryc-feedback .auryc-starrating-section legend.auryc-feedback-fblabel,.fb-desktop .auryc-feedback .nps-rating legend.auryc-feedback-fblabel{margin-left:-10px!important}.fb-desktop .auryc-feedback label.auryc-feedback-checkbox:focus,.fb-desktop .auryc-feedback label.auryc-feedback-radio:focus{background:#fafaff!important;-webkit-box-shadow:0 1px 1px #b3badb!important;box-shadow:0 1px 1px #b3badb!important;color:#292e3f!important;border:1px solid #6875b8!important}.auryc-feedback .auryc-feedback-title-section .auryc-feedback-fblogo{margin:0 0 20px!important}.fb-desktop .auryc-feedback h1{font-weight:600!important;font-size:20px!important;color:#292e3f!important;text-align:left!important}.fb-desktop .auryc-feedback p{font-size:14px!important;color:#292e3f!important;text-align:left!important}.fb-desktop .auryc-feedback .required-label{color:#505673!important;font-size:12px!important;font-style:italic!important;margin:10px 0!important}.fb-desktop .auryc-feedback .required-label b{color:#db2d43!important}.fb-desktop .auryc-feedback .auryc-feedback-fblabel{text-align:left!important;font-weight:600!important;font-size:12px!important;color:#292e3f!important;position:static!important}.fb-desktop .auryc-feedback .auryc-feedback-fblabel.aurycIsRequired{color:#db2d43!important}.fb-desktop .auryc-feedback .auryc-fb-starrating-field{text-align:left!important}.fb-desktop.fb-desktop.user-is-tabing .auryc-feedback .auryc-fb-starrating-field.focus{outline:solid!important}.fb-desktop .auryc-feedback .auryc-fb-starrating-field label{color:#838aa4!important}.fb-desktop .auryc-feedback .auryc-nps__container{background:transparent!important;border:transparent!important}.fb-desktop .auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges{display:-webkit-box!important;display:-ms-flexbox!important;display:flex!important;text-align:left!important;min-height:30px!important;-webkit-box-pack:justify!important;-ms-flex-pack:justify!important;justify-content:space-between!important;-ms-flex-flow:wrap!important;flex-flow:wrap!important}.fb-desktop .auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges .nps-rating__badge{border-radius:4px!important}.fb-desktop .auryc-feedback .auryc-feedback-radio:before{content:"\f1db"!important;font-size:18px!important;opacity:1!important;padding-left:4px!important;padding-right:4px!important}.fb-desktop .auryc-feedback .auryc-feedback-radio.aurycCheckedOverride:before{border:1px solid #000!important;border-radius:12px!important;content:"\f111"!important;font-size:14px!important;margin:3px!important;padding:1px 2px!important;opacity:1!important}.fb-desktop .auryc-feedback .auryc-feedback-checkbox:before{content:"\f096";font-size:20px!important;padding-left:4px!important;padding-right:4px!important;opacity:1!important}.auryc-feedback .auryc-feedback-checkbox.aurycCheckedOverride:before{padding-left:3px!important;padding-right:3px!important}.fb-desktop .auryc-feedback .auryc-feedback-checkbox,.fb-desktop .auryc-feedback .auryc-feedback-radio{display:inline!important;outline:none!important;padding:4px 10px!important}.fb-desktop .auryc-feedback-checkbox.full,.fb-desktop .auryc-feedback-radio.full{display:block!important}.fb-desktop .auryc-feedback .auryc-fb-starrating-field.centered{text-align:center!important}.auryc-feedback .auryc-feedback-title-section .auryc-feedback-fblogo.centered{margin:0 auto 1.7em!important}.fb-desktop .auryc-feedback-title-section h1.centered,.fb-desktop .auryc-feedback-title-section p.centered,.fb-desktop .auryc-feedback .auryc-nps__container .nps-rating .nps-rating__badges.centered,.fb-desktop .auryc-nps__container .auryc-feedback-fblabel.centered,.fb-desktop .auryc-starrating-section .auryc-feedback-fblabel.centered{text-align:center!important}</style><link rel="stylesheet" type="text/css" href="./HackerRank_files/basequestion-76d6aa25.css"><script charset="utf-8" src="./HackerRank_files/basequestion-d1b427f1.js.download"></script><link rel="stylesheet" type="text/css" href="./HackerRank_files/hackerrank_r_modules_login_view_instructions-35e1b362.css"><script charset="utf-8" src="./HackerRank_files/hackerrank_r_modules_login_view_instructions-09645869.js.download"></script><link rel="stylesheet" type="text/css" href="./HackerRank_files/hackerrank_r_vendors_instructions-8932da70.css"><script charset="utf-8" src="./HackerRank_files/hackerrank_r_vendors_instructions-90273392.js.download"></script><link rel="stylesheet" type="text/css" href="./HackerRank_files/instructions-6cabc189.css"><script charset="utf-8" src="./HackerRank_files/instructions-5e81debf.js.download"></script><link rel="stylesheet" type="text/css" href="./HackerRank_files/hackerrank_r_vendors_login_view_file_upload_question_view_rba_question_view_frontend_question_view_sudorank_view-4e6612ef.css"><script charset="utf-8" src="./HackerRank_files/hackerrank_r_vendors_login_view_file_upload_question_view_rba_question_view_frontend_question_view_sudorank_view-52c213fd.js.download"></script><link rel="stylesheet" type="text/css" href="./HackerRank_files/file_upload_question_view-662508b0.css"><script charset="utf-8" src="./HackerRank_files/file_upload_question_view-af63bead.js.download"></script><meta property="og:url" id="meta-og-url" content="https://www.hackerrank.com/test/3fmff7cgcpe/questions/46hcjfcfs00"><meta name="twitter:url" id="meta-twitter-url" content="https://www.hackerrank.com/test/3fmff7cgcpe/questions/46hcjfcfs00"></head>
  <body class="theme-m">
      

  <!-- Just a placeholder div to start loading open sans and source code loader -->
  <div class="font-open-sans-loader"></div>
  <div class="font-source-code-loader"></div>
  <!-- Just a placeholder div to start loading open sans and source code loader end -->

  <div id="content" onclick="void(0);"><div class="ui-kit-root"><div class="body-wrap base-page test_view-page question_listview-page single_question_view-page"><div class="toast-message loading"><span class="toast-container containment"><i class="ui-icon-loading"></i><span class="toast-text">Loading...</span></span></div><div class="root-container"><div class="prefetch-assets-wrapper"></div><header class="d-flex flex-column main-header"><nav class="d-flex align-items-center main-header__nav"><div class="justify-content-center"><a href="https://www.hackerrank.com/test/3fmff7cgcpe/questions"><img class="d-flex main-header__logo" src="./HackerRank_files/fe99c1" alt="Data Science test"></a></div><div class="d-flex align-items-center main-header__test"><h1 class="main-header__title">Data Science test</h1><div class="d-flex align-items-center main-header__test-info"><div class="main-header__test-time" data-balloon="06 hours 31 mins 17 seconds" data-balloon-pos="down">Remaining time <strong class="main-header__timer">06 hours 31 mins</strong><button class="ui-btn ui-btn-normal ui-btn-plain main-header__toggle-timer" tabindex="0" aria-label="Hide test timer" data-event-category="Question Details Page" data-event-action="Click" data-event-label="HideRemainingTime"><div class="ui-content align-icon-right"><span class="ui-text">Hide<i class="ui-icon-timer-visibility"></i></span></div></button></div><div class="main-header__test-attempts">Questions Attempted<!-- --> <strong class="main-header__info-text">0<!-- --> / <!-- -->1</strong></div></div></div><nav class="d-flex userinfo" aria-label="User account options"><div class="dropdown userinfo__dropdown"><div aria-haspopup="menu" class="dropdown-handle align-items-center justify-content-center userinfo__handle _ar_hide_" _ar_hide_="width:219.462px;height:58.0035px;margin:0px;position:static;display:inline-block;"><button class="ui-btn ui-btn-normal ui-btn-plain align-items-center userinfo__name" tabindex="0" data-event-category="Question Details Page" data-event-action="Click" data-event-label="ProfileSettings"><div class="ui-content align-icon-right"><span class="ui-text"><i class="ui-icon-user userinfo__icon"></i><span>Abhranil Mukhopadhyay</span><i class="ui-icon-arrow-down-filled userinfo__icon"></i></span></div></button></div><div role="menu" class="dropdown-body userinfo__options" aria-hidden="true" tabindex="-1"><div class="dropdown-menu pull-right"><ul class="userinfo__list" aria-label="User account options"><li><a class="d-flex userinfo__link" data-event-category="Question Details Page" data-event-action="Click" data-event-label="InstructionsSettings" href="https://www.hackerrank.com/test/3fmff7cgcpe/instructions">Instructions</a></li><li><a class="ui-btn ui-btn-normal ui-btn-plain userinfo__logout-btn ui-btn-link" tabindex="0" data-event-category="Question Details Page" data-event-action="Click" data-event-label="SubmitAndLogOutSettings"><div class="ui-content align-icon-right"><span class="ui-text">Submit Test</span></div></a></li></ul></div></div></div></nav></nav></header><div class="d-flex flex-row test-container"><div class="d-flex question-tab"><ul class="question-tab__list"><li><a class="d-block question-tab__list-item" title="List of Questions" href="https://www.hackerrank.com/test/3fmff7cgcpe/questions">ALL</a></li><li><a class="d-block question-tab__list-item" aria-label="See instructions" href="https://www.hackerrank.com/test/3fmff7cgcpe/instructions"><i class="ui-icon-info question-tab__list-item-icon"></i></a></li><li class="question-tab__separator"></li></ul><ul class="question-tab__list question-tab__list--scrollable"><li><a class="d-block question-tab__list-item question-tab__list-item--active" aria-label="Solve question 1" href="https://www.hackerrank.com/test/3fmff7cgcpe/questions/46hcjfcfs00">1</a></li></ul></div><div class="d-flex flex-column test-container__content"><div class="question-view question-view--file_upload"><div class="file-upload-question"><div class="file-upload-question__statement"><section><h1 class="question-view__title">1. Medication compliance forecasting </h1></section><section class="question-view__instruction"><div class="candidate-rich-text"><div id="46hcjfcfs00-instruction"><p>To build a predictive model, you are provided a data set that contains details about patient and the</p>

<p>prescription.&nbsp;</p>

<p>Objective is to predict patient’s likelihood of adherence to a prescribed regimen. For that,</p>

<p>information is provided both for patient and the prescription. Patient information include details like</p>

<p>age, gender, medical history, cultural background etc. Details about the prescription are like Diet</p>

<p>control advised, Exercise advised etc.</p>

<p>Variables list:</p>

<table border="1" cellpadding="0" cellspacing="0" style="width:619px;" width="619">
	<tbody>
		<tr>
			<td style="width:35px;height:23px;">
			<p>No.</p>
			</td>
			<td nowrap="" style="width:187px;height:23px;">
			<p>Variable</p>
			</td>
			<td nowrap="" style="width:168px;height:23px;">
			<p>Description</p>
			</td>
			<td nowrap="" style="width:229px;height:23px;">
			<p>Value</p>
			</td>
		</tr>
		<tr>
			<td style="width:35px;height:23px;">
			<p>1</p>
			</td>
			<td nowrap="" style="width:187px;height:23px;">
			<p>Patient_id</p>
			</td>
			<td nowrap="" style="width:168px;height:23px;">
			<p>Unique id of each patient</p>
			</td>
			<td nowrap="" style="width:229px;height:23px;">
			<p>Numerical value</p>
			</td>
		</tr>
		<tr>
			<td style="width:35px;height:23px;">
			<p>2</p>
			</td>
			<td nowrap="" style="width:187px;height:23px;">
			<p>Age</p>
			</td>
			<td nowrap="" style="width:168px;height:23px;">
			<p>Age of patient</p>
			</td>
			<td nowrap="" style="width:229px;height:23px;">
			<p>(between 0 to 113)</p>
			</td>
		</tr>
		<tr>
			<td style="width:35px;height:23px;">
			<p>3</p>
			</td>
			<td nowrap="" style="width:187px;height:23px;">
			<p>Gender</p>
			</td>
			<td nowrap="" style="width:168px;height:23px;">
			<p>Gender of patient</p>
			</td>
			<td nowrap="" style="width:229px;height:23px;">
			<p>(M, F)</p>
			</td>
		</tr>
		<tr>
			<td style="width:35px;height:23px;">
			<p>4</p>
			</td>
			<td nowrap="" style="width:187px;height:23px;">
			<p>Prescription_period</p>
			</td>
			<td nowrap="" style="width:168px;height:23px;">
			<p>How many days medication was prescribed for</p>
			</td>
			<td nowrap="" style="width:229px;height:23px;">
			<p>(between 1 to 120)</p>
			</td>
		</tr>
		<tr>
			<td style="width:35px;height:23px;">
			<p>5</p>
			</td>
			<td nowrap="" style="width:187px;height:23px;">
			<p>Diabetes</p>
			</td>
			<td nowrap="" style="width:168px;height:23px;">
			<p>If patient is diabetic or not</p>
			</td>
			<td nowrap="" style="width:229px;height:23px;">
			<p>(0,1)</p>
			</td>
		</tr>
		<tr>
			<td style="width:35px;height:23px;">
			<p>6</p>
			</td>
			<td nowrap="" style="width:187px;height:23px;">
			<p>Alcoholism</p>
			</td>
			<td nowrap="" style="width:168px;height:23px;">
			<p>If patient is alcoholic or not</p>
			</td>
			<td nowrap="" style="width:229px;height:23px;">
			<p>(0,1)</p>
			</td>
		</tr>
		<tr>
			<td style="width:35px;height:23px;">
			<p>7</p>
			</td>
			<td nowrap="" style="width:187px;height:23px;">
			<p>HyperTension</p>
			</td>
			<td nowrap="" style="width:168px;height:23px;">
			<p>If patient is hypertensive or not</p>
			</td>
			<td nowrap="" style="width:229px;height:23px;">
			<p>(0,1)</p>
			</td>
		</tr>
		<tr>
			<td style="width:35px;height:23px;">
			<p>8</p>
			</td>
			<td nowrap="" style="width:187px;height:23px;">
			<p>Smokes</p>
			</td>
			<td nowrap="" style="width:168px;height:23px;">
			<p>if patient smokes or not</p>
			</td>
			<td nowrap="" style="width:229px;height:23px;">
			<p>(0,1)</p>
			</td>
		</tr>
		<tr>
			<td style="width:35px;height:23px;">
			<p>9</p>
			</td>
			<td nowrap="" style="width:187px;height:23px;">
			<p>Tuberculosis</p>
			</td>
			<td nowrap="" style="width:168px;height:23px;">
			<p>if patient had tb or not</p>
			</td>
			<td nowrap="" style="width:229px;height:23px;">
			<p>(0,1)</p>
			</td>
		</tr>
		<tr>
			<td style="width:35px;height:23px;">
			<p>10</p>
			</td>
			<td nowrap="" style="width:187px;height:23px;">
			<p>Sms_Reminder</p>
			</td>
			<td nowrap="" style="width:168px;height:23px;">
			<p>How many sms reminders were sent to patient per day</p>
			</td>
			<td nowrap="" style="width:229px;height:23px;">
			<p>(0,1,2)</p>
			</td>
		</tr>
		<tr>
			<td style="width:35px;height:23px;">
			<p>11</p>
			</td>
			<td nowrap="" style="width:187px;height:23px;">
			<p>Adherence</p>
			</td>
			<td nowrap="" style="width:168px;height:23px;">
			<p>Patient adherence to prescription</p>
			</td>
			<td nowrap="" style="width:229px;height:23px;">
			<p>(yes, no)</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>Training data will be given with above mentioned variables including outcome variable (i.e.</p>

<p>Adherence).</p>

<p>Your model’s performance will be evaluated on a test data set which will have the same variables.</p>

<p>Your model should give probability score for each patient and a prediction of whether patient will</p>

<p>adhere to prescription or not (Yes / No). Please provide a function or definition to score the test data.</p>

<p>&nbsp;</p>

<p>Training data can be downloaded from following link:</p>

<p><a href="https://s3.amazonaws.com/istreet-assets/b0dYYtsKn3qpFdbc92-1FA/Training%20Data.csv">https://s3.amazonaws.com/istreet-assets/b0dYYtsKn3qpFdbc92-1FA/Training Data.csv</a></p>

<p>&nbsp;</p>

<p>Training data to be scored:</p>

<p><a href="http://s3.amazonaws.com/istreet-assets/OXs0DPJTWCFsd_THzQXilA/Test%20Data.csv">Test Data</a></p>

<p>&nbsp;</p>

<p><span style="font-size:18px;"><strong>Evaluation:</strong></span></p>

<p>For each patient id in test set, you must predict if a patient is going to adhere to the prescribed regimen. Your model will be evaluated on precision and recall for both the outcomes. So, your code must include generation of confusion matrix for your predictions.</p>

<p>Example:</p>

<p>&nbsp;</p>

<table border="0" cellpadding="0" cellspacing="0" style="width:463px;" width="463">
	<tbody>
		<tr>
			<td style="width:171px;height:17px;">&nbsp;</td>
			<td style="width:146px;height:17px;">
			<p><strong>Actual Yes</strong></p>
			</td>
			<td style="width:146px;height:17px;">
			<p><strong>Actual No</strong></p>
			</td>
		</tr>
		<tr>
			<td style="width:171px;height:17px;">
			<p><strong>Predicted Yes</strong></p>
			</td>
			<td style="width:146px;height:17px;">
			<p>280</p>
			</td>
			<td style="width:146px;height:17px;">
			<p>1463</p>
			</td>
		</tr>
		<tr>
			<td style="width:171px;height:17px;">
			<p><strong>Predicted &nbsp;No</strong></p>
			</td>
			<td style="width:146px;height:17px;">
			<p>42</p>
			</td>
			<td style="width:146px;height:17px;">
			<p>18270</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>• Precision for Yes: 280/(280+1463)= 16.1%</p>

<p>• Recall for Yes : 280/(280+42)= 87.0%</p>

<p>• Precision for No: 18270/(18270+42)= 99.8%</p>

<p>• Recall for No: 18270/(18270+1463)= 92.6%</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p><span style="font-size:18px;"><strong>Submission file format:</strong></span></p>

<p>You need to upload final results and code in a zip file. It should have:</p>

<p>a.) Result: In a csv file, adherence metric as yes or no for each patient with a probability score between 0 to 1.</p>

<p>Sample output:</p>

<p>patient_id, adherence, probability score</p>

<p>1001, yes, 0.99</p>

<p>b.) Code in a file with appropriate file extension.</p>

<p>c) A word document describing your approach to solve the above problem.</p>
</div></div></section></div><div class="file-upload-question__btn-upload"><section><div class="d-flex flex-column file-upload file-upload__drop"><div class="d-flex flex-row align-items-center justify-content-between"><div class="file-upload__left"><svg viewBox="0 0 24 24" width="1em" height="1em" class=" ui-svg-icon" fill="currentColor"><g><g><path d="M20.2 15.6c-.5 0-.9.4-.9.9v2.7c0 .5-.4.9-.9.9H5.6c-.5 0-.9-.4-.9-.9v-2.7c0-.5-.4-.9-.9-.9s-.9.4-.9.9v2.7c0 1.5 1.2 2.7 2.7 2.7h12.7c1.5 0 2.7-1.2 2.7-2.7v-2.7c.1-.5-.3-.9-.8-.9z"></path><path d="M11.4 17c.4.4.9.4 1.3 0l3.6-3.6c.3-.4.3-.9-.1-1.3-.3-.3-.9-.3-1.2 0l-2 2V3c0-.4-.2-.7-.5-.8-.5-.3-1.1-.2-1.4.3-.1.2-.1.3-.1.5v11.1l-2-2c-.2-.2-.4-.3-.6-.3-.5 0-.9.4-.9.9 0 .2.1.5.3.6l3.6 3.7z"></path></g></g></svg><label for="file_upload_question-1">Drag and Drop File</label></div><div class="file-upload__or-text file-upload__text-muted">or</div><div class="d-flex flex-column file-upload__right"><button class="ui-btn ui-btn-normal ui-btn-primary" tabindex="0" aria-label="Add File"><div class="ui-content align-icon-right"><span class="ui-text">Add File</span></div></button><input id="file_upload_question-1" type="file" class="d-none"></div></div></div></section></div><div class="file-upload-question__btn-submit"><button class="ui-btn ui-btn-normal ui-btn-line-primary" tabindex="0"><div class="ui-content align-icon-right"><span class="ui-text">Submit Answer &amp; Continue</span></div></button></div></div></div></div></div></div></div></div></div><!--Required to handle event bubbling of click in ios safari -->

    
    

      <script>
        window.moment = {
          tz: {},
        };
      </script>
    

      <script>
    //HR namespace
    HR = window.HR || {};
    HR.development = false;
    HR.assetPath = 'https://hrcdn.net/candidate-site/assets/';
    HR.pageLoadTime = Date.now();
    HR.production = true;
    HR.devServer = false;
    HR.isIsomorphic = true;
    HR.loadedWithOldCss = true;
    HR.pusher = {"key":"a280047e3b323ccb1b65","cluster":"mt1"};
  </script>

  <!-- Vendor scripts -->
  
    <script src="./HackerRank_files/hackerrank_r_vendor-377deede8f.js.download"></script>
  

  
  <script src="./HackerRank_files/runtime-a4ab5b9c.js.download"></script><script type="text/javascript" id="">/*
 JavaScript Cookie v2.1.3
 https://github.com/js-cookie/js-cookie

 Copyright 2006, 2015 Klaus Hartl & Fagner Brack
 Released under the MIT license
*/
(function(l){var g=!1;if(!g){var e=window.Cookies,a=window.Cookies=l();a.noConflict=function(){window.Cookies=e;return a}}})(function(){function l(){for(var e=0,a={};e<arguments.length;e++){var b=arguments[e],c;for(c in b)a[c]=b[c]}return a}function g(e){function a(b,c,d){if("undefined"!==typeof document){if(1<arguments.length){d=l({path:"/"},a.defaults,d);if("number"===typeof d.expires){var h=new Date;h.setMilliseconds(h.getMilliseconds()+864E5*d.expires);d.expires=h}try{var k=JSON.stringify(c);
/^[\{\[]/.test(k)&&(c=k)}catch(p){}c=e.write?e.write(c,b):encodeURIComponent(String(c)).replace(/%(23|24|26|2B|3A|3C|3E|3D|2F|3F|40|5B|5D|5E|60|7B|7D|7C)/g,decodeURIComponent);b=encodeURIComponent(String(b));b=b.replace(/%(23|24|26|2B|5E|60|7C)/g,decodeURIComponent);b=b.replace(/[\(\)]/g,escape);return document.cookie=[b,"\x3d",c,d.expires?"; expires\x3d"+d.expires.toUTCString():"",d.path?"; path\x3d"+d.path:"",d.domain?"; domain\x3d"+d.domain:"",d.secure?"; secure":""].join("")}b||(k={});h=document.cookie?
document.cookie.split("; "):[];for(var g=/(%[0-9A-Z]{2})+/g,n=0;n<h.length;n++){var q=h[n].split("\x3d"),f=q.slice(1).join("\x3d");'"'===f.charAt(0)&&(f=f.slice(1,-1));try{var m=q[0].replace(g,decodeURIComponent);f=e.read?e.read(f,m):e(f,m)||f.replace(g,decodeURIComponent);if(this.json)try{f=JSON.parse(f)}catch(p){}if(b===m){k=f;break}b||(k[m]=f)}catch(p){}}return k}}a.set=a;a.get=function(b){return a.call(a,b)};a.getJSON=function(){return a.apply({json:!0},[].slice.call(arguments))};a.defaults={};
a.remove=function(b,c){a(b,"",l(c,{expires:-1}))};a.withConverter=g;return a}return g(function(){})});</script><script type="text/javascript" id="">(function(f){function h(){for(var a={},c=0;c<arguments.length;c++){var d=arguments[c],g;for(g in d)d.hasOwnProperty(g)&&(a[g]=d[g])}return a}function k(b,c,f){var g=a.session_id?a.session_id:a.session_cookie_key?d.get(a.session_cookie_key):void 0;f=h({session_id:g,company_id:a.company_id,attempt_id:a.attempt_id,test_id:a.test_id},f);b={product:a.product,event_name:b,event_value:c,params:f};var e;c={session_landing_url:d.get("session_landing_url"),session_referrer:d.get("session_referrer"),session_referring_domain:d.get("session_referring_domain")};
try{if(e=d.get("session_utm_params"))e=JSON.parse(e),c.session_utm_source=e.s,c.session_utm_medium=e.m,c.session_utm_campaign=e.c}catch(n){}e=c;c=a.use_cookie?{uid:d.get(a.uid_cookie_key),uid_token:d.get(a.uid_token_cookie_key)}:{uid:a.uid,uid_token:a.uid_token};e=h(b,e,c);b=new XMLHttpRequest;b.withCredentials=!0;b.open("POST",l);b.setRequestHeader("Content-Type","application/json;charset\x3dUTF-8");b.setRequestHeader("X-Requested-With","XMLHttpRequest");b.send(JSON.stringify(e))}var d=f.Cookies,
a={product:"candidate_site",use_cookie:!0,uid_cookie_key:"hackerrank_mixpanel_token",session_cookie_key:"session_id",uid_token_cookie_key:"metrics_user_identifier"},l=f.HR&&f.HR.development?"/metrics":"https:\/\/metrics.hackerrank.com\/metrics",m={getConfig:function(){return a},updateConfig:function(b){"object"===typeof b&&(a=h(a,b))},track:k};f.hrMetrics=m})(window);</script><script type="text/javascript" id="">function debounce(b,f,c){var a;return function(){var d=this,e=arguments,g=function(){a=null;c||b.apply(d,e)},h=c&&!a;clearTimeout(a);a=setTimeout(g,f);h&&b.apply(d,e)}}(function(){document.addEventListener("click",debounce(google_tag_manager["GTM-NLXX3SZ"].macro(11),500,!0),!0);document.addEventListener("mouseenter",debounce(google_tag_manager["GTM-NLXX3SZ"].macro(20),1E3),!0);window.jsTrackGoogleAnalytics&&"function"!==typeof window.jsTrackGoogleAnalytics||(window.jsTrackGoogleAnalytics=google_tag_manager["GTM-NLXX3SZ"].macro(23))})();</script><script type="text/javascript" id="">Element.prototype.matches||(Element.prototype.matches=Element.prototype.msMatchesSelector||Element.prototype.webkitMatchesSelector);"function"!=typeof Object.assign&&Object.defineProperty(Object,"assign",{value:function(d,f){if(null==d)throw new TypeError("Cannot convert undefined or null to object");for(var e=Object(d),b=1;b<arguments.length;b++){var a=arguments[b];if(null!=a)for(var c in a)Object.prototype.hasOwnProperty.call(a,c)&&(e[c]=a[c])}return e},writable:!0,configurable:!0});</script>
  <script src="./HackerRank_files/hackerrank_r_client-78526b5f.js.download"></script>

  

<script type="text/javascript" async="" src="./HackerRank_files/21db1c5c8b372aecca.js.download"></script><script src="./HackerRank_files/bundle.min.js.download" crossorigin="anonymous"></script><div><div class="hr-toaster hr-toaster-topCenter" style="top: 76px; right: 50vw; bottom: auto;"><span></span></div></div></body></html>
```
