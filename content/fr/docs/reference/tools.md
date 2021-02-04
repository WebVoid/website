---
title: Outils
weight: 80
---

## Kubectl

[`kubectl`](/fr/docs/tasks/tools/install-kubectl/) est l'outil en ligne de
commandes pour Kubernetes. Il vous permet d'interfacer avec votre cluster.

## Kubeadm

[`kubeadm (EN)`](/docs/setup/production-environment/tools/kubeadm/install-kubeadm/)
est l'outil en ligne de commandes pour mettre en place un cluster Kubernetes
sécurisé sur une infrastructure physique, des serveurs cloud ou une machine
virtuelle (actuellement en alpha).

## Minikube

[`minikube`](https://minikube.sigs.k8s.io/docs/) est un outil vous permettant
de mettre en place sur votre machine locale un cluster Kubernetes à une Node
pour le effectuer vos développement et vos tests.

## Dashboard

[`Dashboard (EN)`](/docs/tasks/access-application-cluster/web-ui-dashboard/),
l'interface web utilisateur de Kubernetes, vous permet de déployer des
applications contenerisées dans votre cluster Kubernetes, de résoudre les
problèmes et de gérer le cluster et ses ressources.

## Helm

[`Kubernetes Helm (EN)`](https://github.com/kubernetes/helm) est un outil
permettant de gérer des ensembles pré-configurés de ressources Kubernetes.
Ces ensembles de ressources s'appellent des `charts`.

Utilisez Helm pour:
* Trouver et utiliser une application populaire facilement grâce à son `chart`
* Partager vos propres applications en tant que `chart` Kubernetes
* Créer des déploiements reproductibles pour vos applications Kubernetes
* Gérer intelligemment vos fichiers de manifest Kubernetes
* Gérer les releases de packages Helm

## Kompose

[`Kompose (EN)`](https://github.com/kubernetes/kompose) est un outil permettant
aux utilisateurs de `Docker Compose` de migrer en douceur vers Kubernetes.

Utilisez Kompose pour:
* Traduire un fichier docker-compose en objets Kubernetes
* Se diriger d'un environnement de développement local Docker vers une
application gérée dans Kubernetes
* Convertir des fichiers `yaml` docker-compose v1 ou v2 ou des
[Bundles d'Applications Distribuées](https://docs.docker.com/compose/bundles/)
