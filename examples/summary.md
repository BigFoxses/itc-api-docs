#### [Back To Overview](https://github.com/fastlane/itc-api-docs/)

# List Apps

    https://itunesconnect.apple.com/WebObjects/iTunesConnect.woa/ra/apps/manageyourapps/summary/v2

```json
{
  "data":{
    "showSharedSecret":false,
    "cloudStorageEnabled":true,
    "gameCenterGroupLink":"/WebObjects/iTunesConnect.woa/ra/apps/manageyourapps/summary/gamescentergroup",
    "canCreateAppBundles":true,
    "canCreateIOSApps":false,
    "summaries":[
      {
        "adamId":"[App ID]",
        "name":"Your Awesome App",
        "vendorId":"99",
        "bundleId":"com.krausefx.app",
        "appType":"ios",
        "versions":[
          {
            "id":null,
            "version":"0.9.13",
            "state":"readyForSale",
            "stateKey":"readyForSale",
            "stateGroup":"readyForSale",
            "largeAppIcon":{
              "assetToken":"Purple3/v4/04/58/ed/....png",
              "thumbnailAssetToken":"Purple1/....png",
              "url":"https://is4-ssl.mzstatic.com/image....png",
              "thumbNailUrl":"https://is2-ssl.mzstatic.com....png",
              "sortOrder":null,
              "originalFileName":null
            },
            "supportedHardware":[
              "iPhone"
            ]
          },
          {
            "id":null,
            "version":"0.9.14",
            "state":"prepareForUpload",
            "stateKey":"prepareForUpload",
            "stateGroup":"preRelease",
            "largeAppIcon":{
              "assetToken":"Purple3/v4/04/58/ed/....png",
              "thumbnailAssetToken":"Purple1/....png",
              "url":"https://is4-ssl.mzstatic.com/image....png",
              "thumbNailUrl":"https://is2-ssl.mzstatic.com....png",
              "sortOrder":null,
              "originalFileName":null
            },
            "supportedHardware":[
              "iPhone"
            ]
          }
        ],
        "lastModifiedDate":1426959953000,
        "iconUrl":"https://is2-ssl.mzstatic.com/...png",
        "type":"ios"
      },
      ...
    ],
    "canCreateMacApps":false,
    "sharedSecretLink":"/WebObjects/iTunesConnect.woa/ra/apps/manageyourapps/summary/sharedsecret",
    "macBundlesEnabled":false,
    "catalogReportsLink":"/WebObjects/iTunesConnect.woa/ra/apps/manageyourapps/summary/catalogreports",
    "cloudStorageLink":"/WebObjects/iTunesConnect.woa/ra/apps/manageyourapps/summary/cloudstorage"
  },
  "messages":{
    "error":null,
    "info":null,
    "warn":null
  },
  "statusCode":"SUCCESS"
}
```

#### [Back To Overview](https://github.com/fastlane/itc-api-docs/)
