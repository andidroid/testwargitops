# testwargitops

kubectl kustomize testwar/base/ > out.yaml

datree test out.yaml
kubectl apply -f out.yaml 

kubectl kustomize testwar/secrets/ > out.yaml

kubectl kustomize testwar/overlays/test > out.yaml