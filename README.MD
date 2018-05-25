ELECTORN SEED

This is a Electron seed you can ues this project to convert any angular-cli (web app) app into elctron app (Desktop App). 

TO USE

Replace dist folder to your Angular project's dist folder.

Update src/index.html <base href="./">

(you can generate dist folder by using command npm run build prod )

How to run the project

1. Run npm install
2. Run npm start

Generate Windows packages.

electron-packager . demoApp --overwrite --asar=true --platform=win32 --arch=ia32 --icon=assets/icons/win/icon.ico --prune=true --out=release-builds --version-string.CompanyName=CE --version-string.FileDescription=CE --version-string.ProductName="demoApp"

https://www.christianengvall.se/electron-packager-tutorial/

https://angularfirebase.com/lessons/desktop-apps-with-electron-and-angular/
