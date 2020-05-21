A sample integration of create-eract-app and express+mongo

The following variables are needed by the /dist/.env file in order to test the integration:

PORT=3001
MONGO_DB_URL=
MONGO_DB_NAME=
MONGO_USER_NAME=
MONGO_USER_PASS=
MONGO_CONNECTION_STRING=mongodb+srv://${MONGO_USER_NAME}:${MONGO_USER_PASS}@${MONGO_DB_URL}/${MONGO_DB_NAME}?retryWrites=true&w=majority

