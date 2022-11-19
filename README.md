### Hi there 👋

<!--
**narcisista3g/narcisista3g** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<div align="center" id="top">
  <h2>
    <i>Developer Back End</i>
  </h2>
  <a href"https://github.com/narcisista3g?tab=followers">
    <img alt="GitHub followers" src="https://img.shields.io/github/followers/narcisista3g?colorA=1e1e28&colorB=c9cbff&logo=Github&style=for-the-badge" />
  </a>
  <a href="https://twitter.com/strange_silva">
     <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/strange_silva?colorB=c6aae8&colorA=1e1e28&label=Follow&logo=twitter&logoColor=white&style=for-the-badge">
  </a>
  <a href="https://discord.gg/6cr4MnsCYY">
    <img alt="Discord server"  src="https://img.shields.io/discord/1039840281094266910?colorA=1e1e28&colorB=c6aae8&label=Discord&logo=discord&logoColor=white&style=for-the-badge">
  </a>
</div>

<br />

<div style="width: 10px;"></div>

<a  href="https://discord.gg/6cr4MnsCYY"><img align="right" src="https://discordapp.com/api/guilds/1039840281094266910/widget.png?style=banner4"/></a>

```typescript
import { message } from "narcisistajs";

class Narcisista {
  private message: string[];

  contructor() {
    this.message = ["ts", "js", "py"]
  };

  public async function SendMessage(): Promise<string> {
    const send = await message();

    const msg = send(this.message);

    return msg;
  };
};

export { Narcisista };
```

<br />

<h4 align="center">

![metrics](./github-metrics.svg)

</h4>
