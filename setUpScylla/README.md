#Setup 

kubectl create namespace <scy> 

kubectl -n scy create -f svc.yaml

kubectl -n scy create -f configMap.yaml

kubectl -n scy create -f pv.yaml

kubectl -n scy create -f sfs.yaml

kubectl -n scy exec -it scylla --/bin/bash



