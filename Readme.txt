Course link:
=============
https://app.pluralsight.com/library/courses/kubernetes-developers-core-concepts/table-of-contents

How to run dashboard:
======================
Kubernetes login:
------------------
Manual
https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/
kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.7.0/aio/deploy/recommended.yaml
kubectl proxy

Dashboard
http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/#/login

Create user
https://github.com/kubernetes/dashboard/blob/master/docs/user/access-control/creating-sample-user.md

How to create user
https://upcloud.com/resources/tutorials/deploy-kubernetes-dashboard


Create user token:
kubectl -n kubernetes-dashboard create token admin-user