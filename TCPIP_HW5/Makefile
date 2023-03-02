all:myftpClient.o myftpServer.o myftp.o
	gcc -o myftpClient myftpClient.o myftp.o
	gcc -o myftpServer myftpServer.o myftp.o

myftpServer.o:myftpServer.c
	gcc -c myftpServer.c

myftpClient.o:myftpClient.c
	gcc -c myftpClient.c

myftp.o:myftp.c
	gcc -c myftp.c

clean:
	rm -f *.o myftpServer myftpClient

