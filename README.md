## javascript-cv

This is the official DevOps JS personal website built using ReactJS and [Bulma](https://bulma.io/) as the CSS framework.
The personal information on the website is populated from a json file that follows the [JSON Resume](https://jsonresume.org/schema/) open source standard.

## Getting the project to your local machine
For getting started you can clone the repository via your IDE, Visual Studio Code

<img src="https://gitlab.com/livingdevops/jump-start/01_SoftwareDevelopment/-/blob/master/1-2_LAB_Javascript_App/README_files/Screenshot_2020-08-13_at_15.25.46.png" width="300">

## Understanding the structure of the application

- dependencies
- sources
- navigating in the IDE
- build commands

## Customizing it
Feel free to fork this project and update it with your own information and style. Just update the ´src/resume.json´ with your personal information.

Update the resume.json with your personal information (check JSON Resume)
Install dependencies and run the application:

```bash
npm install
```
You can also test the app with a development server, just run:

```bash
npm start
```
The application will now be available via http://localhost:3000

A pdf can be created based on pdf/index.js settings
```bash
nohup npm start & sleep 10 && node pdf/pdf.js 
```

With a Windows machine, you can run ```npm start``` and ```node pdf/pdf.js``` sequently in separate Powershell terminals. 

## License
MIT
