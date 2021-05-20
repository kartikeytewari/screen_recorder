# Screen Recording App

This is a simple screen recording app made using ElectronJS. To compile the app and run in your particular machine follow the commands:
- Clone the repository using the command <br>
    `git clone https://github.com/kartikeytewari/screen_recorder`
- Go to the folder <br>
    `cd screen_recorder`
- Build the file using <br>
    `npm build`
- Install electron-packager using <br>
    `npm install electron-packager --save-dev` <br>
    `npm install electron-packager`
- Build the app for your OS and architecture
    - For Windows on x86 architecture: <br>
        `electron-packager ./ screen_record --platform=win32 --arch=x64`
    - For Windows on arm64 architecture: <br>
        `electron-packager ./ screen_record --platform=win32 --arch=arm64`
    - For MacOSX on x86 architecture: <br>
        `electron-packager ./ screen_record --platform=darwin --arch=x64`
    - For MacOSX on arm64 architecture: <br>
        `electron-packager ./ screen_record --platform=darwin --arch=arm64`

Tech Stack Used:
- HTML5
- CSS3
- Javascript
- ElectronJS
- Electron forge
- Electron packager
- Git/Github
- Bulma CSS
