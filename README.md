## Statement of Purpose
### Reduction in Innovation
<hr>

The [industry lifecycle](https://www.investopedia.com/terms/i/industrylifecycle.asp) represents the different stages an industry experiences throughout its lifetime. As we close in on the fourth decade of cybersecurity, our industry has entered the maturity phase of this lifecycle consisting of slowing growth and industry consolidation. This trend has already been observed with [hundreds of cybersecurity mergers and acquisitions in 2022](https://www.businesswire.com/news/home/20230206005384/en/SecurityWeek-Analysis-Over-450-Cybersecurity-MA-Deals-Announced-in-2022) and is only expected to increase.

Research has shown that when an industry enters the maturity phase and consolidation begins, [innovation decreases](https://clsbluesky.law.columbia.edu/2017/04/24/the-relationship-between-consolidation-and-innovation-in-the-drug-industry/).

As an industry, we do not defend against malicious actors and cybercrime. We are in a constant never-ending race for innovation.

We must foster innovation at all costs.

Consolidation creates silos and to foster innovation, we must remove these silos and allow for the sharing of common security data between toolsets, dashboards, and platforms.


### Fostering Innovation in a Continuous Testing Model
<hr>

At the same time as we enter the maturity phase, there’s been an increase in continuous attack surface management and continuous testing. These approaches provide a reduction in vulnerability discovery to mitigation time, fulfill compliance needs, and come with built in remediation validation.

Continuous testing should be a holistic approach that includes various functions including asset management, attack surface management, vulnerability management, and threat intelligence among others.

Research has further shown that most innovation occurs in smaller organizations where quick decision-making abilities and a greater risk appetite facilitates innovation. Industry consolidation has a negative effect on this and so **we need to create an ecosystem for both the smaller organizations and larger enterprises to thrive and work together, thus removing the silos created by industry consolidation.**

For example, Greynoise is a medium sized company that can observe new attacks in the wild. If organizations can correlate the data from Greynoise and the data in their Attack Surface Management platform, then organizations can see in real time if their assets are affected by real-world threats.

Currently, there is no widely used standard that allows for sharing of security data including, but not limited to, vulnerability management data, threat intel, and asset inventory.

We foster innovation by providing a cohesive way for all toolsets to communicate, creating the opportunity for vendor-created or organization made dashboards which give a holistic view of the organization’s security posture. **This is the goal of the Common Security Data Exchange.**


### Common Security Data Exchange
<hr>

![CSDX-diagram2](https://github.com/csdxorg/csdx/blob/main/CSDX-diagram2.jpg)

A proposed method of communicating security data in a pub/sub model with data **storage** types based on the National Information Exchange Model (NIEM) Cyber Domain.

### Goals
- Create a standard model for the sharing of common security data which
    - Uses a pub/sub protocol for instantaneous data updates
    - Uses mTLS or other secure transmission mechanism
- Create a vendor agnostic storage mechanism which allows for
    - Data import into current platform offerings
    - Creation of custom dashboards for those organizations which choose to do so
    - Integration of future data types based on standards such as STIX/TAXII


