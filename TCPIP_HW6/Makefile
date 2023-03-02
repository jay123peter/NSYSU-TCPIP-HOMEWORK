all :main.o pcap.o fill_packet.o
	gcc -o myping main.o pcap.o fill_packet.o -lpcap

main.o:main.c
	gcc -c main.c

pcap.o:pcap.c
	gcc -c pcap.c

fill_packet.o:fill_packet.c
	gcc -c fill_packet.c

clean :
	rm -rf *~ *.o myping


