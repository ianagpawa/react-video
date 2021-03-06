# react-video
##### This repo is for my React video player project.    

### Quick Start
-Clone the repo: `git clone https://github.com/ianagpawa/react-video.git`


#### Dependencies
This app requires `Node` and `npm` to be installed on your system.  To install dependencies, while the terminal is in the project folder, execute the following command:
```
$   npm install
```

#### Requirements
This app requires an API key from [Youtube](http://www.youtube.com). The API key should be saved in a `secrets.js` file in the `src` folder.

##### Youtube
`secrets.js`
```
const API = "{'youtube': 'XXXXX'}"
module.exports = API
```


#### View the App
In order to view the app, navigate the terminal into the project folder, execute the command below, and open your browser to `http://localhost:8080`:
```
npm start
```

### What's included
Within the project folder, you will find the following files (image files not included):

```
react-video/
    ├── src/
    |   ├── components/
    |   |    ├── search_bar.js
    |   |    ├── video_detail.js
    |   |    ├── video_list_item.js
    |   |    └── video_list.js
    |   ├── index.js
    |   └── secrets.js
    ├── style/
    |   └── style.css
    ├── test/
    |   ├── components/
    |   |    └── app_test.js
    |   └── test_helper.js
    ├── .babelrc
    ├── .gitignore
    ├── index.html
    ├── package-lock.json
    ├── package.json
    ├── README.md
    └── webpack.config.js
```

## Creator

**Ian Agpawa**
[Github](https://github.com/ianagpawa)
 agpawaji@gmail.com
