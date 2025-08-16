# pnpmの操作手順

## 前提条件

- [Node.js 20+](https://github.com/room202/react?tab=readme-ov-file#volta-%E3%82%92%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB)

## インストール

```bash
npm install -g pnpm
```

### おすすめ自作コマンド

※Claude Codeでコマンドを自作させる

```bash
# コードの文法チェック
pnpm lint

# TypeScript の型チェック
pnpm type-check

# カバレッジ
pnpm test:coverage

# コントラクト
pnpm contract
```
