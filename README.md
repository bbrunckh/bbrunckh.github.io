*Ben Brunckhorst, Ashley Pople and Stefan Dercon - University of Oxford*

### Background

Globally, [1.47 billion people are exposed to the risk of intense flooding](https://blogs.worldbank.org/climatechange/147-billion-people-face-flood-risk-worldwide-over-third-it-could-be-devastating); 89% of these live in low and middle-income countries. More than 1 in 3 are poor. 132 million live in extreme poverty. Evidence points to a [vicious circle of disaster loss and poverty](https://link.springer.com/article/10.1007/s41885-020-00060-5), but what if **better targeting of earlier assistance** could help break it?

### Our experience in Bangladesh

In 2020, the United Nations piloted *anticipatory* cash transfers to vulnerable households in response to severe monsoon flooding affecting millions in Bangladesh.<sup id="a1">[<sup>1</sup>](#f1)</sup> These cash transfers were activated when a 5-day forecast of river discharge exceeded a pre-determined dangerous threshold. Regions were targeted based on a rapid assessment of flood risk and socioeconomic vulnerability, and eligible households were drawn from pre-existing beneficiary lists due to COVID-19 restrictions. Cash transfers worth $53 were sent to 23,434 households using mobile money before peak flooding.

We surveyed 9,130 households 10-12 weeks later to evaluate the effect of these cash transfers. [Our evaluation](https://www.disasterprotection.org/anticipatory-cash-transfers-in-climate-disaster-response), the first of its scale and rigour in a humanitarian setting, found that **timely assistance has large welfare benefits in a climate disaster**. Cash transfers improved food security, increased evacuation and decreased asset loss. At the time of the survey, beneficiaries had higher child and adult food consumption, better mental wellbeing, engaged in less costly borrowing, and reported higher earning potential than comparable control households. These benefits accrued before a traditional response would normally arrive. Moreover, speed of delivery matters: the effect of cash is predicted to dissipate entirely if the transfer is not received within 12 days of the local flood peak.

Beyond the surprisingly persistent impacts on a wide range of outcomes, we found that the time taken to target and verify beneficiaries was a serious constraint to scaling-up anticipatory action. The complex range of factors affecting flood impacts are also difficult to assess under time-pressure, which may lead to excluding those who most need assistance, while including the less vulnerable. **What if we could identify in advance where disasters are most likely to have persistent impacts on livelihoods and well-being?** Innovative approaches from others that are harnessing machine learning to target assistance lay the groundwork. 

## The *MobileAid*<sup id="a2">[<sup>2</sup>](#f2)</sup> paradigm

Building on [advances in poverty mapping](http://www.povertymaps.net/brief/), Togo’s successful Novissi program in 2020 was one of the first public sector programs [targeting social assistance using mobile phone and satellite data](https://www.poverty-action.org/study/using-mobile-phone-and-satellite-data-target-emergency-cash-transfers-togo#footnote-1). This [MobileAid](https://medium.com/center-for-effective-global-action/how-precision-aid-and-machine-learning-based-targeting-can-complement-existing-social-protection-de3bc3211fd2) combines machine learning-based targeting, with recipient self-enrolment and contactless delivery via mobile money. It marks an important policy shift, as machine learning-based wealth estimates using non-traditional data have largely been confined to academic research in the past. Early evidence indicates **better accuracy and a greater proportion of the poorest receiving benefits** (less errors of exclusion and inclusion) compared to standard targeting practices. 

MobileAid can be deployed **rapidly** and **at scale**, making it especially well-suited in climate disasters like flooding, when [timely assistance has large welfare benefits](https://www.disasterprotection.org/latest-news/the-importance-of-being-timely-in-climate-disaster-response). Combined with innovations in [flood forecasting](https://ai.googleblog.com/2020/09/the-technology-behind-our-recent.html) and [exposure models](https://www.nature.com/articles/s41467-019-09282-y), there is incredible potential to **integrate climate disasters** in a MobileAid framework that delivers well targeted assistance in anticipation of shocks, helping break the cycle of poverty and disaster loss.

## Our approach

We propose to explore the potential of using machine learning-based targeting and flood forecasts, drawing on our Bangladesh experience and unique dataset for validation as follows: 

1. **Train deep learning algorithms** to estimate vulnerability to climate shocks over space before a flood shock, by combining poverty maps with flood specific training data: 
- Ground truth: 100,000+ household surveys from regions affected by flooding
- Inputs: satellite imagery, flood risk maps and other high resolution spatial data

2. **Identify the most vulnerable households** in the most vulnerable regions before a flood shock:
- Based on  basic household characteristics, recorded in pre-registration 
- Based on machine-learning methods using mobile phone metadata

3. **Overlay real-time event specific flood data and inundation forecasts** to highlight the most exposed regions at the onset of a disaster 

4. **Evaluate predictions against actual welfare and livelihood impacts** for almost 10,000 households surveyed after severe monsoon floods in Bangladesh

5. **Compare targeting alternatives and simulate the effect of cash transfers** using the Bangladesh cash transfer evaluation as a benchmark for pre-registered households

## An agenda to (continuously) improve

In developing this research agenda, we seek to:

- **Collaborate with government** and key institutions throughout to complement existing capabilities, ensure feasibility, streamline implementation and encourage enrolment.

- **Improve the quality and quantity of ground truth data** for training and validation by investing in a series of representative post-disaster household surveys.

- **Gain access to high-resolution inputs** that capture important information, such as mobile phone, social network or connectivity metadata during a disaster, in order to improve targeting performance.

- **Calibrate models** for location specific [evolution in flood risk](https://www.hull.ac.uk/work-with-us/research/institutes/energy-and-environment-institute/our-work/evoflood-quantifying-the-evolution-of-flood-hazard-and-risk-across-a-changing-world) and demographics so that trigger ready assistance can be targeted in a dynamic way year after year, especially in places prone to seasonal disasters. 

- **Identify biases** and refine machine learning methods so that training data and inputs are used in an effective and equitable way based on community engagement, validation and targeting performance.


<b id="f1">*1*</b> Northern Bangladesh experiences annual monsoon fluvial flooding that often exceeds the capacity of ultra-poor subsistence farming households to cope. Floods in 2020 were the highest and longest in decades. [↩](#a1)

<b id="f2">*2*</b> *MobileAid* was coined by The Centre for Effective Global Action, University of California, Berkeley. [↩](#a2)


