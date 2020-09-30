FROM node:12.18.4
RUN mkdir /app
WORKDIR /app
RUN npm install -g create-react-app \
                   create-react-native-app \
                   react-native-cli 
COPY ./app /app/
RUN yarn install