# Future breaking changes

There are defaults in our projects that for backward compability reasons hide good features from our
users. Here we list these so that we can do the changes when changing the major version or maybe
when we change the project name.

## Switch from kuectl apply as the default reconciliation method

It should be hassle free to witch to kpt live apply. A reason not to do this is that the kpt project
seem dead. If we could make switching to kapp hassle free that might be a better option. When I
tried to swith to kapp from kubectl apply I got into problems, but those might be avoidable.

This has been discussed in the past:

https://github.com/carvel-dev/kapp/issues/204

https://github.com/carvel-dev/kapp/issues/138#issuecomment-2282953076

https://github.com/carvel-dev/kapp/issues/214

## Let reusePullRequest be the default in jx-promote

## Let reusePullRequest be the default in jx-updatebot

This also demands defaults for the label used to identify PRs.