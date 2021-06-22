fisrt step here was to run a test on my code to se if it passes all the test. To show that code is working as expected
Then I built a docker image which holds my artifact meaning my docker fime with the base image python 3.9, the install the dependencies of Parlai andalso install the parlai itself
and setting parlai as the entry point( way of pre-defining a command) 
Then I pushed the Docker image to the registry, while taging the docker image with a commit shavalue( this make every time I make a commit a new shavale will be assigned for reference)
Challenges: I needed to setup a bitbucket account first which i was not using before