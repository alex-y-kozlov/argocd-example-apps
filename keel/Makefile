.PHONY: delete deploy kustomize

apply:
	kubectl apply -f ./k/keel.cicd-01-traefik.yaml
kustomize: kustomization.yaml
	kustomize build > ./k/keel.cicd-01-traefik.yaml
#delete:
#	kubectl delete -f drone.out.yaml
