yarn start

API

docker run --name mymongodb -d -p 27017:27017

Start MongoDB server:

1. Open a terminal or command prompt and run the following command to start the MongoDB server:

   - On: `"C:\Program Files\MongoDB\Server\version\bin\mongod.exe" --dbpath="C:\data\db"`
   - On macOS/Linux: `mongod --dbpath /data/db`

Replace "version" with your installed MongoDB version, and ensure the data directory exists.

2. Connect to MongoDB in VS Code:

   a. Open the Command Palette (Ctrl+Shift+P) and type "MongoDB: Connect".
   b. Enter the connection string: For a local MongoDB server, use "mongodb://localhost:27017".
   c. Press Enter, and you should see your MongoDB connection in the "MongoDB" tab on the left sidebar.

client side - app
yarn init -y
yarn add nuxt @nuxtjs/axios @nuxtjs/vuetify

