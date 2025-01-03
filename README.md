# bitcoin-node
Notes on setting up a full node on Raspberry Pi 5 with stratum server

I have a video that covers the topic on [YouTube](https://www.youtube.com/watch?v=U-jz9LZ7zos).

## Eratum
I forgot to mention in my video and on the PDF file that if you are not just using
TOR, you need to configure your firewall on your router to port forward 8333 to your Pi.
If you don't do that, you won't really have a reachable node.

Another thing to do is check out [bitnodes.io](https://bitnodes.io). You can test
your node's connection with their tool.
