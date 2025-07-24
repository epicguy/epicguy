## Hello! This is James.
I get excited doing software architecture, design and implementation. My focus in recent years as been using Node.js on AWS.
Having worked on many greenfield projects, I have also honed my skills and built starter-packs for automating all the things.
This includes focus on DX, use of GitOps, maximum use of Terraform for all things infrastructure, Database-schema-as-code (Liquibase / Flyway)
and a good amount of security concerns (OWASP, VPN + bastion, sealed secrets) as well as exceptional observability and debugging-in-production.
#### Currenlty working on:
  - [InfluenceBoard.com](https://app.influenceboard.com) built on VanillaJS and NodeJS (AWS, MySQL, Fargate)
  - [Paisley](https://app.paisley.io) a crypto-curency wallet and back-end support for purchasing CVM on the new Convex blockchain.
#### Ideal tech stack:
- React + Typescript
- Fastify
- PostgreSQL
- Docker + Fargate
- AWS + Terraform
  
### Diversion and side hobbies:
#### Sudoku
Took a little while, but I have successfully createad all 5B unique grids, using pure Javascript in 8 hours on a 64 core AWS EC2 instance.
I'll next look at a Javascript algorithim to create puzzles for each grid solution, with the minimun number of clues.
This involves the challenge of "covering" all the "unavoidable sets" for a given grid, in a minimum way.
Should be fun.
#### Back-end framework for start-ups
Attempting to create a framework that is quick to build freatures, while being dirt cheap to run ($10/mo on AWS would be awesome, eh?)
The "trick" is to eliminate the traditional database layer, using an interesting feature of Kafka called indexed-topics,
allowing me to keep the DDD Entities in memory while also having a fast-write to a persisted back-up on disk.
Additionally, by creating "deltas" as a first concern for updating read-models, we can stream these same updates to clients
for an "always updated" end-user experience, without the overhead of developer implementation and complexity.
