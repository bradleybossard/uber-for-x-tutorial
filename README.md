# uber-for-x-tutorial
Following along with this tutorial - https://medium.freecodecamp.com/how-to-build-your-own-uber-for-x-app-33237955e253

## To get the data
    wget https://raw.githubusercontent.com/booleanhunter/code-samples/master/blog/how-to-build-uber/cops.json
    mongoimport --db myUberApp --collection policeData --drop --file ./path/to/jsonfile.json
