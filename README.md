# nfs-client-provisioner1
Guidde: https://www.debontonline.com/2020/11/kubernetes-part-11-how-to-configure.html

Install:
	kubectl create namespace nfs-client-provisioner 

	kubectl apply -f nfs-client-provisioner/class.yaml

	kubectl apply -f nfs-client-provisioner/rbac.yaml

	kubectl apply -f nfs-client-provisioner/deployment.yaml


Test:

deploy test in test_nfs Folder.
