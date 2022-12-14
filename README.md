# [threejs-first-app](https://sctlcd.github.io/threejs-first-app/)

<br />
<img src="https://github.com/sctlcd/threejs-first-app/blob/main/design/threejs-first-app-mockup-presentation-min.png" alt="three-js-first-app" width="800">
<br />

---

# Table of Contents <a name="tableOfContents"></a>

1. [Introduction](#introduction)

2. [Run the project locally](#runLocally)

3. [Deployment](#deployment)
	- [Deployment – Run locally](#deploymentRunLocallydeploymentRunLocally)
	- [Deployment – Live website](#deploymentLiveWebsite)

4. [Credits](#credits)
	- [Media](#media)
---

## Introduction <a name="introduction"></a>

Creating a planet and its satellites with Three.js

Back to [top](#tableOfContents)

---

## Run the project locally <a name="#runLocally"></a>

Install Node.js [five-server](https://www.npmjs.com/package/five-server), a development server with live reload capability. 

  - To install:
    
    ```
      # Remove live-server (if you have it)
      npm -g rm live-server

      # Install five-server
      npm -g i five-server
    ```

  - To update (from time to time)
        
    ```
      # Update five-server
      npm -g i five-server@latest
    ```

  - To run (from your local directory):
        
    ```
      five-server . -p 8000
    ```

  - Plugins for popular code editors
  Some code editors have plugins which will spawn a simple server on demand.

      - [Five Server](https://marketplace.visualstudio.com/items?itemName=yandeu.five-server) for Visual Studio Code.
      - [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for Visual Studio Code.
      - [Live Server](https://atom.io/packages/atom-live-server) for Atom.

Back to [top](#tableOfContents)

---

## Deployment <a name="#deployment"></a>
### Deployment – Run locally <a name="#deploymentRunLocally"></a>

1. Prerequisite:  
    - Make sure [Node](https://nodejs.org/en/) and [NPM](https://www.npmjs.com/) are installed on your computer. You can download both at nodejs.org (NPM is included in your Node installation).  
    - Please see `.nvmrc` file at the root of `threejs-first-app` repo.  
    - Using nvm, a Node Version Manager is recommended as it helps you manage and switch between different Node versions with ease. It provides a command-line interface where you can install different versions with a single command, set a default, switch between them, etc.
2. In GitHub click on the repository nammed [threejs-first-app](https://github.com/sctlcd/threejs-first-app)
3. Clone the repository locally. Run

    ````
      git clone https://github.com/sctlcd/threejs-first-app.git
    ````

4. Install all modules listed as dependencies in package.json
 
    ```
      cd threejs-first-app
      npm i 
    ```

    note: in this app
    - [three](https://www.npmjs.com/package/three) - **JavaScript 3D library**

5. Install Node.js [five-server](https://www.npmjs.com/package/five-server), a development server with live reload capability. 

    - To install:
        
        ```
          # Remove live-server (if you have it)
          npm -g rm live-server

          # Install five-server
          npm -g i five-server
        ```

    - To update (from time to time)
        
        ```
          # Update five-server
          npm -g i five-server@latest
        ```

    - To run (from your local directory):
        
        ```
          five-server . -p 8000
        ```

    - Plugins for popular code editors
    Some code editors have plugins which will spawn a simple server on demand.

        - [Five Server](https://marketplace.visualstudio.com/items?itemName=yandeu.five-server) for Visual Studio Code.
        - [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for Visual Studio Code.
        - [Live Server](https://atom.io/packages/atom-live-server) for Atom.

Back to [top](#tableOfContents)

---

### Deployment - Live Website <a name="#deploymentLiveWebsite"></a>

[threejs-first-app](https://sctlcd.github.io/threejs-first-app/) live website is currently deployed on [GitHub pages](https://pages.github.com/) using the `main` branch on GitHub. Once you have the project setup locally, you can proceed to deploy it remotely.

1.	In GitHub click on your repository to open it.
2.	Find the 'settings' tab and click on it.
3.	In the left menu select 'Pages'
4.	In Build and deployment section, under 'Source' choose a branch `Deploy from a branch`, under Branch chose `main` and `/(root)` then press the Save button
5.	Wait a couple of minutes and refresh the page then you will see a URL to your live site.

=> Live link: https://sctlcd.github.io/threejs-first-app/

Back to [top](#tableOfContents)

---

## Credits <a name="credits"></a>

### Media <a name="media"></a>

- [favicon.ico](https://www.flaticon.com/free-icon/planet_3336074?term=planet&related_id=3336074) - [Flaticon](https://www.flaticon.com/) | copyright [Freepik](https://www.freepik.com)

- [scene background texture](https://i.imgur.com/P7z3aw1.jpeg) - [imgur](https://imgur.com/) | copyright [Jgoodz](https://imgur.com/user/Jgoodz)

- [box texture](https://i.imgur.com/sSZc7Yr.png) - [imgur](https://imgur.com/) | copyright [SmartassCody](https://imgur.com/user/SmartassCody)

- [sphere texture](https://i.imgur.com/5FbL240.jpeg) - [imgur](https://imgur.com/) | copyright [kebuenowilly](https://imgur.com/user/kebuenowilly)

Back to [top](#tableOfContents)

---