FROM fusuf/whatsasena:latest

RUN git clone https://github.com/MhmdMukarram1/CHINTU-WA-BOT /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Afx-Abu/Abu-media

CMD ["node", "bot.js"]
