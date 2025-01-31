---
description: "Demonstrate the deployment workflow of WebView2 with WiX Burn Bundle."
extendedZipContent:
  -
    path: SharedContent
    target: SharedContent
  -
    path: LICENSE
    target: LICENSE
languages:
  - cpp
page_type: sample
products:
  - microsoft-edge
urlFragment: WV2DeploymentWiXBurnBundleSample
---
# WiX Burn Bundle to deploy the WebView2 Runtime

<!-- only enough info to differentiate this sample vs the others; what is different about this sample compared to the sibling samples? -->
This sample, **WV2DeploymentWiXBurnBundleSample**, demonstrates how to deploy the Evergreen WebView2 Runtime with your app.  This sample creates a WiX installer for [WebView2APISample](../WebView2APISample/README.md) and uses WiX Burn Bundle to chain-install the Evergreen WebView2 Runtime.

For more information about this sample, see [WiX Burn Bundle to deploy the WebView2 Runtime](https://review.docs.microsoft.com/microsoft-edge/webview2/samples/wv2deploymentwixburnbundlesample).
