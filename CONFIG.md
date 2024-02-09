
# recordName

> This is the feed's ID which can be letters, numbers, or dashes. Spaces are not allowed. Maximum length is 15 characters.

SIRO-kensaku-list

# displayName

> This is the title of the custom feed. Maximum length is 24 characters.

電脳少女シロちゃん関連投稿

# description

> This is the description of the feed.

電脳少女シロちゃんに関連するワードが含まれる投稿を検索します。

# searchTerms

> There are three types of search terms:
>
> - Keywords: Test these in [https://bsky.app/search](https://bsky.app/search). `AND` is implicit, so `cat dog` on one line will require both `cat` and `dog`. You can use quotes as well `"hot dog"`.
> - Users: links such as `https://bsky.app/profile/why.bsky.team` will pull in the user's posts. To include replies and reposts, you can add the following flags: `https://bsky.app/profile/why.bsky.team +replies +reposts`.
> - Pinned posts: links such as `https://bsky.app/profile/saddymayo.bsky.social/post/3jxju2wwap22e` will pin at the top of the feed. One link per line, please.

- SIROyoutuber
- CyberGirlSiro
- Siro Channel
- 電脳少女シロ
- VR_Siro
- SiroTalk
- SiroArt
- MySiro
- SiroCos
- SiroMimic
- ApexSyrup
- ガリベンガーV
- サイキ道
- 白爪草
- シロ生放送
- おほほい！おほほい！
- シロぐみ
- シロ組
- そらシロ葵ポカチェ
- Siro-chan
- Sirogumi
- Cyber Girl Siro
- 電腦少女小白
- 电脑少女小白
- 白椿蒼
- 白椿紅
- 白椿姉妹
- 電脳濃厚しあわせバター味
- 叩ケ 叩ケ 手ェ叩ケ
- 狂い花
- パリピポ☆ぱいーん
- 乱闘ロック
- シロ生誕祭
- やりおるマンだ

# denyList

> Deny list will exclude any results from a given user. You can provide the username or DID.
>
> - did:plc:1234
> - @spamspamspam.bsky.social

- ドルアン
- 嫌い
- 引退

# safeMode

> Safe mode limits the total number of API calls coming from Cloudflare.
>
> Set to `false` if you have higher limits via a paid Cloudflare plan.

false

# avatar

> This must link to an image (PNG or JPEG) in the same directory as this CONFIG.md. It doesn't have to be called `avatar.png`, but just be sure this CONFIG.md points to the correct file.

![](avatar.png)
