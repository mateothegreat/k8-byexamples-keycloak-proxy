<!--
#                                 __                 __
#    __  ______  ____ ___  ____ _/ /____  ____  ____/ /
#   / / / / __ \/ __ `__ \/ __ `/ __/ _ \/ __ \/ __  /
#  / /_/ / /_/ / / / / / / /_/ / /_/  __/ /_/ / /_/ /
#  \__, /\____/_/ /_/ /_/\__,_/\__/\___/\____/\__,_/
# /____                     matthewdavis.io, holla!
#
#-->

[![Clickity click](https://img.shields.io/badge/k8s%20by%20example%20yo-limit%20time-ff69b4.svg?style=flat-square)](https://k8.matthewdavis.io)
[![Twitter Follow](https://img.shields.io/twitter/follow/yomateod.svg?label=Follow&style=flat-square)](https://twitter.com/yomateod) [![Skype Contact](https://img.shields.io/badge/skype%20id-appsoa-blue.svg?style=flat-square)](skype:appsoa?chat)

#

> k8 by example -- straight to the point, simple execution.
Deploy Keycloak using https://github.com/mateothegreat/k8-byexamples-keycloak.

## Usage

```sh
   __  ______  ____ ___  ____ _/ /____  ____  ____/ /
  / / / / __ \/ __  __ \/ __  / __/ _ \/ __ \/ __  /
 / /_/ / /_/ / / / / / / /_/ / /_/  __/ /_/ / /_/ /
 \__, /\____/_/ /_/ /_/\__,_/\__/\___/\____/\__,_/
/____
                        yomateo.io, it ain't easy.

Usage: make <target(s)>

Targets:

  dump/submodules      Output list of submodules & repositories
  install              Installs manifests to kubernetes using kubectl apply (make manifests to see what will be installed)
  delete               Deletes manifests to kubernetes using kubectl delete (make manifests to see what will be installed)
  get                  Retrieves manifests to kubernetes using kubectl get (make manifests to see what will be installed)
  get/all              Retrives all resources (in color!)
  describe             Describes manifests to kubernetes using kubectl describe (make manifests to see what will be installed)
  context              Globally set the current-context (default namespace)
  shell                Grab a shell in a running container
  dump/logs            Find first pod and follow log output
  dump/manifests       Output manifests detected (used with make install, delete, get, describe, etc)


Tools:

  get/myip              Get your external ip
  testing-curl          Try to curl http & https from $(HOST)
  testing/curlhttp      Try to curl http://$(HOST)
  testing/curlhttps     Try to curl https://$(HOST)
  testing/getip         Retrieve external IP from api.ipify.org
  git/update            Update submodule(s) to HEAD from origin
  git/up                Update all .make submodules
  rbac/grant-google     Create clusterrolebinding for cluster-admin
```

## Install

```sh
make install
```

## Delete

```sh
make delete
```
