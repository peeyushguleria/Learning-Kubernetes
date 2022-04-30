<h1>Containers and Virtual Machines.</h1>
<img src="https://www.docker.com/wp-content/uploads/Blog.-Are-containers-..VM-Image-1.png">

### Introduction
We are going to compare Containers and Virtual Machines. First, you can see a little diagram regarding the infrastructure on the screen, like the architect of these two things. Then, we'll go into the details and what all these things represent, and how they compare with each other? So Containers and Virtual Machines have similar resource isolation, unlike the allocation benefits that they provide. But the functioning part is a bit different because, in Containers, they virtualize the operating system instead of the hardware, and Containers are much more portable and efficient as we looked into the previous video.
So on this screen, you can see on the left-hand side the containerized applications, App A, App B, App C, App D, and there's something called Docker, the host operating system, and then the infrastructure on your hardware. So Containers, in simple terms, are abstracting at the App layer. So basically, the package, the code, and the dependencies together, multiple Containers can, you know, run on the same machine. The critical part over here we mentioned in the previous video is sharing the host operating system.
<hr>

### What is an OS kernel?
The OS Kernel is, you know, being shared by all the above Containers. So it's not like installing a new operating system on its own. No, it's using the host operating system, and each particular app that you see on the screen App A, App B, App C, App D it's running in an isolated environment. So these are like isolated processes. Also, you can communicate with each other, but it does not have much information about what is going on, let's say, in the host operating system outside it.

So this is great because you're not installing, let's say, the entire operating system. For example, containers are taking less space than a virtual machine, which we'll talk more about later. And it's basically like images which we'll also look into later. They take like a few megabytes of size. They can handle, you know, more applications and require fewer VMs, unlike operating systems.

On the other hand, you can see Virtual Machine on the right-hand side. This is because the virtual Machine provides an abstraction of the physical hardware. It will turn one particular server into multiple servers.

So literally divide the hard disk space and install separate operating systems on that. You might have done dual booting on stuff. With that, you can install Windows on one part of the hard disk, with Linux or some other operating system on another part. So that is on the hardware level that is happening.
<hr>

### What is a hypervisor?
A hypervisor is a virtual machine monitor and software that allows you to create and run Virtual Machines. And the role is that basically, it will enable the host computer, unlike the primary server, to support multiple guest Virtual Machines by sharing its resources.

For example, if you want to share the memory, the space, and the processing power, all these things can be shared with different operating systems. So each Virtual Machine is a full copy of an entire operating system, the application, all the necessary binaries, and all the libraries and stuff. This takes up to like tens of GBS and, you know, all these things. And also, to boot this up, it can be a little slow.
<hr>

### Conclusion
But that is like the main difference between a Container and a Virtual Machine. So it's not a "this or that" question. People often ask, "Should I use Containers or Virtual Machines?" Because it's like Containers and Virtual Machines are used together, they provide great flexibility in terms of deploying and managing. So, in short, you can say that Containers run on top of Virtual Machines, which is fine. As I previously said, it's not a "this or that" question because both of these things get used. 
<hr>
