# LAN-Search

Lan Search is a tool designed for the purpose of searching for files and folders which are shared over a Local Area Network. It is particularly useful in organizations where a lot of folders are shared on individual systems.

## How it works?

Here's how the application works. You specify an IP range. The tool searches for live hosts. It then determines the list of folders shared by each system and looks for files (according to a keyword that you specify).

The first point of interest would be - how to determine whether a system with a particular IP address is active. This can be achieved using the Ping class defined in the namespace System.Net.NetworkingInformation. The Ping class offers both synchronous and asynchronous methods to detect whether a remote host is reachable.

## Output Images

Search Results
:------------------:|
![Search Result](Screenshots/pic3.png)  

UI
:------------------:|
![UI](Screenshots/pic2.png)

Search Configurations
:------------------:|
![Search Configurations](Screenshots/pic1.png)

## Project Demo ppt and LaTex Document is provided along with this Project 

See our Project Presentation @ [Project PPT](/LAN_Search.pptx) <br>
See our LaTex Document in IEEE Conference Format @ [Project Document](/TRIE_FILE_SEARCH_ENGINE.pdf)

## For Project Demo, Check @

[LAN Search Demo](https://youtu.be/jsArVg6YyUE)
