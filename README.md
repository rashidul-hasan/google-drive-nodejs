## Google Drive Nodejs

Upload/download files to google drive using nodejs.

### Installation

1. Clone this repo.

1. Create a google cloud platform project & enable google drive API. Follow [this](https://developers.google.com/drive/api/v3/quickstart/nodejs) link for details.(Click on the Enable Drive Api button on this page. It'll create a demo quickstart project & enable drive api & give you a credentials json file) After that you need to download the `credentails.json` file and place it on the root of the project.

1. Run `node index.js` This will give you an url. Copy the url & paste it on your browser. After authorizing your google account you will get a token.
Copy that token & paste it on the terminal.

1. A `token.json` will be generated. This file contains the token which will be used to call google drive APIs.

1. Now if you run `node index.js` you will see a list of files on your google drive.

### TODO

- [ ] Download file

- [ ] Upload file 