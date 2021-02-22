# ThreeJsSeanBradley

[How Modiface utilized TensorFlow.js in production for AR makeup try on in the browser](https://blog.tensorflow.org/2020/02/how-modiface-utilized-tensorflowjs-in-ar-makeup-in-browser.html 'Users can simply visit a L’Oreal brand product page, and instead of just browsing through product photos, can actually see how the product will look on them before they purchase it.')

[TensorFlowDemo, replace WebGL with ThreeJS](https://storage.googleapis.com/tfjs-models/demos/face-landmarks-detection/index.html 'I want to replace WebGL with ThreeJS in the livedemo')

[Constructing a 3D Face Mesh from Face Landmarks in Real-Time with TensorFlow.js and Plot.js](https://heartbeat.fritz.ai/constructing-a-3d-face-mesh-from-face-landmarks-in-real-time-with-tensorflow-js-and-plot-js-62b177abcf9f 'still need to read, most importantly want to dig through the repo')

[ar-facedoodle](https://github.com/cyrildiagne/ar-facedoodle "simple and silly but still a good place to start, mostly because it's simple")

[spite/FaceMeshFaceGeometry](https://github.com/spite/FaceMeshFaceGeometry 'uses threeJS instead of WebGL')

[This tutorial walks through how to stream MediaPipe data out over UDP, so any external app and receive and use the data.](https://github.com/madelinegannon/example-mediapipe-udp "Notes on how to connect Google's MediaPipe ML Framework to openFrameworks")

[TensorFlow.js for React Native: Up & Running!](https://tech.courses/tensorflow-js-react-native/ 'Earlier this month, TensorFlow.js for React Native was made generally available following an alpha release phase.')

[TensorFlow.js for React Native is here!](https://blog.tensorflow.org/2020/02/tensorflowjs-for-react-native-is-here.html 'We are pleased to announce that TensorFlow.js for React Native is now available for general use.')

[MediaPipe Facemesh](https://github.com/tensorflow/tfjs-models/tree/master/face-landmarks-detection 'MediaPipe Facemesh (mediapipe-facemesh) is a lightweight package predicting 486 3D facial landmarks to infer the approximate surface geometry of a human face (paper).')

```bash
 npm init -y
 npm i three
 mkdir dist
 mkdir dist/server
 mkdir dist/client
 touch dist/client/index.html
 mkdir src
 mkdir src/client
 touch src/client/client.ts
 touch src/client/tsconfig.json
 mkdir src/server
 touch src/server/server.ts
 touch src/server/tsconfig.json
 touch README.md
 npm i @types/node
 npm i express
 npm i @types/express
 tsc -p ./src/server/
 node ./dist/server/server.js
 touch .gitignore
 git init
 git add README.md
 git commit -m "first commit"
 git branch -M main
 git remote add origin git@github.com:TurtleWolfe/ThreeJsSeanBradley.git
 git push -u origin main
 npm i @types/three
 tsc -p ./src/client/
 node ./dist/server/server.js
 tsc -p ./src/client/
 tsc -p ./src/server/
 node ./dist/server/server.js
 git commit -m "#12 Client Side Dependency Imports"
```

```bash
 1968  git status
 1969  git push
 1970  clear
 1971  git push
 1972  git status
 1973  clear
 1974  exit
 1975  history
 1976  clear
 1977  exit
 1978  tsc -p ./src/client/
 1979  tsc -p ./src/server/
 1980  node ./dist/server/server.js
 1981  git status
 1982  git add .
 1983  git status
 1984  git commit -m "#13 Importing ThreeJS Modules"
 1985  git status
 1986  git push
 1987  git status
 1988  clear
 1989  exit
 1990  cd
 1991  ll
 1992  cd /
 1993  ll
 1994  sudo nano /etc/fstab
 1995  sudo apt update
 1996  apt list --upgradable
 1997  sudo apt upgrade
 1998  sudo reboot
 1999  npm install --save-dev nodemon
 2000  npm install --save-dev concurrently
```
