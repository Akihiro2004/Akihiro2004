<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:5b21b6,100:c084fc&height=200&section=header&text=Darrien%20Rafael%20Wijaya&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=Building%20AI%20that%20feels%20like%20someone%2C%20not%20something&descSize=16&descAlignY=58&animation=fadeIn" alt="Darrien Rafael Wijaya" width="100%"/>
</p>

<p align="center">
  <a href="https://darrienwijaya.vercel.app/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=A78BFA&center=true&vCenter=true&width=620&lines=Computer+Science+%26+Statistics+%40+BINUS+University;I+build+AI+companions+that+chat%2C+sing+and+play+games;Currently%3A+teaching+Mira+new+tricks" alt="Typing intro"/>
  </a>
</p>

<p align="center">
  <a href="https://darrienwijaya.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-1a1b27?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://darrienwijaya.vercel.app/mira"><img src="https://img.shields.io/badge/Meet_Mira-7c3aed?style=for-the-badge" alt="Meet Mira"/></a>
  <a href="https://www.linkedin.com/in/darrienwijaya/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:darrienwijaya@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## Hey, I'm Darrien

I'm a Computer Science and Statistics student at **BINUS University**, and most of my time goes into one question:

> *What does it take for an AI to feel natural to talk to?*

Not just answering questions, but remembering you, picking up on context, and doing things *with* you, like playing a game or singing a song. My main playground for that question is **Mira**.

---

## Meet Mira

<img src="./assets/miragif.gif" alt="Mira preview" width="300" align="right"/>

**Mira** is an experimental AI companion I built to feel as human as possible.

A raw LLM can talk, but it forgets you, doesn't really read the room, and can't *do* much. Mira is my attempt to fix that by layering things on top of the model:

- **Memory** so she remembers past conversations
- **Context awareness** so she understands what's going on
- **Decision rules** so she picks the right action for the moment
- **A voice**: text-to-speech for talking, a custom RVC model for singing
- **Hands**: integrations that let her play Chess and Minecraft

She lives on Discord, streams as a VTube Studio avatar, and is honestly more fun to hang out with than a typical chatbot.

<p>
  <a href="https://darrienwijaya.vercel.app/mira"><img src="https://img.shields.io/badge/Learn_more_about_Mira-7c3aed?style=flat-square" alt="Learn more about Mira"/></a>
</p>

<br clear="right"/>

### What she can do

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>Chat</h4>
      Talks naturally on Discord and other apps, remembers past conversations, adapts to context, and can role-play.
    </td>
    <td width="50%" valign="top">
      <h4>Sing</h4>
      Uses a custom-trained RVC voice model to sing in different tones and emotions, which sounds far more natural than plain TTS.<br/><br/>
      <a href="https://miratunes.vercel.app/"><img src="https://img.shields.io/badge/Listen_to_Mira_sing-blueviolet?style=flat-square" alt="Listen to Mira sing"/></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>Play games</h4>
      Plays Chess and Minecraft with you and talks while she plays, explaining her moves in real time.<br/><br/>
      <a href="https://youtu.be/KTo7M4Du3EI?si=g3DyjhQTrq8t-HDl"><img src="https://img.shields.io/badge/Watch_Mira_play_chess-success?style=flat-square" alt="Watch Mira play chess"/></a>
    </td>
    <td width="50%" valign="top">
      <h4>Be a character</h4>
      Connects to VTube Studio, so she's a live, animated avatar and not just a text box.
    </td>
  </tr>
</table>

### How she works

```mermaid
flowchart LR
    A([You say something]) --> B[Context understanding]
    M[(Memory)] <--> B
    B --> C{Decision rules}
    C -->|talk| D[LLM reply + TTS]
    C -->|sing| E[RVC singing voice]
    C -->|play| F[Chess / Minecraft]
    D --> G([Discord · VTube Studio])
    E --> G
    F --> G
```

I built Mira end to end:

- The **conversation flow** that lets her understand context
- A **memory system** that tracks past interactions
- **Text-to-Speech** for her spoken replies
- A **custom voice model** trained for singing
- The **Chess and Minecraft** integrations

### Mira in action

<p align="center">
  <img src="./assets/sing.gif" width="420" alt="Mira singing"/>
</p>

<p align="center">
  <img src="./assets/screenshots/chat1.jpg" width="260" alt="Mira chat screenshot 1"/>
  <img src="./assets/screenshots/chat2.png" width="260" alt="Mira chat screenshot 2"/>
  <img src="./assets/screenshots/chat3.jpg" width="260" alt="Mira chat screenshot 3"/>
</p>
<p align="center"><sub>Real conversations with Mira on Discord</sub></p>

<details>
<summary><b>Psst, I asked Mira to introduce me. Click to see what she said.</b></summary>
<br/>

> **You:** Mira, who made you?
>
> **Mira:** Darrien did! A CS and Statistics student at BINUS who really, *really* wants AI to feel less like a tool and more like a friend.
>
> **You:** What does Darrien actually work on?
>
> **Mira:** Me, mostly. Darrien built my memory so I don't forget you, the logic that helps me read the room, my speaking voice, and a singing voice too. Oh, and taught me chess and Minecraft. I explain my moves, so you can't say I didn't warn you.
>
> **You:** How do I get in touch?
>
> **Mira:** Easy. Send an email to [darrienwijaya@gmail.com](mailto:darrienwijaya@gmail.com), connect on [LinkedIn](https://www.linkedin.com/in/darrienwijaya/), or check out the [portfolio](https://darrienwijaya.vercel.app/). Tell Darrien I said hi!

</details>

---

## Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=python,firebase,discord,github,vercel&theme=dark" alt="Python, Firebase, Discord, GitHub, Vercel"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini"/>
  <img src="https://img.shields.io/badge/LLaMA-0467DF?style=flat-square&logo=meta&logoColor=white" alt="LLaMA"/>
  <img src="https://img.shields.io/badge/RVC_voice_models-7c3aed?style=flat-square" alt="RVC"/>
  <img src="https://img.shields.io/badge/Text--to--Speech-5b21b6?style=flat-square" alt="Text-to-Speech"/>
  <img src="https://img.shields.io/badge/VTube_Studio-ff6b9d?style=flat-square" alt="VTube Studio"/>
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Akihiro2004&theme=tokyonight" alt="GitHub Stats" height="160"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Akihiro2004&theme=tokyonight" alt="Top Languages" height="160"/>
</p>

---

<p align="center">
  <b>Thanks for stopping by!</b> If you're into AI companions, voice models, or AI that plays games, I'd love to chat.<br/>
  <sub>Mira says hi too</sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:c084fc,50:5b21b6,100:1a1b27&height=110&section=footer" alt="" width="100%"/>
</p>
