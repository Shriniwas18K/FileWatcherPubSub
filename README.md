# FileWatcherPubSub
This mini-project is command-line tool.
- Compile the program using any C compiler. example : gcc

  	gcc rolexhound.c -o rolexhound

- It's executable takes arguement as path to file. We may provide absolute or relative path of file		

  	rolexhound <pathtofile>

![image](https://github.com/Shriniwas18K/FileWatcherPubSub/assets/153389794/704c9ee7-981c-4720-8c86-15fb4a8ff25f)
- It logs output when file is accessed or written in every 10s
## Learnings 
- using signal.h to handle keyboard interrupts and prevent executable from accidental termination , i.e. termination of the executable occurs only by CTRL+C
- using windows.h apis to get access to internal file details like LastAccessTime
- handling command-line arguements and proper documentation with comments
