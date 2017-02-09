# install node.js

open https://nodejs.org/en/download/

![node_download](https://raw.githubusercontent.com/ouiyeah/node_js/master/img/node_download.png "node_download")

uncompress node package and export environments at the end of '.bashrc' (for linux)

>$ sudo mv [node_dir] /usr/lib/node

>$ vi ~/.bashrc

    export NODE_HOME=/usr/lib/node
    export NODE_PATH=${NODE_HOME}/lib/node_modules
    export PATH=${NODE_HOME}/bin:$PATH

#install node_modules

>$ npm install -g rosnodejs ws express log4js grunt mysql crypto body-parser sequelize pdfkit
