[Docker Basics]()  
1. [intro video]()
2. [Link to guide from the same guy in the video](https://blog.docker.com/2016/03/containers-are-not-vms/)
3. https://blog.docker.com/2016/04/containers-and-vms-together/
4. https://blog.docker.com/2016/03/containers-are-not-vms/
5. [Container vs VM]()
6. [Container vs Process](https://sites.google.com/site/mytechnicalcollection/cloud-computing/docker/container-vs-process)
7. https://stackoverflow.com/questions/31237663/os-containers-isolation-vs-process-isolation
8. https://medium.freecodecamp.org/a-beginner-friendly-introduction-to-containers-vms-and-docker-79a9e3e119b
9. https://medium.com/@jessgreb01/digging-into-docker-layers-c22f948ed612
10. https://www.networkcomputing.com/storage/docker-containers-what-makes-them-so-portable/1465322250
11. [Docker Install for windows 10 Home](https://docs.docker.com/toolbox/overview/)
12. https://docs.microsoft.com/en-us/virtualization/windowscontainers/about/
13. uses of Docker:
  In the same way you can write code, push it up to version control like git and have another person a world away pull down your that code on their computer and have it be exactly the same. Docker allows you build an environment/infrastructure push up an image of it to a docker repository and have someone, a world away, pull down your docker image, and have it run exactly the same way it ran on your computer.
  The reason this is possible is because of the concept of containers. You can put say mysql in one container, apache in another, and php in yet another one all wrapped up in a host container running a variation of linux you like. Have the php container pull in php code from a git repository, and set it up so that docker spins up a working environment with your app once you run the command to initialize everything.

This way instead of having a designer go through technical setup instructions they might not understand just to help you “skin” your app, you just have them download docker, pull down your docker image and issue a simple command to spin it up and they can immediately start interacting with it at say http://localhost:8080/ … just like that.  

Another thing to think about is that because of this, you can run the same container/environment in production as you do on your local environment so that there is little to no difference in the two, which makes it easier to reproduce and fix production bugs, for example.  
20. https://www.quora.com/Why-is-Docker-useful  
21. https://www.level-up.one/docker-tutorial-containers-vms/  
23. https://www.google.com/imgres?imgurl=https://www.ccnahub.com/wp-content/uploads/2016/05/hypervisor.jpg&imgrefurl=https://www.ccnahub.com/linux/type-1-vs-2-hypervisor-virtualization-platform/&h=269&w=602&tbnid=URzolKEQs6CqOM:&q=type+1+and+type+2+hypervisors&tbnh=94&tbnw=211&usg=AFrqEzc-iqwofiR1L-5pdlG7dlYhMCtVAA&vet=1&docid=x4ypIldp61zTmM&sa=X&ved=2ahUKEwjf-6SAhNTcAhXBp1kKHYM4BFkQ9QEwAHoECAkQBg  
24. https://medium.com/@paccattam/drooling-over-docker-2-understanding-union-file-systems-2e9bf204177c  
25. https://washraf.gitbooks.io/the-docker-ecosystem/content/Chapter%201/Section%203/union_file_system.html  
26. https://stackoverflow.com/questions/32775594/why-does-docker-need-a-union-file-system
27. https://www.level-up.one/docker-kubernetes-best-architecture/
28. https://stackify.com/kubernetes-docker-deployments/  
29. https://deis.com/blog/2016/docker-storage-introduction/
