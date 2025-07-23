# Future breaking changes

There are defaults in our projects that for backward compability reasons hide good features from our
users. Here we list these so that we can do the changes when changing the major version or maybe
when we change the project name.

## Switch from kubectl apply as the default reconciliation method

In principle I think you could make kubectl apply --prune work properly with ApplySets. But it still
in alpha and would currently require some legwork to get it to work cluster wide.

https://kubernetes.io/blog/2023/05/09/introducing-kubectl-applyset-pruning/

https://github.com/kubernetes/enhancements/issues/3659#issuecomment-1542965531

It should be hassle free to switch to kpt live apply. A reason not to do this is that the kpt
project isn't very active. If we could make switching to kapp hassle free that might be a better
option. When I tried to swith to kapp from kubectl apply I got into problems, but those might be
avoidable.

This has been discussed in the past:

https://github.com/carvel-dev/kapp/issues/204

https://github.com/carvel-dev/kapp/issues/138#issuecomment-2282953076

https://github.com/carvel-dev/kapp/issues/214

So the problem is that to make the switch to kapp hassle free we need to use options that would not
be compatible with the options currently set in Makefile.mk.

kapp seem to have neither of the following problems with kubectl apply:

client side: can't handle large resources due to kubectl.kubernetes.io/last-applied-configuration
server side: fields that are removed in manifest might not be removed in resource

## Use get-selectors-by-release-and-clean.sh by default?

## Let reusePullRequest be the default in jx-promote

## Let reusePullRequest be the default in jx-updatebot

This also demands defaults for the label used to identify PRs.

## Remove support for jenkins as a pipeline runner

## Upgrade jx-api to v4 from v4beta1

Remove fields marked as deprecated

## Make sparse checkout default
