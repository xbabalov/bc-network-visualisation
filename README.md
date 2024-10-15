# Bachelor Thesis - Basic application for integration and visual exploration of open biomedical networks
https://is.muni.cz/auth/th/b9179/

**Included files**
1. dbms.dump
2. app.zip

**Loading the database with Neo4j Desktop**
1. Install Neo4j Desktop from https://neo4j.com/download/
2. Create a new project
3. Add file into the project - add dbms.dump file 
4. In the file options create new dbms from dump
5. Start the new dbms
6. The connection information can be found in the dbms details tab while it is running

**Application setup**
1. Download Node from https://nodejs.org/en/ (if you do not have it yet)
2. Unzip app.zip
3. In the src folder, in App.vue file in `data()` properties double check the connection properties so they fit your running database connection information:
-*protocol*
-*host*
-*port*
-*username*
-*password*
4. Open command line and enter into the app folder
5. Run `npm install -g npm`
6. Run `npm run serve`
7. Open the corresponding localhost page in your browser
