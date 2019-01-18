#section 2, lecture 14
1. docker run busybox ls works, but docker run hello-world doesn't
   A: Image [FS snapshot, startup command]. for hello-world image file snapshot, the only thing inside it is echo out or kind of printout sth. while for busybox,
    the FS contains that ls command.

#section 2, lecture 15
1. docker ps(show running containers): docker run busybox ping google.com, then run docker ps.
2. docker ps --all (show all containers)
3. docker start + id: will restart the exited docker image again.
4. docker system prune: remove all containers, clean the cache
5. docker logs + id'
