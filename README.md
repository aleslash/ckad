# ckad

https://github.com/dgkanatsios/CKAD-exercises

https://github.com/ibrahimatay/CKAD-Exercises


## Recursos

During the exam, candidates may:

- review the Exam content instructions that are presented in the command line terminal.
- review Documents installed by the distribution (i.e. /usr/share and its subdirectories)
- use Packages that are part of the distribution (may also be installed by Candidate if not available by default)
- use the browser within the VM to access the following documentation: https://kubernetes.io/docs/, https://kubernetes.io/blog/ and their subdomains. This includes all available language translations of these pages
- CKAD ONLY: candidates can use the browser within the VM to access https://helm.sh/docs
- use the search function provided on https://kubernetes.io/docs/ however, they may only open search results that have a domain matching the sites listed above

## Links diretos para usar durante a prova

- https://kubernetes.io/docs/reference/
- https://kubernetes.io/docs/reference/kubectl/cheatsheet/

## Pontos de atencao

- troca de contexto
- salvar arquivos
- para jobs: -- sh -c "sleep x && echo done"
- helm: delete release, upgrade release, install,
- service account e secret
- deployment, history e rollback, rollout restart
- delete pod --force --grace-period=0
- service, comando get ep e comando expose
- pv e pvc
- storage class e pvc
- secret, secret volume e secret env
- configMap e configMap volume
- sidecar vs initContainer
- network policy

## Comandos uteis
```
alias k=kubectl                         # will already be pre-configured

export do="--dry-run=client -o yaml"    # k create deploy nginx --image=nginx $do

export now="--force --grace-period 0"   # k delete pod x $now
```
