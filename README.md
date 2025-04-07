# TagTidy
TagTidy can clean up your audio tags, making them well-formed

```
> tagtidy test.mp3

🕵️ detected ID3v1 tag
🐛 found 2 issues
⚙️ [Edit] [view Issues (--N)]

> I --1

🚨 invalid ID3v1 year, expected 0000 - 9999, found `2Ō2A`
| 
|        2Ō2A
|         ^ ^ --------- must be a digit
|
💁 note: modify the year to exact four digits
🧑‍🔧 fix: [Modify] [Discard]
⚙️ [Next (1/2)]

> M

enter a new value:
2025

👍 you fixed the issue, 1 issue left
⚙️ [view Issues] [Save] [Cancel]

> S

📁 saved

```
