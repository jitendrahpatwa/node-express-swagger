#swag 

### npm install --save swagger-ui-express

### swagger link follewd by http://localhost:3000/api-docs/
### api is found by http://localhost:3000/

### use swagger.json to design the swagger apis ui

### in index.js specifies the code 
>var swaggerUi = require('swagger-ui-express');
##
>var swaggerDocument = require('./swagger.json');
***
&
before using listen function use code
***
>app.use('/api-docs', swaggerUi.serve, swaggerUi.setup(swaggerDocument));
