## Installation process

### Master node (CP)

1. Przygotowanie node'a pod deployment K8s (kernel, moduły, swap).
2. Dodanie repo K8s i instalacja pakietów.
3. Inicjalizacja klastra.
4. Instalacja pluginu sieiowego.

### Worker node
1. Przygotowanie node'a pod deployment K8s (kernel, moduły, swap).
2. Dodanie repo K8s i instalacja pakietów.
3. Join worker node'a do master node'a (do klastra).

Punkty 1. oraz 2. pokryte są poprzez skrypt [deploy-k8s-ubuntu.sh](/deploy-k8s-ubuntu.sh)
