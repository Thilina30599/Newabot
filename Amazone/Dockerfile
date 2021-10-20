FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Thilina30599/Newabot /root/ales
WORKDIR /root/ales/
ENV TZ=Europe/Istanbul
RUN yarn install --no-audit

CMD ["node", "bot.js"]
