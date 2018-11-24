# Lesson 3

## Build
`docker build -t lesson3:latest .`

## Start the contatiner
`docker run --rm -it lesson3:latest`

## To run the test case
Open the Kitematic Alpha to access another terminal on same contatiner. Click on exec button to launch the terminal.
Type `python endpoint_test.py` to run the test cases