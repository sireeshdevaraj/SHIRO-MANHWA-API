# SHIRO-MANHWA API
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/sireeshdevaraj/SHIRO-MANHWA-API.svg)](https://GitHub.com/Naereen/StrapDown.js/pull/)
[![GitHub release](https://img.shields.io/github/release/sireeshdevaraj/SHIRO-MANHWA-API.svg)](https://GitHub.com/sireeshdevaraj/SHIRO-MANHWA-API/releases/)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/sireeshdevaraj/SHIRO-MANHWA-API/graphs/commit-activity)

Fan of Mangas,Manhwas and Manhuas? , Want a Category suggestions too?.Fetch requests from API and use it in your web/android/Discord Bot.

## LATEST VERSION

Here's the [![Latest release](https://badgen.net/github/release/sireeshdevaraj/SHIRO-MANHWA-API)](https://shiro.kuuhaku.space/)

## API END POINTS
- Get a random manhwa: [/manhwas](https://shiro.kuuhaku.space/manhwas)
- Get manhwas with category:
  - ROMANCE recommendation: [/manhwas?category=romance](https://shiro.kuuhaku.space/manhwas?category=romance)
  - ACTION recommendation: [/manhwas?category=action](https://shiro.kuuhaku.space/manhwas?category=action)
  - FANTASY recommendation: [/manhwas?category=fantasy](https://shiro.kuuhaku.space/manhwas?category=fantasy)
- Fan of OVER-POWERED Main character? No problem:
  - OP recommendation: [/op](https://shiro.kuuhaku.space/manhwas?category=over-powered)

## List of Categories
+ action
+ fantasy
+ comedy
+ over-powered
+ not-assigned
+ isekai
+ romance

## Want a Discord Bot that can do all these? with moderation and anime info?,no worries,Shiro is here.
![Discord Bots](https://top.gg/api/widget/909026192785551371.svg)


First ever Verified Manhwa Bot on Discord!
[Invite Shiro](https://top.gg/bot/909026192785551371)
[Make Embeds with Shiro](https://shiromanhwa.me/embed)
[Shiro Dashboard](https://shiromanhwa.me/)

![](https://user-images.githubusercontent.com/65805722/146648535-e1011b6c-8573-4675-a823-a80ea46cfec4.png)

Usage inside the Discord Bot

## USAGE
![Usage](https://i.imgur.com/bXWY0Jp.gif)
```python
import requests
response = requests.get('https://shiro.kuuhaku.space/manhwas')
print(response.json())
```

## JAVASCRIPT
```js
fetch("https://shiro.kuuhaku.space/manhwas?category=fantasy", {
  "method": "GET",
  "mode": "cors"
}).then(d=>d.json()).then(d=>console.log(d))
```

## RATE LIMITS
I'm Not a Fan of rate limits ,there are no restrictions, you can pull  as many requests as you can!! **FOR NOW**

## PROBLEM ACCESSING?

If you have any issues on using the API, feel free to create a new issue and I'll try to solve it as soon as possible!

## To-Do List
- [ ] Slice of Life Category
- [ ] Demon Lord Category
- [ ] Comedy End Point
- [ ] A Simple Dashboard for API
- [ ] Rate Limits
- [ ] API Private Keys
- [ ] Integrating AI
