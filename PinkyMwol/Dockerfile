FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/Ikshwakupandey953/pink /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/Ikshwakupandey953/uploads
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
RUN npm install ytdl-core@latest
CMD ["node", "bot.js"]
