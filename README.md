# fleet-infra

This is an example repository for multi-cluster Flux.

Actual clusters are hosted from here, and it is tested regularly through use.

## OIDC

These clusters use Dex for GitHub OIDC, which is configured based on:

* [Weave GitOps Guides: Setting Up Dex](https://docs.gitops.weave.works/docs/guides/setting-up-dex/#deploy-dex)

There should be no secrets published here, except for ones that can be public.

(There is a published OIDC client secret there, which we have dutifully copied
and reused deliberately, but you should generate your own and probably should
not publish it in an open access venue or public forum space as I have done.)

## Access

If you are meant to have access to these clusters, follow the instructions here
to gain direct access with `kubectl`.

* [Howto (howard.moomboo.space)](https://howto.howard.moomboo.space)

This is not a production system, but it may host some production services. 🤞

Depend on these systems at your own risk, they are provided gratis by owner
come with no warranty or guarantee of continued service, and may go down
forever at any time!
