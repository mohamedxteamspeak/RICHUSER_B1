FROM fusuf/whatsasena:latest

RUN git clone https://github.com/mohamedxteamspeak/RICHUSER_B1 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Africa/Morocco
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
