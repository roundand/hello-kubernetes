# hello-kubernetes

Use https://hub.docker.com/r/alpine/git/ to clone this repo to environments with Docker but no git, such as http://play-with-k8s.com

docker run -ti --rm -v ${HOME}:/root -v $(pwd):/git alpine/git clone https://github.com/roundand/hello-kubernetes

(Remember to use Ctrl-Ins and Shift-Ins to copy and paste in play-with-k8s)
