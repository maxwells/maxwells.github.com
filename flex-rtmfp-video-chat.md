---
layout: page
title: Flex RTMFP Video Chat Demo
---
{% include JB/setup %}

### Flex RTMFP Video Chat Demo 

Instructions
1. Direct a friend to this domain
2. Choose a Group ID that you will both use
3. Choose a unique username
4. Click "Connect..."
5. Once connected, click "Publish video..."
6. Chat

<div id="flashContent" style="width:500px;height:500px;">
</div>
      
<script type="text/javascript" src="assets/flex-rtmfp/swfobject.js">
</script>
<script type="text/javascript">
    // For version detection, set to min. required Flash Player version, or 0 (or 0.0.0), for no version detection. 
    var swfVersionStr = "11.1.0";
    // To use express install, set to playerProductInstall.swf, otherwise the empty string. 
    var xiSwfUrlStr = "";
    var flashvars = {};
    var params = {};
    params.quality = "high";
    params.bgcolor = "#ffffff";
    params.allowscriptaccess = "sameDomain";
    params.allowfullscreen = "true";
    var attributes = {};
    attributes.id = "Main";
    attributes.name = "Main";
    attributes.align = "middle";
    swfobject.embedSWF(
        "assets/flex-rtmfp/Main.swf", "flashContent", 
        "800px", "600px", 
        swfVersionStr, xiSwfUrlStr, 
        flashvars, params, attributes);
    // JavaScript enabled so display the flashContent div in case it is not replaced with a swf object.
    swfobject.createCSS("#flashContent", "display:block;text-align:left;");
</script>