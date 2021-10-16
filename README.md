# testwargitops

kubectl kustomize testwar/base/ > out.yaml

datree test out.yaml
kubectl apply -f out.yaml 

kubectl kustomize testwar/secrets/ > out.yaml

kubectl kustomize testwar/overlays/test > out.yaml



# Doku Links, Blog Posts
https://docs.wildfly.org/bootablejar/
https://www.eclipse.org/jkube/docs/kubernetes-maven-plugin
https://github.com/GoogleContainerTools/jib/tree/master/jib-maven-plugin

https://www.wildfly.org/news/2021/02/01/Bootable-jar-jkube-clustering-openshift/
https://www.ellin.com/2021/03/11/highly-available-wildfly-applications-on-kubernetes/