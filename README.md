# Fleet is Retired

This notice is to inform you that on Wednesday, November 4th, 2020 Kolide has
officially retired Fleet. This repository will be left up in an archived state
for posterity, and to assist existing Fleet users.

Please refer to the FAQ below for additional information [including
migration options](#q-what-should-i-use-instead-of-fleet).

## FAQ

### Q: What was Kolide Fleet?

Kolide Fleet was an open-source Osquery Fleet Manager written in Go and Javascript.

### Q: What does retiring entail?

Effective immediately, Kolide will no longer promote, endorse,
support, or update Fleet. Any infrastructure outside of Github
supporting downloads or packages will also be retired.

Since we will not be updating Fleet with any security patches or
accepting bug bounty reports, it is important that you find a
[suitable alternative right
away](#q-what-should-i-use-instead-of-fleet).

### Q: Is Kolide retiring Kolide Launcher?

No. [Kolide Launcher](https://github.com/kolide/launcher) is a major
component of our SaaS product, and we fervently believe in keeping the
endpoint agent technology open-source.

### Q: Why is Kolide retiring Fleet?

We are proud and humbled by all of the organizations using Fleet
today.  We think it’s a great solution to monitor server-based
infrastructure using Osquery. We recognize many organizations depend
on Fleet so retiring it was not a decision we took lightly.

Since 2019, Kolide has found success building a SaaS endpoint security
product around the philosophy of User Focused Security. This
philosophy is about building a foundation of trust between the
security team and the end-users of a given organization.

When Fleet is used to obtain visibility on end-user devices, it is not
software that enables an honest and accountable relationship between
the security team and the end-users who are subject to the data
collection Fleet enables.

Specifically, Fleet allows administrators to vacuum up large
quantities of end-user data without providing those users with any
visibility or tools to understand or control that process. Fleet does
not hold security practitioners accountable for the data they collect
or how it will be ultimately used.  In fact, many folks reach out to
us asking how to use Fleet and Osquery together to collect things like
web browser history, device geolocation, and other personal
information from devices. These objectives are antithetical to our
company’s values. At Kolide these values are non-negotiable and we no
longer want to enable software under our name and branding that
enables those use-cases.

While we could change Fleet to meet these ideals and be compatible
with our philosophy, we would rather invest that same energy and
resources toward improving our SaaS app.

Given the facts above, we have decided it is in our best interest to retire
the project and thoroughly explain our rationale.

### Q: Why retire Fleet now?

Kolide has not substantially contributed to Fleet for over 2 years.
Recently, an active contributor reached out to let us know they were
planning on forking it and asked for our blessing. This recent
reach-out caused us to re-evaluate if it’s something Kolide wants to
continue to directly invest in or endorse.

After going through that exercise, we determined that Fleet was built by a
different Kolide; one that embodied different values and had different goals.
Due to the mismatch in ideals and the opportunity to distance ourselves from
Fleet, we have decided now is the best time to retire the project and let the
community decide on a suitable fork to follow.

### Q: What should I use instead of Fleet?

**Kolide no longer endorses the use of Fleet for monitoring end-user devices.**

If you are looking to get additional visibility on end-user devices
and want to do it **honestly**, you should check out [Kolide
K2](https://kolide.com).  It’s a refreshing take on how to use
technologies like Osquery and Slack to achieve the security team’s
goals while simultaneously respecting end-users and their privacy.

If you use Fleet to monitor servers and are looking for a direct
migration path https://github.com/fleetdm/fleet appears to be the
first of many promising forks.

We will update this space with forks that best
support that use case.

Also, since Fleet is open source under the permissive MIT license, you
are of course free to fork it and build your own version. Our only ask
is you do not associate Kolide or our branding as a means of promoting
or endorsing any derivative of Fleet you create.


### Q: Where is the fleet source code

Security vulnerabilities have been reported since we formally retired
Fleet. As such, we have deleted the code. Older version can be found
in the [commit history](https://github.com/kolide/fleet/commits/master)
and the past [releases](https://github.com/kolide/fleet/releases).

## Kolide SaaS

Want to go directly to insights?

Try our [osquery SaaS
platform](https://kolide.com/?utm_source=oss&utm_medium=readme&utm_campaign=fleet)
providing insights, alerting, fleet management and user-focused
security tools. We also support advanced aggregation of osquery
results for power users. Get started immediately, with your 14-day
free trial
[today](https://kolide.com/signup?utm_source=oss&utm_medium=readme&utm_campaign=launcher). Launcher
packages customized for your organization can be downloaded in-app
after signup.
