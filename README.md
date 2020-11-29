# kintone-plugin-customize-template

kintoneプラグインカスタマイズでよく使う環境のテンプレ

- ESlint
- Webpack
- Babel
- webpack-plugin-kintone-plugin

※ ESlintはVSCodeの拡張を使う前提

## How to Use

### クローン and インストール

```bash
git clone https://github.com/RyBB/kintone-plugin-customize-template

npm install
```

### 秘密鍵の作成

create-pluginやplugin-packerを利用してください

```bash
# ディレクトリ構造例
├── README.md
├── package-lock.json
├── package.json
├── private.ppk
├── scripts
│   └── npm-start.js
├── src
│   ├── css
│   │   ├── 51-modern-default.css
│   │   ├── config.css
│   │   └── desktop.css
│   ├── html
│   │   └── config.html
│   ├── image
│   │   └── icon.png
│   ├── js
│   │   ├── config.js
│   │   ├── desktop.js
│   │   └── dist
│   │       ├── config.js
│   │       └── desktop.js
│   └── manifest.json
└── webpack.config.js
```

### パッケージング and アップロード

- パッケージング

```bash
npm run build
```

- アップロード

```bash
npm run upload
```

- watch (パッケージングとアップロード同時)

```bash
npm start
```
