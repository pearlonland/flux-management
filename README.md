
`flux bootstrap github
 --owner=pearlonland
 --repository=flux-management
 --path=flux-cluster/minikube
 --personal=true
 --private=false` \
 
 Please enter your GitHub personal access token (PAT): \
► connecting to github.com \
✔ repository "https://github.com/pearlonland/flux-management" created \
► cloning branch "main" from Git repository "https://github.com/pearlonland/flux-management.git" \
✔ cloned repository \
► generating component manifests \
✔ generated component manifests \
✔ committed component manifests to "main" ("2928af49888cfa505543f1a65c33d024c8d9abb5") \
► pushing component manifests to "https://github.com/pearlonland/flux-management.git" \
► installing components in "flux-system" namespace \
✔ installed components \
✔ reconciled components \
► determining if source secret "flux-system/flux-system" exists \
► generating source secret \
✔ public key: xxxx \
✔ configured deploy key "flux-system-main-flux-system-./flux-cluster/minikube" for "https://github.com/pearlonland/flux-management" \
► applying source secret "flux-system/flux-system" \
✔ reconciled source secret \
► generating sync manifests \
✔ generated sync manifests \
✔ committed sync manifests to "main" ("xxx") \
► pushing sync manifests to "https://github.com/pearlonland/flux-management.git" \
► applying sync manifests \
✔ reconciled sync configuration \
◎ waiting for GitRepository "flux-system/flux-system" to be reconciled \
✔ GitRepository reconciled successfully \
◎ waiting for Kustomization "flux-system/flux-system" to be reconciled \
✔ Kustomization reconciled successfully \
► confirming components are healthy 
✔ helm-controller: deployment ready \
✔ kustomize-controller: deployment ready \
✔ notification-controller: deployment ready \
✔ source-controller: deployment ready \
✔ all components are healthy \
