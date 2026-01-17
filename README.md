# README

2024/9/9
  - node 20.17.0
  - (npm 10.8.2)

```
npm install -g hexo
```

```
npm init
npm install --save-dev https://github.com/kmuncie/hexo-renderer-sass
```

```
hexo server
hexo new <article name>
hexo new draft <article name>
hexo new page <article name>
hexo generate
hexo deploy
```

```
git remote add -f git@github.com:tsupox/tsupox.github.io.git
```

```
{% asset_img hoge.jpeg %}
```

## Memo

- `youtube` plagin was deleted by `hexo v7.0.0` (see: [tag-plagins](https://hexo.io/ja/docs/tag-plugins#YouTube-v7-0-0%E3%81%A7%E5%89%8A%E9%99%A4%E3%81%95%E3%82%8C%E3%81%BE%E3%81%97%E3%81%9F))
  - use `hexo-tag-embed` instead of `youtube` plagin

## history

  - 2024/9/9 hexo version up from v5.0.0 to v7.3.0