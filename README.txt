gcc filecalls.c queuecalls.c gradingServerQ.c -o server -pthread
gcc filecalls.c submitQ.c -o client
./server <portNo>
./client <serverIP> <portNo> <new or status> <filename or reqID>
