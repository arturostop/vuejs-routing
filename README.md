# web-jobs

## Project setup
You can download this project by clicking on the green "Code" button and selecting "Download ZIP"
- Once decompressed on your computer, open command line and go to the project directory and open it on VS Code with: 
```
code .
```

### Compiles and hot-reloads for development
Once in VS Code, in the top menu find "Terminal" and open a terminal to run the next command:
```
npm run serve
```
When the process finish this should show a link to open the project on your default browser by Ctrl + click on it

![image](https://user-images.githubusercontent.com/22846310/201242903-ce4286c4-b514-4cea-ad68-455e4378aa12.png)

### Use JSON file as a test db
In another terminal, install the json server locally in the project with the command:
```
npm install json-server
```

Then, run the server with the following command, sending the directory of the json file as an argument:
```
npx json-server --watch data/db.json
```
![image](https://user-images.githubusercontent.com/22846310/202523865-0d5ca102-5f9a-4f2b-b4e4-66c7b346bb3d.png)
