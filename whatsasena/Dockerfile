FROM fusuf/whatsasena:latest

RUN git clone https://github.com/cu31/whatsasena1 /root/whatsasena1
WORKDIR /root/whatsasena1/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
