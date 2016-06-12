# jirafeau
 Jirafeau is a web site permitting to upload a file in a simple way and give an unique link to it.

# docker-compose
```
jirafeau:
   image: evanhoucke/jirafeau
   volumes:
     - /upload/directory:/data
   ports:
     - 80:80
   restart: always
```
