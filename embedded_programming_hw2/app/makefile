CC = arm-none-linux-gnueabi-gcc
CFLAGS = -static -W -Wall
TARGET = app
CFILE = dev_app.c

app :
	$(CC) $(CFLAGS) -o $(TARGET) $(CFILE) 

clean:
	sudo rm -rf $(OBJS) $(TARGET)