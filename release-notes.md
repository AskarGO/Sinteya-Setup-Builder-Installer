# Sinteya Setup Builder 0.1.0

Дата сборки: 2026-11-26 03:10
Издатель: Sinteya

## Что нового

Первый установщик Sinteya Setup Builder.

## Требования

- .NET Desktop Runtime не требуется (self-contained).
- WebView2 Runtime: не требуется.
- Windows 10 (1903+) или Windows 11.

## Установка

1. Запустите `setup.exe`.
2. Примите лицензионное соглашение.
3. Выберите папку и параметры.
4. Нажмите «Установить».

Тихая установка:

```
setup.exe /S /ACCEPTEULA=1 [/DIR="..."] [/LOG="..."]
```

Удаление: `uninstall.exe` (данные сохраняются), `uninstall.exe /S /PURGEDATA=1` — удалить данные.

## Контрольные суммы

- `setup.exe` SHA-256: `61e739089363a6aaf31d9002e4ba477d925706013ee124b3d8b3b65ec6c41662`
- payload SHA-256: `72e48216badbe8544d733084ed3cb48438439c479baeadba7ab9baff931459a6`

Подпись: не подписан.

## Предупреждения
- setup.exe не подписан
