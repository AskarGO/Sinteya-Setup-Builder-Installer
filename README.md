# Sinteya Setup Builder

Установщик **Sinteya Setup Builder 0.1.0** для Windows 10/11 x64.

Self-contained: .NET Desktop устанавливать не нужно. Установка per-user, без администратора.

## Скачать

Последний установщик: [Releases](https://github.com/AskarGO/Sinteya-Setup-Builder-Installer/releases/latest)

- файл: `setup.exe`
- размер: 66 448 384 байт
- SHA-256: `0d8912a8d32897ee5fb7251f1e418f81cabcd14571e8e435b26dff6915fc57b1`

Проверка:

```powershell
Get-FileHash .\setup.exe -Algorithm SHA256
```

## Установка

Запустить `setup.exe`, принять лицензию, выбрать папку, установить.
Ярлыки создаются в меню «Пуск» и на рабочем столе.

Тихая установка:

```powershell
setup.exe /S /ACCEPTEULA=1 /DIR="D:\Apps\Sinteya Setup Builder" /LOG="C:\Temp\sb.log"
```

Удаление:

```powershell
uninstall.exe /S
uninstall.exe /S /PURGEDATA=1
```

Данные по умолчанию сохраняются; `/PURGEDATA=1` удаляет их.

## Подпись

Установщик **не подписан**. SmartScreen может показать «Неизвестный издатель» — проверьте SHA-256 выше.

## Лицензия

Проприетарная, короткий EULA на английском и русском; полный текст показывается в установщике и лежит в `LICENSE.md`. Установщики, созданные вами с помощью Sinteya Setup Builder, принадлежат вам.

## Исходники

Исходный код находится в приватном репозитории и здесь не публикуется.