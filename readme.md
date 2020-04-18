Steps to configure a project like this: 
1. npm init -y
2. npm install babel-cli@6 babel-preset-react-app@3
3. Create a src folder. Place all the JS files which has to be compiled in the folder. 
4. Run the following command: 
```
npx babel --watch src --out-dir . --presets react-app/prod
```
This command will watch all the changes in the src folder and will compile the files in the root folder, with the same name. 
5. Include root folder js files to the HTML
