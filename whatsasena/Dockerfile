FROM fusuf/whatsasena:latest

RUN git clone https://github.com/f3lixbl4ck/blackasena /root/blackasena
WORKDIR /root/blackasena/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
