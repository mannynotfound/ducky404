# ducky404

Random Payload scripts for the [USB Rubber Ducky](http://usbrubberducky.com). 

## Usage

inject.bin will always be the first thing executed on USB load, to compile a .txt ducky script into inject.bin run the following:

(Assuming your drive is called Untitled and you're on mac, otherwise replace with your sd card mount point)

```bash
java -jar duckencoder.jar -i execute.txt -o /Volumes/Untitled/inject.bin
```

## Thoughts

While Rubber Ducky is a very good prank/hacking tool, I am interested in use of the Ducky for an almost performative art purpose. The fact
that you can see the computer run the actions is pretty powerful, and there could be some very interesting use of delaying/typing/launching to create
a both useful and cinematic experience.
