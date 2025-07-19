# **BLANK-PROJECT-BASIC**


## 📦 Project Setup

### 1. Installation
- Install **Live Sass Compiler** extension (VS Code).
- Install **Live Server** extension (VS Code).

### 2. Configure

- Configure **Live Sass Compiler** settings: 
  Update your Live Sass Compiler: Settings with the following configuration:
<pre>

{
    "diffEditor.hideUnchangedRegions.enabled": true,
    "[php]": {
        "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
    },
    "settingsSync.ignoredExtensions": [],
    "liveSassCompile.settings.useNewCompiler": false,

    "liveSassCompile.settings.formats": [
        {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": "/assets/css"
        }
    ],
    "liveSassCompile.settings.generateMap": true
    
}

</pre>