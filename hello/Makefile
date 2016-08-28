obj-m := hello.o  
KERNELDR := /usr/src/linux-headers-4.2.0-36-generic/  
PWD := $(shell pwd)  
modules:  
	$(MAKE) -C $(KERNELDR) M=$(PWD) modules  
moduels_install:  
	$(MAKE) -C $(KERNELDR) M=$(PWD) modules_install  
clean:  
	rm -rf *.o *~ core .depend .*.cmd *.ko *.mod.c .tmp_versions  

