fwm:fwm_menu.o fwm_func.o 
	gcc -o fwm fwm_menu.o fwm_func.o


fwm_menu.o:fwm_menu.c fwm_header.h
	gcc -c fwm_menu.c


fwm_func.o:fwm_func.c fwm_header.h
	gcc -c fwm_func.c


clean:
	rm *.o
