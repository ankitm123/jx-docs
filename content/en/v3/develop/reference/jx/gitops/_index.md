---
title: jx gitops
linktitle: gitops
type: docs
description: 
aliases:
  - jx-gitops
---

## jx gitops

GitOps utility commands

### Usage

```
jx gitops
```

### Synopsis

GitOps utility commands

### Options

```
  -h, --help   help for jx-gitops
```

### SEE ALSO

* [jx gitops annotate](jx-gitops_annotate)	 - Annotates all kubernetes resources in the given directory tree
* [jx gitops apply](jx-gitops_apply)	 - Performs a GitOps regeneration and apply on a cluster git repository
* [jx gitops condition](jx-gitops_condition)	 - Runs a command if the condition is true
* [jx gitops copy](jx-gitops_copy)	 - Copies resources (by default confimaps) with the given selector or name from a source namespace to a destination namespace
* [jx gitops gc](jx-gitops_gc)	 - Commands for garbage collecting resources
* [jx gitops git](jx-gitops_git)	 - Commands for working with Git
* [jx gitops hash](jx-gitops_hash)	 - Annotates the given files with a hash of the given source files for ConfigMaps/Secrets
* [jx gitops helm](jx-gitops_helm)	 - Commands for working with helm charts
* [jx gitops helmfile](jx-gitops_helmfile)	 - Commands for working with helmfile
* [jx gitops image](jx-gitops_image)	 - Updates images in the kubernetes resources from the version stream
* [jx gitops ingress](jx-gitops_ingress)	 - Updates Ingress resources with the current ingress domain
* [jx gitops jenkins](jx-gitops_jenkins)	 - Commands for working with Jenkins GitOps configuration
* [jx gitops kpt](jx-gitops_kpt)	 - Commands for working with kpt packages
* [jx gitops kustomize](jx-gitops_kustomize)	 - Generates a kustomize layout by comparing a source and target directories
* [jx gitops label](jx-gitops_label)	 - Updates all kubernetes resources in the given directory tree to add/override the given label
* [jx gitops lint](jx-gitops_lint)	 - Lints the gitops files in the file system
* [jx gitops namespace](jx-gitops_namespace)	 - Updates all kubernetes resources in the given directory to the given namespace
* [jx gitops plugin](jx-gitops_plugin)	 - Commands for working with plugins
* [jx gitops postprocess](jx-gitops_postprocess)	 - Post processes kubernetes resources to enrich resources like ServiceAccounts with cloud specific sensitive data to enable IAM rles
* [jx gitops pr](jx-gitops_pr)	 - Commands for working with Pull Requests
* [jx gitops rename](jx-gitops_rename)	 - Renames yaml files to use canonical file names based on the resource name and kind
* [jx gitops repository](jx-gitops_repository)	 - Commands for working with source repositories
* [jx gitops requirement](jx-gitops_requirement)	 - Commands for working with jx-requirements.yml
* [jx gitops sa](jx-gitops_sa)	 - Commands for working with kubernetes ServiceAccount resources
* [jx gitops scheduler](jx-gitops_scheduler)	 - Generates the Lighthouse configuration from the SourceRepository and Scheduler resources
* [jx gitops split](jx-gitops_split)	 - Splits any YAML files which define multiple resources into separate files
* [jx gitops upgrade](jx-gitops_upgrade)	 - Upgrades the GitOps git repository with the latest configuration and versions the Version Stream
* [jx gitops variables](jx-gitops_variables)	 - Lazily creates a .jx/variables.sh script with common pipeline environment variables
* [jx gitops version](jx-gitops_version)	 - Displays the version of this command
* [jx gitops versionstream](jx-gitops_versionstream)	 - Administer the cluster version stream settings
* [jx gitops webhook](jx-gitops_webhook)	 - Commands for working with WebHooks on your source repositories

###### Auto generated by spf13/cobra on 29-Mar-2021
