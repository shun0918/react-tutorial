FROM node:latest

ARG REACT_PROJECT_NAME=reacttutorial

WORKDIR /usr/src/app
# cross-device link not permittedのエラー対策
# 参考https://qiita.com/muddydixon/items/7e7fa0c58d0fe495ce07
#RUN cd $(npm root -g)/npm \
#  && npm install fs-extra \
#  && sed -i -e s/graceful-fs/fs-extra/ -e s/fs\.rename/fs.move/ ./lib/utils/rename.js
RUN npm install -g create-react-app && create-react-app ${REACT_PROJECT_NAME}