---
layout: page
title: Masto.NYC policies and resources
---

This page lists the operational policies for [Masto.NYC](https://masto.nyc), as well as links to various user resources.

Looking for our child safety standards? [They're down here](#child-safety-standards).

## Membership policy

Anyone who lives or works in the New York metropolitan area is welcome to create an account on Masto.NYC. Business and organizations located here are also welcome!

If you don’t live or work in the area, you’re still welcome to explore the site, but please don’t make an account here. This rule is enforced against blatant offenders who don’t reside in [what Wikipedia considers the New York Metropolitan Area](https://en.wikipedia.org/wiki/New_York_metropolitan_area).

If you create an account here but end up moving away from New York, then you can still keep and continue to use your Masto.NYC account for as long as you like.

## Moderation policies

All of our moderation is driven by our server rules, listed on [the Masto.NYC About page](https://masto.nyc/about).

### Report rule-breaking behavior

We rely on our users to report content that conflicts with our server's rules. If you spot a post that breaks the rules of this server, please report it! This is true for both local and federated content.

### Rules enforcement for local users

If we receive valid complaints about a Masto.NYC user making rule-breaking posts, then we respond according to the following general pattern:

* The first infraction results in a warning.
* Subsequent infractions result in temporary suspension.
* Repeated infractions might result in permanent suspension.
* We reserve the right to skip directly to suspension for egregious infractions, at the moderators' discretion.

This graduated response does not apply to child sexual abuse and exploitation, which is handled under our [child safety standards](#child-safety-standards): those accounts are permanently suspended on the first offense.

### Blocklists and defederation

We subscribe to three denylists published by [IFTAS](https://about.iftas.org/library/denylist-resources/):

- **Do Not Interact**, their curated list of servers they recommend defederating.
- **Abandoned and Unmanaged Domains**, which covers spammers and servers nobody is running any more.
- **CARIAD at the 66% threshold**: servers that at least two thirds of the instances IFTAS observes have already blocked.

We chose a threshold rather than a hand-picked list so that this policy is something you can hold us to. "We block what two thirds of the network blocks" is checkable. IFTAS also publishes 51% and 80% versions of the same list, and if we move between them we will say so here.

**Threads is not blocked.** It appears on the list we subscribe to, and we take it off deliberately. If that changes it will be a decision made here, not something a list decided for us.

Routine updates apply automatically. When a list adds a handful of servers, we take it. When a change is unusually large — more servers at once than these lists normally move — it is held and a moderator decides before anything happens.

A block is lifted only when a moderator puts that server on our allowlist, and a batch of them is held for review the same way. A server dropping off an IFTAS list does not unblock it: those lists are not the only reason we block a server, and we are not going to restore federation with somebody because a third party stopped tracking them.

If you already follow somebody on a server that gets added, we limit that server rather than suspending it, so the people you follow are not torn away from you without warning.

At the moderators' discretion, we might from time to time block additional servers as the situation warrants. We use our own server's rules as a guide for blocking servers. For example, if we receive reports about a server whose users post a lot of targeted spam with no obvious moderation, then we might block that server.

If you want a server unblocked, or want to ask why one is blocked, then [open an issue on the repository that holds the list](https://github.com/Five-Borough-Fedi-Project/sync-blocked-fedi-domains/issues). The allowlist is a file in there, so a decision to unblock is a change you can read.

### Join us as a moderator

If you are interested in joining the Masto.NYC moderation team, then [fill out this application](https://forms.gle/bf9zVXUxTWjEZ4qSA).

## Shutdown policy

If we ever need to permanently shut down Masto.NYC services, then we will post public notice three months in advance of the planned last day. This is in adherence to the [Mastodon server covenant](https://joinmastodon.org/covenant).

## Links and resources

### Site status page

Our main status page is at <https://status.masto.nyc>.

### News-and-announcements account

To have news and announcements about Masto.NYC appear in your feed, follow [@warren](https://masto.nyc/@warren).

### Art credit

All of our server artwork is by [Marykate Carney](https://www.instagram.com/marykate_carney/).

### Infrastructure source code

[Our infrastructure source is on GitHub](https://github.com/Five-Borough-Fedi-Project/masto.nyc-docean). Feel free to open an issue with any feature requests or questions!

## DMCA Agent Information

[Here is the DMCA policy for Masto.NYC.](https://github.com/Five-Borough-Fedi-Project/org-docs/blob/main/policy-docs/dmca-policy.md)

Contact
<p>
Five Borough Fedi Project<br />
93 4th Ave, PO Box 1323<br />
New York, NY 10003
</p>
<help@masto.nyc>

## Child safety standards

Five Borough Fedi Project has a zero-tolerance policy toward child sexual abuse and
exploitation (CSAE). Child sexual abuse material (CSAM), and any other content that
sexualizes or endangers a minor, is prohibited on Masto.NYC and in the Masto.NYC app.
We remove it, permanently suspend the accounts responsible, and report apparent CSAM
to NCMEC's CyberTipline automatically. To report it to us, use the **Report** option
on any post or profile, or email <help@masto.nyc>.

[Here are the full child safety standards for Masto.NYC.](/child-safety.html)

## Press releases

* [Five Borough Fedi Project launches,
bringing independent social media to NYC](/press/5bfp-launches.html)

## Annual transparency reports

* [2024](/annual_reports/2024/index.md)
