**The App is build using Express and MongoDb and we have used pug as a server side template. This git repo only contain backend of the main app you can check the frontend part from the following link.** https://topgadgets.herokuapp.com/

**more detail about files and working of command and database schemas are given below.**

**The Schema for MongoDb is given in the { DataModel } folder do check it to setup data models**

Take Mobile Image Width 500 x 500 and background as #ced2de

Take Laptop Image Width 430 x 270 and background as #ced2de

to import/delete data from json file into db follow the command:
node Data/import-dev-data.js {COMMAND}
if(import) --> use {COMMAND} == --import
if(delete) --> use {COMMAND} == --delete

Example : if you want to upload the data then :
**node Data/import-dev-data.js --import**

to import/delete data from json file into DB :
node Data/import-dev-data.js --import-mobile
if(import) --> use {COMMAND} == --import-mobile
else --delete-mobile

Example : if you want to delete the data of mobile then :
**node Data/import-dev-data.js --delete-mobile**

**Do check the import-dev-data.js file for better understanding :**

**for config.env file do this :**

NODE_ENV=development
PORT = 5500
USERNAME = <your_mongoDb_username>
DATABASE = <your+monogDb_link>
DATABASE_PASSWORD = <your_mongoDb_password>

**install the same dependencies given in package.json and you are ready to go!!!**
