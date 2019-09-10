# Standard Operating Procedures

### Service Name
Sample Service

### Procedure Name
Start Service

### Time to execute
1 minute

### Description
Start a service already installed on this host

### Pre-execution


### Execution 
``` bash
start_service.sh
```

### Validation
the log is in /var/log/sampleservice

### Rollback
``` bash
stop_service.sh
```

### Notes
