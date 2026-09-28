# Nombre del programa final
PROGRAMA := programa

CC := gcc
CFLAGS := -Wall

# TODO 1
SRCS := main.c operaciones.c

# TODO 2
OBJS := $(SRCS:.c=.o)

all: $(PROGRAMA)

# TODO 3
$(PROGRAMA): $(OBJS)
	$(CC) $^ -o $(PROGRAMA)

# TODO 4
%.o : %.c
	$(CC) $(CFLAGS) -c $< -o $@

clean:
	rm -f $(PROGRAMA) $(OBJS)

# TODO 5
.PHONY: all clean
