---
title: Documents de Référence
linkTitle: "Référence"
main_menu: true
weight: 70
content_type: concept
---

<!-- overview -->

Cette section de la documentation de Kubernetes contient les informations de références.



<!-- body -->

## Documents de Référence de l'API

* [Vue d'ensemble de l'API de Kubernetes](/docs/reference/using-api/)
* Documentation de référence de l'API des anciennes versions de Kubernetes:
  * [1.19](https://v1-19.docs.kubernetes.io/fr/docs/reference/)
  * [1.18](https://v1-18.docs.kubernetes.io/fr/docs/reference/)
  * [1.17](https://v1-17.docs.kubernetes.io/fr/docs/reference/)
  * [1.16](https://v1-16.docs.kubernetes.io/fr/docs/reference/)

## Bibliothèques client de l'API

Pour appeler l'API de Kubernetes depuis un langage de programmation on peut utiliser une [bibliothèque client](/docs/reference/using-api/client-libraries/). Les bibliothèques client officiellement supportées sont:

* [Kubernetes Go client library](https://github.com/kubernetes/client-go/)
* [Kubernetes Python client library](https://github.com/kubernetes-client/python)
* [Kubernetes Java client library](https://github.com/kubernetes-client/java)
* [Kubernetes JavaScript client library](https://github.com/kubernetes-client/javascript)

## Documents de Référence des outils en ligne de commande (CLI)

* [kubectl](/docs/reference/kubectl/overview/) - Principal outil en ligne de commande (CLI) pour exécuter et gérer un cluster Kubernetes.
    * [JSONPath](/docs/user-guide/jsonpath/) - Guide de la syntaxe des [expressions JSONPath](http://goessner.net/articles/JsonPath/) avec kubectl.
* [kubeadm](/docs/admin/kubeadm/) - Outil en ligne de commande (CLI) pour provisionner facilement un cluster Kubernetes sécurisé.
* [kubefed](/docs/admin/kubefed/) - Outil en ligne de commande (CLI) pour aider à administrer des clusters fédérés.

## Documents de Référence pour la configuration

* [kubelet](/docs/admin/kubelet/) - Le principal *agent* qui s'exécute sur chaque noeud. Kubelet prends un ensemble de PodSpecs et s'assure que les conteneurs qui y sont décrit s'exécutent correctement.
* [kube-apiserver](/docs/admin/kube-apiserver/) - L'API REST qui valide et configure les données des objects de l'API tels que les Pods, Services, Deployments ...
* [kube-controller-manager](/docs/admin/kube-controller-manager/) - Démon en charge de la principale boucle de régulation (core control loop) de Kubernetes.
* [kube-proxy](/docs/admin/kube-proxy/) - S'occupe de reacheminer (forwarding) simplement les flux TCP/UDP ou bien en utilisant un Round-Robin sur un ensemble de back-ends.
* [kube-scheduler](/docs/admin/kube-scheduler/) - Ordonnanceur (scheduler) qui gère la disponibilité, la performance et la capacité.
* [federation-apiserver](/docs/admin/federation-apiserver/) - Serveur API pour les clusters fédérés.
* [federation-controller-manager](/docs/admin/federation-controller-manager/) - Démon en charge de la boucle de régulation (core control loop) d'une fédération de clusters Kubernetes.

## Documents de Conception

* [Architecture de Kubernetes](https://git.k8s.io/community/contributors/design-proposals/architecture/architecture.md)
* [Vue d'ensemble des documents de conception de Kubernetes](https://git.k8s.io/community/contributors/design-proposals).


