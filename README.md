# Sponsorships
<a href="https://github.com/huff-language">@huff-language</a>

@[TBAsecret👀]

# Sponsor address
0x123...xyz (or Sponsor'sENSGoesHere.eth)

---

# What is this?
This repo is a mockup of how you could hack together a way that onchain sponsorship payments could be displayed on Github, without Github needing to turn on native support for crypto payments.

# How it would work
* There would be two template repos:
  * Sponsors (for projects)
  * Sponsorships (for sponsors)
* The Sponsors repo would contain a readme with a widget where either a one-time or recurring (via <a href="https://www.loopcrypto.xyz/">loopcrypto</a>?) donation could be made to the project
* If the address the payment is sent from is listed in the sponsor's Sponsorships repo as their grantor address, the project's Sponsors repo will update to include sponsor's Github handle (w link) on a list of sponsors, ordered by projected/cumulative annual donation amount to the project
* The sponsor's Sponsorships repo will similarly update to include the project's Github handle (w link) on a list of sponsored projects, ordered by projected/cumulative annual donation amount given to each project

Nascent will pay a 500 DAI bounty for the first good-faith, functional, open-source implementation that meets the casual spec above
