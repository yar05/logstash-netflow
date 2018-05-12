# logstash-netflow
Logstash netflow filter extracted from logstash netflow module.
Remove 03-dns-filter.conf is you don't need DNS reverse lookups, might be heavy on queries. 
80-netflow-output.conf will install original ES template. 

- Requires $LOGSTASH_HOME 
- Tested against logstash 6.2


