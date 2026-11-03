# 깨알 · Kkaeal

**바탕화면 구석에 사는 픽셀 생물을 잡고, 키우고, 체육관에 보내는 Windows 게임입니다. 무료입니다.**
Kkaeal (깨알) — a free Windows game: pixel creatures live in the corner of your desktop — catch them, raise them, send them into gyms.

옛 이름은 Pixling 입니다. 파일·세이브 폴더 이름은 그대로라 새 판으로 덮어써도 생물이 남습니다. · Formerly Pixling — the file and save-folder names stay the same, so your creatures carry over.

이 저장소에는 **내려받을 파일만** 있습니다. 소스 코드는 없습니다.
This repository only hosts the downloads. There is no source code here.

## 받기 · Download

**[깨알.zip — 최신판 / latest](https://github.com/nobles92ts-ship-it/pixling-download/releases/latest/download/Kkaeal.zip)** (Windows · 약 78MB · 받으면 `Kkaeal.zip` 으로 저장됩니다 · saves as `Kkaeal.zip`)

Release 의 `Pixling.zip` 은 같은 exe 로, 게임 안 자동 업데이트가 씁니다. · `Pixling.zip` in each Release is the same build, used by the in-game updater.

지난 판은 [Releases](https://github.com/nobles92ts-ship-it/pixling-download/releases) 에 있습니다. · Older versions are under Releases.

안 받아지면 **예비 받기처**: [itch.io — nobles92ts-ship-it.itch.io/pixling](https://nobles92ts-ship-it.itch.io/pixling) (같은 파일) · If the download above doesn't work, the same file is on itch.io.

## 켜는 법 · How to start

1. zip 을 풉니다. · Unzip it.
2. `깨알` 폴더의 `깨알.exe` 를 두 번 누릅니다(예전 판의 `Pixling.exe` 도 같은 게임 · 같은 세이브). · Double-click `깨알.exe` in the `깨알` folder (an older `Pixling.exe` is the same game and save).
3. 파란 「Windows의 PC 보호」 창이 뜨면 **추가 정보 → 실행**. · If "Windows protected your PC" appears: **More info → Run anyway**.
   이 파일에 코드 서명이 없어서 뜹니다. · It appears because the file isn't code-signed.

## 알아 둘 것 · Good to know

| | |
|---|---|
| 세이브 · Save | `%APPDATA%\Pixling` — 새 판으로 덮어써도 남습니다 · survives updates |
| 입력 · Input | 누른 **횟수**만 셉니다. 어떤 키인지·무엇을 쳤는지는 세지 않습니다 · Counts presses only — never which key or what you typed |
| 인터넷 · Network | 켤 때 한 번 GitHub 에 새 판이 있는지 묻습니다(판 번호만 보냄) · 받기는 동의할 때만 · Asks GitHub once at start whether a newer version exists (sends only its version number); downloads only if you agree |
| 출석 · Attendance | v0.2.8 부터 게임이 켜져 있으면 하루 한 번 이름 없는 번호 · 판 번호 · 퀘스트 단계를 서버(Cloudflare)로 보냅니다. 하루 몇 명이 켰는지, 어느 단계까지 했는지만 셉니다. 번호는 날이 지나면 지우고 합계만 남깁니다. 끄는 설정은 없습니다. 이 표에 접속 주소(IP)는 저장하지 않습니다. 다만 Cloudflare 자체 접속 기록에는 남을 수 있습니다 · From v0.2.8, while running, the game sends an anonymous number, its version and your quest step to the server (Cloudflare) once a day. It only counts how many people played that day and how far they got. The number is deleted after that day and only totals remain. There is no setting to turn it off. That table stores no connection address (IP), though Cloudflare's own access logs may keep it |
| 이벤트 · Events | 켤 때와 켜져 있는 동안 1시간마다 서버에 이벤트가 있는지 묻습니다 · At start and every hour while running, the game asks the server whether an event is on |
| 랭킹 · Ranking | 처음에 꺼져 있습니다. 직접 참여를 켠 분만 팀 이름 · 태그 · 출전 팀과 도전 결과를 랭킹 서버로 보냅니다 · Off by default. Only players who turn it on send their team name, tag, active team and challenge results to the ranking server |
| 숨기기 · Hide | `\`(₩) 키 한 번 · One press of `\` |
| 지원 · Platform | Windows 전용 · Windows only |

## 출처 · Credits

비영리 팬메이드입니다. 디지몬 도트는 반다이, 포켓몬 도트는 닌텐도·게임프리크·크리처스의 것입니다. 전문은 zip 안의 `OUTPUT_NOTICE.md` 에 있습니다.
Non-commercial fan game. Digimon sprites belong to Bandai; Pokémon sprites belong to Nintendo, Game Freak and Creatures. The full notice is `OUTPUT_NOTICE.md` inside the zip.
