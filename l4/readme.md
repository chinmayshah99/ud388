# Lesson 3
In Windows

## Using Kitematic Alpha
### Build
`docker build -t lesson4:latest .`

### Start the contatiner
`docker run --rm -it lesson4:latest`

## To run the test case
Open the Kitematic Alpha to access another terminal on same contatiner. Click on exec button to launch the terminal.
Type `python endpoint_test.py` to run the test cases


### Without using Kitematic Alpha
### Build
`docker build -t lesson4:latest .`

### Start the contatiner
`docker run --rm -it --name alpha lesson4:latest`

## To run the test case
In docker type terminal: `docker exec -it alpha sh`
Type `python endpoint_test.py` to run the test cases
