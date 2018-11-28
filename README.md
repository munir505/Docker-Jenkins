# Docker-Jenkins
Run 
docker build -t jenkins . && ./docker-run
To build and deploy using jenkins

#### Use this to get vertification code
```bash
gcloud auth login
```
#### This creates the clusters
```bash
gcloud container clusters create <name> --zone <zone>
```
#### Deploys App from docker hub image using yaml file
```bash
kubectl create -f <file_name.yaml>
```
#### Use this to get vertification code
```bash
kubectl get pods|services|deployment
```
