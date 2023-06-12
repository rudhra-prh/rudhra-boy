FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/rudhra-prh/rudhra-boy /root/rudhra-prh
WORKDIR /root/rudhra-prh/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
