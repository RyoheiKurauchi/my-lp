# my-lp

Astro + Tailwind CSS で構築したランディングページです。

## 技術スタック

- [Astro](https://astro.build/) v6
- [Tailwind CSS](https://tailwindcss.com/) v4
- TypeScript

## セットアップ

```sh
npm install
```

## 開発サーバーの起動

```sh
npm run dev
```

ブラウザで `http://localhost:4321` を開くと確認できます。

## コマンド一覧

| コマンド          | 内容                                    |
| :---------------- | :-------------------------------------- |
| `npm run dev`     | 開発サーバーを起動 (`localhost:4321`)   |
| `npm run build`   | 本番用ビルドを `./dist/` に出力         |
| `npm run preview` | ビルド結果をローカルでプレビュー        |

## プロジェクト構成

```
/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Contact.astro
│   │   ├── Features.astro
│   │   ├── Header.astro
│   │   └── Hero.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       ├── global.css
│       ├── base.css
│       ├── primitives.css
│       └── semantic.css
└── package.json
```
