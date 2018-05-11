

add parameter to apiserver
--runtime-config=autoscaling/v2alpha1=true  

create secret
kubectl create  secret generic  cm-adapter-serving-certs --from-file=serving.crt=apiserver.crt --from-file=serving.key=apiserver.key -n custom-metrics
 
