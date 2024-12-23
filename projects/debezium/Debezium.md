This is to learn and understand things about debezium.

Basic setup done. Now few things are in my mind ? 

bucketing them to two segments : 

###### TODO 
- [ ] Setup Testing environment for debezium
	- [ ] Particular to Postgres
- [ ] Tool to consume replication slot directly


##### Open Questions 
- implementation of queue
- monitoring ? 


Basic Architecture : 



Documents : 
- https://debezium.io/documentation/reference/stable/architecture.html
- https://www.youtube.com/watch?v=DWidkj_cy7U (how to create a custom kafka connector)
	- https://github.com/dalelane/kafka-connect-developers-intro-tutorial (code)
- https://www.youtube.com/watch?v=0cZ4elFNAQQ
- usage <pg_recvlogical> https://chatgpt.com/c/676999a5-ba60-8001-91c7-45268b984b01 -> More details 
- https://is.muni.cz/th/itqvy/Performance_testing_of_debezium_Send_Version__8_.pdf?lang=en -> Load testing of debezium (35k/sec)
- https://debezium.zulipchat.com/#narrow/channel/348249-community-postgresql/topic/Debezium.20performance.3A.20.20Millsec.20behind.20source.20is.20ramping.20up/near/433313926 -> This guy is also facing similar issue
- https://www.postgresql.org/docs/current/logicaldecoding.html 