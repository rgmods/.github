<p align="center">
  <a href="#">
    
  </a>
  <p align="center">
   <!-- <img width="300" height="300" src="https://raw.githubusercontent.com/rgmods/.github/main/profile/rgmods.png" alt="Logo"> -->
  </p>
  <h1 align="center"><b>RG Mods</b></h1>
  <p align="center">
    <br />
    <a href="https://rgmods.com"><strong>rgmods.com</strong></a>
    <br />
    <br />
    <b>Download for </b>
    macOS
    ·
    Windows
    ·
    Linux
    <br />
    <i>~ Links will be added once a release is available. ~</i>
  </p>
</p>
RG Mods is an open source development framework for rXg mods/applications. Ttilizing rXg's API interface, we allow users to create and publish customizable mods/applications to the rXg community for other engineers to utilize, provide feedback, and expand upon.
<br/>
<br/>

> NOTE: RG Mods is under active development, most of the listed features are still experimental and subject to change.

Using our development framework, you can create custom mods/applications using rXg's vastly unique features and capabilities with IFTTT ideology to interact with third party APIs and applications such as Discord, Google Suite Products, Slack, etc. The possibilities to create custom applications around rXg are endless.

<p align="center">
  <a href="">
    <img src="https://img.shields.io/discord/991906436948963489?label=Discord&color=5865F2" />
  </a>
  <img src="https://img.shields.io/static/v1?label=Licence&message=MIT&color=000" />
  <br />
</p>

# Motivation

After browsing through the RGNets Reddit page, it seemed as if people had features and use cases through rXg's capabilities that they wanted to share, but wasn't so simple for any user to replicate their project. Then came the idea, a all in one development tool that allowed users to create mods/applications that integrate seemlesly with rXg's architecture, and made it easier to share and implement your project with others.

# Architecture
- Consistent Local Development
  - Docker Compose makes local development consistent for your whole team, eliminating "works on my machine".
- Extensible
  - Built on the solid foundation of Next.JS, you can easily extend features based on use-cases.
- GraphQL + Prisma
  - Easily use Prisma data models in GraphQL, while keeping complete control over what is exposed.
- Type Safety
  - We deliver unparalleled type safety, from defining models in a Prisma schema, all the way to querying for them in the client.
- The core (`rgmcore`) is written in pure JavaScript.

## Monorepo structure:

### Apps:

- `desktop`: An electron application.
- `web`: A Next.JS webapp.

### Core:

- `core`: The service core, referred to as `rgmcore`. Contains secure database and networking logic that can be deployed in a variety of host applications.
