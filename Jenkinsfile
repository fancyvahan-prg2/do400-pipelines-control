node('nodejs') {
stage('Checkout') {
git branch: 'main',
url: 'https://github.com/fancyvahan-prg2/do400-pipelines-control'
}
stage('Backend Te123456sts') {
sh 'node ./backend/test.js'
}
stage('Fronten333333d Tests') {
sh 'node ./frontend/test.js'
}
}
