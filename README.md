# antd-iconfont-issue
antd iconfont localization issue

# fix
``````
"extraBabelPlugins": [
    "transform-runtime",
    ["import", [{ "libraryName": "antd", "style": true }]]
  ],
  "env": {
    "development": {
      "theme": {
        "@icon-url": "'/iconfont/iconfont'"
      },
      "extraBabelPlugins": [
        "dva-hmr"
      ]
    },
    "production": {
      "theme": {
        "@icon-url": "'/./iconfont/iconfont'"
      }
    }
  }
  ``````
