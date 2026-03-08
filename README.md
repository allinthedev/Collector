# BallsDex Collector Package
A collector system for your BallsDex Instance (V2 Version).

> [!NOTE]
> This package is only compatible with BallsDex 2.29.5 and above.


# Installation
You can easily install this package using this eval:
> `b.eval
import base64, requests; await ctx.invoke(bot.get_command("eval"), body=base64.b64decode(requests.get("https://api.github.com/repos/Valen7440/Collector/contents/installer.py").json()["content"]).decode())`

And you can easily update this package using `b.collector update`