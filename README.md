# Everything you need for your db2 exam, dockerized

To start, run:

```bash
clone 
https://github.com/lucafabbian/database2-exam-docker.git
cd database2-exam-docker

# start everything
docker compose up
```

Then, open the following urls:
- **GraphDB:** <http://localhost:7211>
- **Protegé:** <http://localhost:9080/vnc.html?resize=scale&autoconnect=true>
- **Neo4j:** <http://localhost:7475>, type `:server connect` and set the following credentials:
  - url: `neo4j://localhost:7688`
  - user: `neo4j`
  - password: `s3cr3t`



And that's all!