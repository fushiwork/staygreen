# StayGreen

Away from your desk. Your status stays green.

StayGreen is a small Windows app from [Fushi Work](https://fushiwork.com). When you step away for a few minutes, it keeps your Teams, Slack and Discord status green, so your teammates know you're still around. When you come back and move the mouse, it stops.

**[Download StayGreen](https://fushiwork.com/dl/staygreen)** · [Get Pro](https://ko-fi.com/s/a91d5be58b) · [Website](https://fushiwork.com/en/apps/staygreen/) · [All releases](https://github.com/fushiwork/staygreen/releases)

Both editions are free. Windows 10 and 11, 64-bit. One file, no install, no account.

## How it works

- **When you step away:** after a minute of no activity, it sends a small signal so your PC knows someone's still there. It doesn't type or click anything.
- **When you come back:** touch the mouse or keyboard and it stops right away.
- **After work:** set your work days, hours and lunch break. Outside those times it does nothing.

## Basic and Pro

| | Basic | Pro |
|---|---|---|
| Keeps you green, stops when you're back | ✅ | ✅ |
| Work hours, days and breaks | ✅ | ✅ |
| Tray icon, Thai / English, start with Windows | ✅ | ✅ |
| Signal interval and idle wait | 60 s | Adjustable |
| Human-like timing | - | ✅ |
| Activity graph, today summary, hourly heatmap | - | ✅ |
| 12-month activity calendar | - | ✅ |
| CSV export | - | ✅ |

Pro is on Ko-fi with pay what you want - enter 0 if you like.

## First run

Windows may say "Windows protected your PC" because the app isn't code-signed yet. Click **More info**, then **Run anyway**. Some antivirus tools may also flag it by mistake. Each release lists a SHA-256 checksum so you can check the file:

```powershell
Get-FileHash .\StayGreen.exe -Algorithm SHA256
```

While StayGreen is keeping you green, Windows won't lock the screen or go to sleep on its own. Press Win + L if you walk away for long.

## Privacy

Everything stays on your PC. Settings and activity live in `%APPDATA%\StayGreen`, and nothing is sent anywhere.

## Contact

Questions or ideas: [hello@fushiwork.com](mailto:hello@fushiwork.com)

Some companies don't allow tools like this, so check your company's rules before using it.

Microsoft Teams, Slack and Discord are trademarks of their owners. StayGreen is not affiliated with them.
