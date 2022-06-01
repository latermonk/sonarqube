# sonarqube



https://docs.sonarqube.org/latest/setup/install-server/



https://github.com/SonarSource/docker-sonarqube/blob/master/example-compose-files/sq-with-postgres/docker-compose.yml    





## Docker-compose




https://hub.docker.com/_/sonarqube     

```

sysctl -w vm.max_map_count=524288
sysctl -w fs.file-max=131072
ulimit -n 131072
ulimit -u 8192

```




---


```


ulimit -n 65536 
sysctl -w vm.max_map_count=262144



```


