# Blockchain applications in medical law

## Summary

Privacy-preserving legal transformation: case study of Power-of-Attorney within the Polkadot ecosystem.

The aim of the work is to provide a legal framework for lawmakers and professionals within the Swiss & EU juridical systems; to inform and prepare for the upcoming privacy-preserving technology; and finally to propose concrete solutions and guidelines for the governmental authorities.

## About me

My name is Julia Stempfel, a recent law graduate with an interest in digital as well as medical aspects of the law.

Currently I am exploring the intersection between the legal and medical aspects of the Swiss health system as a student of University of Zurich, where I'm studying MedLaw to obtain a Certificate of Advanced Studies, with my final thesis being on blockchain use cases in medicine. In addition, I'm a full-time employee in law firm, specialising in medical and digitisation cases: for individuals, businesses and institutions incl. hospitals.

In my spare time, I like to deep-dive into the recent technical advancements, especially with a potential to transform the legal system. Almost two years ago I was introduced to Polkadot and independently, to zero-knowledge protocols, and it didn't take long to realise that putting the two together could bring profound changes to how the citizens' data is handled.

Like all new technological innovations, this one too needs a strong legal framework to operate in, both to expand the available market, but most importantly to make users aware of its benefits and shortcomings.


## Proposal details

In this proposal I intend to start bridging the recent gap in the regulations regarding blockchain technology. Among the myriad of applications of the tech to a legal framework, I think a particularly appealing one is providing legislation for an on-chain Power of Attorney. Due to its relative simplicity from the technical execution perspective (relative: e.g. to issuing digital identities to all the country's citizens), it can be considered somewhat of a low-hanging fruit. Blockchain community is yet to demonstrate a working and useful integration with the real world, and this would be a good candidate. I would like to analyse the Polkadot ecosystem as a case study for privacy-enabling computation. Its high level of programmability and the flexible governance structure make it a good candidate for the task. A government that is to adopt such a proposal would be easier to convince to build it out as a parachain, where such entity would have full control over the code, rather than simply launching a smart contract. Furthermore, the customizable parachain governance is a very appealing feature to an authority, and it can not be found in other blockchains.

While some countries within Europe will inevitably follow their own standards that fundamentally differ from the majority, most of the countires tend adopt a similar legal stance. The regulators in any country will in the end struggle with the same questions regarding digitising Power of Attorney. I aim to provide a general framework that can be used as a starting point for the regulators in any European country. I will base my concrete examples on the Swiss legal system, which I am most familiar with, and which is one of the most advanced in the field of regulating blockchain technology.

While I do not have any background in cryptography, I am comfortable reading at a high-level about how blockchain works. I will try to cover the technical parts by myself, but if needed, can reach out to colleagues at ETH Zurich, [Stack Exchange](https://substrate.stackexchange.com/) or the Polkadot/Kusama technical channels for a more in-depth description.

Akin to my previous work, I intend to publish the article produced as part of this proposal in legal academic journals, such as weblaw.ch - the leading online legal publishing house. Last year I have submitted an extensive research article to Weblaw (86 pages), which can be found [here](https://www.weblaw.ch/competence/weblaw_inside/weblaw_aktuell/2022/2/neu_erschienen_stempfel.html) in German. For convenience, I have written an abstract in English which can be accessed on [my github](./abstract_GP_training_legal_guidance.md).

The original documents will be submitted on [Github](https://github.com/legal-julia/power-of-attorney-on-polkadot). Due to the target audience requirements (Swiss academic journal) the version for the journal will only be submitted in German. As with all academic journals, one cannot guarantee acceptance. I will exercise all my skills and resources to produce documents most likely to pass the peer review process.

Initially I had 4 topics in mind for the articles, although the scope of the proposal will be limited to 1 for now. Thanks to the feedback from the Kusama community (Matrix chat and a [Polkassembly post](https://kusama.polkassembly.io/post/1505)) I've decided to initially limit the proposal to 1 most popular article on Power of Attorney. More can follow if the community (Polkadot as well as legal) response is positive. For reference, I'm leaving the remaining topic suggestions below:

1. Patient medical records: current technology overview, upcoming challenges and an outlook of how Polkadot could come to the rescue.

2. How cryptography could help overcome privacy concerns in gene-sequencing: using zero-knowledge and encrypted computation for secure gene analysis with the help of a zero-knowledge parachain on Polkadot.

3. On-chain Power of Attorney: potential benefits for the Swiss legal system.

4. Risk-free patent applications: using commit-reveal for patent protection

The goal for each article is to have 8-10 pages of informative and on-point content (incl. legal and technological aspects), plus additional pages for references & appendix, if needed.

## Deliverables

I estimate the time to research, compose, translate and prepare one article for publication to be about 1 month of full time work. Since I'm planning to write the articles alongside work and further education, my proposal is to dedicate about 3 months of 1/3 time committent to each article, totalling 9 months to complete the entire project. I'm assuming standard rates for an entry-level lawyer in Switzerland of CHF 75/h (~$78).

- Cost per article = (3 months * 160h * 75 CHF * 1/3) = 12,000 CHF
- Total cost = 1 article * 12,000 = 12,000 CHF

For each article, I estimate the structure to be the following:
- Time allocation: 160h
- Deliverables:
  * Research and write-up of the article body: 150h
  * Translation (in parallel with the writing): 5h
  * Preparation for journal submission: 5h

### Article #1
On-chain Power of Attorney: challenges and promises for a legal system.
- How is PoA currently enforced in EU & Switzerland, who benefits from it and who can abuse it?
- Private key ?= full access revisited: a need for additional, trusted verification (or else take all my money).
- A partially government-controlled blockchain - pros and cons. Could a parachain be the solution?
- Encrypted 'allow-revoke' mechanism, revealable only to selected parties, by the means of substrate chain and a user-friendly app.
