to validate the openapi spec 

> npm install -g swagger-cli
> swagger-cli.cmd validate .\skypath.yml

to create a single openapi yml file use speccy

> npm install -g speccy@0.8.7
> speccy resolve skypath.yml -o spec-output.yaml

then you can import it to Postman collection via postman import button