# ai-emotion-recognition-
Chart of emotions recognized using artificial intelligence algorithms

The application implements in a user interface sapUI5 (javascript https://sapui5.hana.ondemand.com/) artificial intelligence algorithms for facial recognition of emotions (source: https://github.com/justadudewhohacks/face-api.js/).

The video from the webcam is captured in the browser and is analyzed using artificial intelligence algorithms.
The following are automatically identified: dominant emotion,gender and age.
The identified emotions are centralized and displayed in two graphs:
- a pie chart to find out the weight of each identified emotion
- a pie chart for comparing emotional and neutral states.
The application allows emptying the recorded data buffer.

For successful execution on the local station you need to install node.js and copying the application to the public folder.

Install node.js (ubuntu)

sudo apt update

sudo apt install nodejs

sudo apt install npm
nodejs -v


Install local web server (system independent)

mkdir ai-emotion-recognition

cd ai-emotion-recognition

npm install -g express-generator

express -f

npm install

npm start


Open in browser (CHROME)
http://localhost:3000/index.html


