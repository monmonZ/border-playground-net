# border-playground-net
<hr>

## 環境構築
以下の環境で作成  
- PC: Mac OS BigSur (M1)  
- IDE: IntelliJ IDEA  
<hr>

### 各種ツールをインストール
#### yarnをインストール
<pre>
$ brew install yarn
</pre>
#### nodebrewをインストール
node.jsをバージョン管理するためnodebrewを導入
<pre>
$ brew install nodebrew
</pre>
#### node.jsをインストール
<pre>
$ nodebrew install-binary latest
$ node -v
v12.8.0
$ 
</pre>
<hr>
### git clone
このリポジトリをgit cloneする
<hr>
### Vue コマンド追加
<pre>
$ npm i -g @vue/cli @vue/cli-init
</pre>

### プロジェクト作成
<pre>
$ vue init nuxt-community/starter-template border-playground-net

? Project name border-playground-net
? Project description Nuxt.js project
? Author m0nmonZ <21101407+monmonZ@users.noreply.github.com>

   vue-cli · Generated "border-playground-net".

   To get started:

     cd border-playground-net
     npm install # Or yarn
     npm run dev

$
</pre>

## Build 

### border-playground-net

> Nuxt.js project

### Build Setup

``` bash
# install dependencies
$ npm install # Or yarn install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout the [Nuxt.js docs](https://github.com/nuxt/nuxt.js).


