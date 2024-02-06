# udacity-devops-engineer-project-2-IAC
Udacity Cloud DevOps Engineer - Deploy a high availability web app using CloudFormation

## Constructing Infra Steps
1. Create Networks
```
./create.sh udagram-network network.yml network-parameters.json
```

2. Update Networks
```
./update.sh udagram-network network.yml network-parameters.json 
```

3. Create Servers
```
./create.sh udagram-server udagram.yml udagram-parameters.json 
```

4. Update Servers
```
./update.sh udagram-server udagram.yml udagram-parameters.json
```

5. Delete Networks
```
./delete.sh udagram-network
```

6. Delete Servers
```
./delete.sh udagram-server  
```

---
## Output
Web server: 	http://udagra-WebSe-XKfwYf6dDeFa-1212895345.us-east-1.elb.amazonaws.com
