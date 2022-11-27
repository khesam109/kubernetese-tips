## 1. Get bash from nginx container:

 ```
 kubectl exec -it sidecar-scenario-7966864d58-rsfm8 -c nginx -- bash
 ```
 
## 2. Check if ```/nginx``` exist

## 3. Add a file in aforementioned directory 

## 4. Get bash from busybox container:
 ```kubectl exec -it sidecar-scenario-7966864d58-rsfm8 -c busybox -- sh```
 
## 5. Check if ```/busybox``` exist

## 6. Check if added file which is added to the first container is here too
