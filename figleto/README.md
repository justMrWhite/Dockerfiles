# About this thing

If you got here, you sure know what it is.\
Figlet outputs your text in a cool way.\
See for yourself:

## How do I get the image?
Well, I did not push it to DockerHub, so you can always get if from here and build it like this:

```docker
docker image build -t figleto .
```
## Okay, how can I run the container?
Easy breezy.

```docker
docker container run figleto figlet hello
```
## Is that it?
Yes, that's it. \
As you can can see, this image is not a bid deal, just for the pleasure and simplicity of playing with containers (just to make sure everything works, but you can always use the hello-world image.)