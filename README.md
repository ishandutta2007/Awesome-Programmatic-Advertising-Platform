# Awesome-Programmatic-Advertising-Platform

## Top Programmatic Advertising Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Demand-Side Platforms (DSPs), Real-Time Bidding, Programmatic Buying & Omnichannel Activation*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Programmatic Advertising**. These systems enable automated, real-time buying of digital advertising inventory across display, video, CTV, audio, and other channels through demand-side platforms (DSPs) and related technology.



**Examples** include The Trade Desk, Google Display & Video 360, Xandr (Microsoft Invest), Yahoo DSP, Amazon DSP, StackAdapt, Adform, MediaMath, Basis Technologies, and Smadex (the category leaders).



**Open-source emphasis**: Full-featured commercial DSPs dominate the market. Open-source activity is concentrated at the lower levels — RTB bidder engines, OpenRTB libraries, and experimental ad platforms. There is no widely adopted open-source equivalent to a major independent DSP. This section lists the strongest available open building blocks and is realistic about the gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[The Trade Desk](https://www.thetradedesk.com/)**  

  Leading independent demand-side platform known for broad inventory access, strong CTV capabilities, and identity solutions such as UID2.



- **[Google Display & Video 360 (DV360)](https://marketingplatform.google.com/about/display-video-360/)**  

  Google’s enterprise DSP tightly integrated with YouTube, Google inventory, and the broader Google Marketing Platform.



- **[Xandr / Microsoft Invest](https://www.xandr.com/)**  

  Microsoft’s demand-side platform (formerly Xandr) offering premium inventory and Microsoft first-party data advantages.



- **[Yahoo DSP](https://www.yahooinc.com/advertising/)**  

  Yahoo’s demand-side platform providing access to Yahoo inventory and broader programmatic channels.



- **[Amazon DSP](https://advertising.amazon.com/solutions/products/amazon-dsp)**  

  Amazon’s demand-side platform leveraging first-party shopping and browsing data for commerce-oriented advertising.



- **[StackAdapt](https://www.stackadapt.com/)**  

  Mid-market, self-serve programmatic platform supporting multi-channel campaigns including CTV and native.



- **[Adform](https://www.adform.com/)**  

  Independent advertising technology platform offering DSP and related programmatic capabilities with a focus on transparency.



- **[MediaMath](https://www.mediamath.com/)**  

  Programmatic platform historically focused on omnichannel buying and data-driven activation.



- **[Basis Technologies](https://basis.com/)**  

  Agency-oriented platform combining programmatic buying with planning and workflow tools.



- **[Smadex](https://www.smadex.com/)**  

  Programmatic platform specializing in mobile and app-based advertising.



## Open-Source GitHub Projects

- **[RTBkit](https://github.com/rtbkit/rtbkit)**  

  Open-source real-time bidder framework that allows building and deploying custom RTB bidders for display advertising.



- **[vanilla-rtb and related bidder engines](https://github.com/vanilla-rtb)**  

  High-performance open-source RTB engines and frameworks for building custom bidding applications.



- **[OpenRTB libraries and serialization tools](https://github.com/)**  

  Open implementations of the OpenRTB specification for bid request/response handling in various languages.



- **[Experimental open DSP / ad platform projects](https://github.com/)**  

  Community efforts to build partial or educational demand-side or full-stack ad platforms (SSP/ADX/DSP modules).



- **[Open ad servers and serving engines](https://github.com/)**  

  Open-source ad servers that can be used for direct or private marketplace inventory (complementary to programmatic buying).



- **[Bidding strategy and optimization open experiments](https://github.com/)**  

  Research and prototype code for bid shading, pacing, and optimization algorithms.



- **[Identity and privacy-enhancing open tools](https://github.com/)**  

  Open components related to cookieless identity, consent, and privacy-safe targeting signals.



- **[Reporting and log processing open pipelines](https://github.com/)**  

  Tools for ingesting and analyzing RTB logs and campaign performance data.



- **[Creative and ad format open libraries](https://github.com/)**  

  Supporting open tools for ad creative handling and validation in programmatic workflows.



- **[Awesome-RTB and curated resource lists](https://github.com/vanilla-rtb/awesome-rtb)**  

  Curated collections of open RTB frameworks, libraries, and related resources.



### Additional Strong Open-Source Options

- Using open RTB engines (RTBkit, vanilla-rtb, etc.) when building a custom bidder for specialized or private-market needs.

- Leveraging OpenRTB libraries for integration or educational purposes.

- Combining open ad servers with commercial DSP access for hybrid stacks.

- Accepting that scale, inventory access, identity graphs, CTV reach, brand safety, and operational reliability of major DSPs cannot currently be matched by open-source alternatives.

- Focusing open-source efforts on the bidder/algorithm layer while relying on commercial platforms for supply and activation.



**Frameworks for building custom systems**: Deploy an open RTB bidder engine → implement bidding logic and budget controls → connect to exchanges via OpenRTB → handle win notices and reporting → optionally integrate with commercial DSPs for broader reach. This is suitable for advanced ad-tech teams building specialized or private-market solutions. The vast majority of advertisers and agencies continue to rely on commercial DSPs (The Trade Desk, DV360, Amazon DSP, StackAdapt, etc.) for production programmatic buying.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Programmatic advertising involves significant spend, data privacy (GDPR, CCPA, etc.), brand safety, and fraud risks. Open-source RTB components require deep expertise in ad tech, security, and compliance. Errors can result in wasted budget or regulatory issues. This list is not advertising, legal, or financial advice.



---

**Made for media buyers, ad-tech engineers, and agencies who want transparent and efficient programmatic activation.**

Let's keep programmatic advertising competitive, measurable, and as open as practical.
