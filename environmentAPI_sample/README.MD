1. Create CRD
kubectl apply -f https://raw.githubusercontent.com/redhat-appstudio/managed-gitops/main/appstudio-shared/manifests/appstudio-shared-customresourcedefinitions.yaml

2. Create CR
oc apply -f environmentAPI_sample/stage-environment.yaml

3. Check created CR
oc get environment -o yaml