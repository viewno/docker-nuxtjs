# イメージの指定
FROM node:lts-alpine

WORKDIR /app

# ホストがlinuxの場合のみownerがrootになるので対策（1000はホストubuntu uid）
# mac windowsは必要なし
#USER 1000:1000

RUN yarn global add nuxt
# RUN npm install --save-dev nuxt

ENV CHOKIDAR_USEPOLLING=true



ENV HOST 0.0.0.0

EXPOSE 3000 3001



