<h1 align="center">PlatformKit Messenger</h1>

<p align="center">
Self-Hosted Audio/Video/Text Chat
</p>

<p align="center">
Peer-to-Peer Video Chat & Screen Sharing
</p>

<div align="center">
    <img src="https://raw.githubusercontent.com/platform-kit/chat/master/assets/images/screenshot.png" style="border-radius:4px; margin:auto;max-width:300px;"  width="400"/>
</div>

**Built with:** <br>

<p float="left">
<img src="https://img.shields.io/badge/Node.js-ebf5fb?style=for-the-badge&logo=nodedotjs"/>
<img src="https://img.shields.io/badge/Express.js-ebf5fb?style=for-the-badge&logo=express&logoColor=000" />
<img src="https://img.shields.io/badge/Vue.js-ebf5fb?style=for-the-badge&logo=vuedotjs" />
</p>

**Deploy with:** <br> 
<p float="left">
<img src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white"/> <img src="https://img.shields.io/badge/Digital_Ocean-0080FF?style=for-the-badge&logo=DigitalOcean&logoColor=white" /> <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=Render&logoColor=white"/> 
</p>

**License:** <br> <img src="https://img.shields.io/badge/License-000000?style=for-the-badge"/><img src="https://img.shields.io/badge/MIT-222?style=for-the-badge&logoColor=white"/>

## Features

- Free peer-to-peer audio calls, video calls, screensharing and chat via WebRTC
- Connect to private STUN/TURN servers via Twilio
- UI & API can be easily customized

## Local Development

Clone the project

```bash
  git clone https://github.com/platform-kit/messenger pk-messenger
```

Go to the project directory

```bash
  cd pk-messenger
```

Install dependencies

```bash
  npm install 
```

Start the server

```bash
  npm run start
```

Alternatively you can run the application using docker with: 

```bash
  docker-compose up
```

A local instance is now running at `https://localhost:3000`

## Configuration

Before use, you will need to add the following environment variables to your .env file

```env
ALLOWED_ORIGIN=localhost:3000
TWILIO_ACCOUNT_SID=
TWILIO_AUTH_TOKEN=
```

## Deployment

To deploy to the cloud, simply click one of the buttons below.

<a href="https://heroku.com/deploy?template=https://github.com/platform-kit/messenger" target="_blank"><img src="https://img.shields.io/badge/Deploy%20to%20Heroku→-430098?style=for-the-badge&logo=heroku&logoColor=white"/></a> <a href="https://cloud.digitalocean.com/apps/new?repo=https://github.com/platform-kit/messenger/tree/main" target="_blank"><img src="https://img.shields.io/badge/Deploy%20to%20Digital_Ocean→-0080FF?style=for-the-badge&logo=DigitalOcean&logoColor=white" /> </a> <a href="https://render.com/deploy?repo=https://github.com/platform-kit/messenger" target="_blank"> <img src="https://img.shields.io/badge/Deploy%20to%20Render→-46E3B7?style=for-the-badge&logo=Render&logoColor=fff"/> </a> 