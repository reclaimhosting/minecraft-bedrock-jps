# Minecraft Bedrock Server for Reclaim Cloud
In Minecraft, players explore a blocky, procedurally-generated 3D world, and may discover and extract raw materials, craft tools, build structures or earthworks, and depending on game mode, can fight computer-controlled "mobs", as well as either cooperate with or compete against other players in the same world. Minecraft servers allow players to play online or via a local area network with other people. This installs the Bedrock variant of Minecraft server. For information on compatibility see [https://minecraft.gamepedia.com/Bedrock_Edition](https://minecraft.gamepedia.com/Bedrock_Edition)

## Deploy to Reclaim Cloud
[Click here to deploy to Reclaim Cloud](https://app.my.reclaim.cloud/?app=minecraft-bedrock)

## Installation Instructions

You can find Minecraft Bedrock Server by clicking Marketplace and then Applications to show all or searching by name.

![Screen Shot 2020-06-04 at 11.29.34 AM|530x103](https://community.reclaimhosting.com/uploads/default/original/2X/6/66fffe086313e6975f16e1afe89e18c34510c6c8.png) 

![Screen Shot 2020-06-05 at 9.39.42 PM|690x339](https://community.reclaimhosting.com/uploads/default/optimized/2X/5/523508b380394728e9e122a18a85d6c1e81441b6_2_1380x678.png) 

Installing is as easy as setting an environment name for the server and region to install. After a few minutes your server will be up and running and ready to accept connections from players.

![Screen Shot 2020-06-05 at 9.40.45 PM|690x349](https://community.reclaimhosting.com/uploads/default/original/2X/e/e08dcbed64831969f1c2e83306f2b37cc17d5cd7.png) 

![Screen Shot 2020-06-05 at 9.41.05 PM|690x230](https://community.reclaimhosting.com/uploads/default/original/2X/e/ea0d461810f52f7f077066d146c945e5a434c22f.png) 

![Screen Shot 2020-06-05 at 9.41.51 PM|690x288](https://community.reclaimhosting.com/uploads/default/original/2X/f/fbe40c35f9be688e435169333b46c47887134d7c.png)  

To connect to the server you'll want to take note of the server hostname and port number provided. Open your client and access the server list.

![IMG_4039|690x387](https://community.reclaimhosting.com/uploads/default/optimized/2X/1/18c7f37ebbc62b73f929b41b0282d5da72375323_2_1380x774.jpeg) 

![IMG_4040|690x387](https://community.reclaimhosting.com/uploads/default/optimized/2X/3/3a7c3216b9ee807b04f2f15f57ab07d61168950e_2_1380x774.jpeg) 

Click Add Server and type in your server address and port number.

![IMG_4041|690x387](https://community.reclaimhosting.com/uploads/default/optimized/2X/c/c164e12ddb380d3f7c0840100b27b57fee4d35d1_2_1380x774.jpeg) 

Once the server is added and it has booted (Bedrock will take several minutes start up) you should be able to connect.

![IMG_4043|690x387](https://community.reclaimhosting.com/uploads/default/optimized/2X/c/c201ccf9b169a5a242e337e3f814eb2733bb44c0_2_1380x774.jpeg) 

![IMG_4044|690x387](https://community.reclaimhosting.com/uploads/default/optimized/2X/8/8d32415cad147ae2d556b9493402731dc9b9b2ec_2_1380x774.jpeg)  

Our implementation of Minecraft Bedrock Server uses Docker and you can customize a variety of settings through the use of environment variables. For a full list of documented options visit [https://hub.docker.com/r/itzg/minecraft-bedrock-server](https://hub.docker.com/r/itzg/minecraft-bedrock-server). To add variables to your container, after install you will click the gear icon and select Variables where you can add your own settings in key/value format.

![Screen Shot 2020-06-05 at 9.51.12 PM|690x236](https://community.reclaimhosting.com/uploads/default/optimized/2X/e/e3e973e6c0b40a95b5df1ed10dda666969e462f4_2_1380x472.png) 

![Screen Shot 2020-06-05 at 9.50.38 PM|690x389](https://community.reclaimhosting.com/uploads/default/optimized/2X/1/12ea79d3d1eeb4a4a6b2bf582bf883f12d4f25c6_2_1380x778.png) 

With any change to variables you will need to restart the server for those changes to take effect.

![Screen Shot 2020-06-05 at 11.45.18 AM|690x114](https://community.reclaimhosting.com/uploads/default/original/2X/e/e9661b7041f8bbaa019e278905889b0ad4f3187f.png)