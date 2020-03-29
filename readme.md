Start docker compose: docker-compose up

Download file: https://drive.google.com/file/d/1k5kVifFST7tqv40K5Dac6J__rVESZDHM

Move to scripts folder and extract file

Connect docker mongo: docker exec -it <CONTAINER ID OF MONGO IMAGE> bash

Import file: ./scripts/mongoseed.sh

Mongodb manager:http://localhost:8081/

10 query: query.txt
Connect to docker mongo:
then go inside mongo cli:

- mongo -u root -p root
- use woption

then try 10 query in txt

Investigate the balance between the consistency and availability in your NoSQL system
Read file: consistency_and_avaiablility.txt

Investigate the indexing techniques available in your NoSQL system.
Read file: indexing.txt
