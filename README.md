# bulma-starter

## First time installation

### Prerequisites
* nodejs >= 14.17.6 ([https://nodejs.org/en/download/](https://nodejs.org/en/download/))
```bash
$ node -v
```

### Installation
You are github user `my-username`.
* Create a empty github repository for your project.
* Call this repository something like `my-repository`.
* Copy the repository url to the clipboard.

```bash
$ git clone https://github.com/peddn/bulma-starter.git my-repository
$ git remote set-url origin https://github.com/my-username/my-repository.git
$ cd my-repository
$ npm install
```
* Edit `README.md`.
* Commit your changes.
* Push your changes to your github repository.


## Workflow

Open two terminals.

### Start development environment
in the first terminal:
```bash
$ npm run development
```
This starts the development server with automatic live rebuild and reload.  

### Build for production
in the second terminal:
```bash
$ npm run production
```
This builds the application and exports the the `.html`, `.css` and `.js` files to the `dist` directory. These files are ready to upload to the production webserver.

Enjoy!
