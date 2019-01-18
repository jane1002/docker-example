#section 2, lecture 14
1. docker run busybox ls works, but docker run hello-world doesn't
   A: Image [FS snapshot, startup command]. for hello-world image file snapshot, the only thing inside it is echo out or kind of printout sth. while for busybox,
    the FS contains that ls command.

#section 2 docker commands
1. docker ps(show running containers): docker run busybox ping google.com, then run docker ps.
2. docker ps --all (show all containers)
3. docker start + id: will restart the exited docker image again.
4. docker system prune: remove all containers, clean the cache
5. docker logs + id': not restart, just log the msg.
6. docker create busybox echo hi there: get the container ID
7. stop/kill containers: docker stop/kill + id
8. docker run redis.
9. docker exec -it + id + command(redis-cli)
10. docker exec -it 0927bf42cdad sh : sh call a command processor.
11. docker run -it busybox sh

#section 3 