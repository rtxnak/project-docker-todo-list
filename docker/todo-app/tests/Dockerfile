
FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app
COPY . .
ADD node_modules.tar.gz ./
EXPOSE 3000
ENTRYPOINT [ "npm", "start" ]
