FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/itsmebasil0/cat_bot2 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/itsmebasil8/httm
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
