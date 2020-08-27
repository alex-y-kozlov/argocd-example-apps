.PHONY: delete deploy kustomize

apply:
	kubectl apply -f keel.out.yaml
kustomize: kustomization.yaml
	kustomize build > /k/keel.out.yaml
#delete:
#	kubectl delete -f drone.out.yaml
