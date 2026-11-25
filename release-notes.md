# Sinteya Setup Builder 0.1.0

Дата сборки: 2026-11-26 02:18
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

- `setup.exe` SHA-256: `0d8912a8d32897ee5fb7251f1e418f81cabcd14571e8e435b26dff6915fc57b1`
- payload SHA-256: `0790be23675bc39695310af4592ff2fa2ce0b6e191b9eb2e36c8efbd84e3baff`

Подпись: не подписан.

## Предупреждения
- setup.exe не подписан
