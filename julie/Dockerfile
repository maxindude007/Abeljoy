FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/maxindude007/Abeljoy /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/Ajmal-Achu/maxindude007
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
