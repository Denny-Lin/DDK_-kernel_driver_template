# DDK_kernel_driver_template
* It is a repository for practicing Linux kernel driver in kernel space.
* I learned linux driver by myself.
* I will record the learning porcesses of drivers in linux kernel moudule here.
* What are the strategies of memory protection in kernal space?
* What is system call?
* user program -> interface / system calls -> inode -> driver
* ...

## Platform
* Linux
<br><br>


## Let's get started
* All the behaviors of read and write should be permitted by kernel which is in the kernel space of ram. <br>

![image](https://user-images.githubusercontent.com/67073582/122648803-5e593380-d15d-11eb-9aaf-fc7de2f3f8cb.png) <br>

![image](https://user-images.githubusercontent.com/67073582/122663434-0a863300-d1cd-11eb-8d8d-4a152fe5ecdb.png) <br>

![image](https://user-images.githubusercontent.com/67073582/122663574-13c3cf80-d1ce-11eb-833e-e793b3e56dbd.png) <br>

![image](https://user-images.githubusercontent.com/67073582/122388792-d0394d80-cfa2-11eb-912a-1f32f38a87c4.png) <br>

![image](https://user-images.githubusercontent.com/67073582/122389029-1393bc00-cfa3-11eb-90b1-da17e137e61f.png) <br>

* So what we should do is ...
* To know the interface and what function pointer we can use.
* Yes, we need to know some structures, cuz it is not like the 8051, we just use our private struct or even just array.
* Linux have lots of specific given structs, the data will be sent to other machines following the given structs via wires in phiscial layer. 
* ...
<br><br>

## References
* https://www.youtube.com/watch?v=R5qSTZA0PuY
* https://www.youtube.com/watch?v=oX9ZwMQL2f4
* https://docs.huihoo.com/doxygen/linux/kernel/3.7/structfile__operations.html
* http://0975128810.blogspot.com/2016/01/raspberry-usb-driver.html
* https://www.ibm.com/docs/en/linux-on-systems?topic=hdaa-names-nodes-numbers
* https://www.programmersought.com/article/46983724452/
<br><br>
