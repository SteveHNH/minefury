# Running a Minecraft Server

Minecraft is a clusterF of random pieces of software.

- Bedrock
- Java Edition
- Forge
- Windows Edition
- Switch Edition

I ain't got time to learn about each one so we're gonna focus on the Java edition.

To run the Java edition, you're going to need Java. Depending on the VERSION of Minecrap
you want to run, you might need a specific VERSION of Java. Keep that in mind because
Minecraft sucks.

## Java Version Notice

Unless you are going to be downloading a version of Minecraft older than 1.16, you
should be good using Java 17.

[Download it Here](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)

Download the SE version that matches your system. Probably Windows x64 Installer.

If you're running linux, then grab the appropriate Linux edition.

If for some reason you wind up at a login prompt for oracle and they want you to sign up
for an account, use [mailinator.com](https://mailinator.com/) to make a fake one. Give Oracle
the middle finger on the way out the door.

## Install Java

Now that you downloaded Java, go to your download directory for your browser and run
the installer. Just accept the defaults except for any that want to install extra stupid stuff.

## Get Minecraft Server

Head to [The Minecraft Website](https://www.minecraft.net/en-us/download/server) to get the
latest server version. If you want something older for mods, keep scrolling.

## Setting up the server

Here's where things get stupid. You now have a Minecraft Server `.jar` file.

DO NOT attempt to run it where it lies. Bad move.

1. Create a directory somewhere else. For the love of God, just make a new directory. Something like
`C:\Users\YourName\Documents\MinecraftServer-{Version}`. It's a good idea to append the version to the
directory, because you're going to end up with more than one at some point.
2. Move the `.jar` file to the directory you just created.
3. Open a command prompt. `Win + R`, type `cmd`, and press enter.
4. Type `cd {Directory}` and press enter.
5. Type `java -Xmx1024M -Xms1024M -jar {JarFile}` and press enter. The `-Xmx` and `-Xms` are
setting your memory minimum and maximum. Java is a deadly memory eating hydra, so set this to something
reasonable. If you have a chonky machine, then set the max to something a bit higher. I use `1024` and `4096` respecively.
6. Minecraft is going to start up. If Windows yells about network permission, just say YES. If a remote machine in your house wants to connect, you're going to kick yourself in the nuts (providing you have them) if you say NO. Windows Firewall is a big ball of hot garbage.
7. Minecraft started but it's totally going to error out yelling about eulas. In the directory where you put `server.jar` a bunch of crap just got created. Open `eula.txt` and change the first line to `eula=true`. Who gives a crap what you're agreeing to? Nobody.
8. Run the same command again. Bob's your uncle.

## Old Minecraft Servers

You'll never find these on minecraft.net. They want to bury this crap in the deepest part
of the earth, but I can guarantee that some random thing your kid saw on YouTube is going to require an older stupid version.

Take this url: https://www.minecraft.net/en-us/article/minecraft-java-edition-1-16-1

Replace that junk at the end with whatever version you need. Ex: 1-16-2 = 1.16.2

## Notes

You have a running Minecraft server on your machine now. There's a bunch of stuff you can do but it's out of scope for this guide. I'm not going to tell you how to do it... yet

Keep in mind that other players must also be running Java Edition. I have no idea what to tell you if someone wants to connect a switch or a windows version to it. Minecraft is stupid. It's like a bag full of half-forgotten software that nobody bothered to try to make work together.


