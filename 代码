obj-m := os_attack.o



KDIR := /lib/modules/$(uname -r)/build/

PWD := $(shell pwd)



all:module



module:

$(MAKE) -C $(KDIR) M=$(PWD) modules





clean:

rm -rf *.ko *.mod.c *.o Module.* modules.* .*.cmd .tmp_versions
