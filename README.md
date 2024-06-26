# fleet-infra

This is an example repository for multi-cluster Flux. Not guaranteed to be good
example, but it is still in use as of May 13 2024 and if you see commits, it
probably continues to be in use. No telling, YMMV, herein be scary dragons.

Actual clusters are hosted from here, and it is tested regularly through use.

## OIDC

These clusters use Dex for GitHub OIDC, which is configured based on:

* [Weave GitOps Guides: Setting Up Dex](https://gitops.weave.works/docs/0.29.0/guides/setting-up-dex#deploy-dex)

There should be no secrets published here, except for ones that can be public.

(There is a published OIDC client secret there, which we have dutifully copied
and reused deliberately, but you should generate your own and probably should
not publish it in an open access venue or public forum space as I have done.)

## Access

If you are meant to have access to these clusters, follow the instructions here
to gain direct access with `kubectl`.

* [Howto (howard.moomboo.space)](https://howto.howard.moomboo.space)

This is not a production system, but webhooks may be treated like production.

Services are provided gratis by an owner, come with no warranty or guarantee of
continued or reliable service, and may be turned off sometimes, periodically,
on an unscheduled basis, or have irregular service. Be ye here fore- warned!

These "production" instances may be deleted, could go away forever at any time!
Depend on these systems at your own risk, (what are you even still doing here.)
