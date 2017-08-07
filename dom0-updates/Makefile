CFLAGS+=-g -I. -Wall -Wextra -Werror -fPIC
qfile-dom0-unpacker: qfile-dom0-unpacker.o
	$(CC) -pie -g -o $@ $^ -lqubes-rpc-filecopy
