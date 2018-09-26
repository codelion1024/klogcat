# klogcat
a native layer log utility, which can record kernel log continuously.

#### required configuration  
* selinux config: allow logd kmsg_device:chr_file { read };
* build system intergration: PRODUCT_PACKAGES += klogcat
