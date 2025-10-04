# メモ

## 初回起動

1. 必要データインストール

```
composer install
```

2. Docker 起動

```
./vendor/bin/sail up
```

3. Docker 起動後、マイグレーション

```
./vendor/bin/sail artisan migrate
```

4. アクセス確認
   http://localhost

## コマンド

### 停止

```
./vendor/bin/sail down
```

### 起動

```
./vendor/bin/sail up -d
```
