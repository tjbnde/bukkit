Start with:

docker run -t -i -p 25565:25565 -v /root/mount/bukkit:/root --name bukkit tjbn/bukkit

Make sure to copy the following files to the directory you use for mount:
- start.sh (Example Content: java -Xms512M -Xmx1024M -jar /root/craftbukkit.jar)
- craftbukkit.jar
