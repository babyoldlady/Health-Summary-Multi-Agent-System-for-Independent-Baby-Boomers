# Health-Summary-Multi-Agent-System-for-Independent-Baby-Boomers
The Boomer Health Summary Multi-Agent System is designed to support the rapidly growing aging population as they navigate increasingly complex medical information, specialists, and treatment plans.

**Course:** ITAI 2376 - Deep Learning  
**Project Designer** Hillary (Dreyer) Bruton 
**Project Option:** Option 3 - Multi-Agent Collaborative System

## Project Overview

### Description of Agent
The Boomer Health Summary Multi-Agent System is designed to support a rapidly growing aging population (AKA Baby Boomers) as they navigate increasingly complex medical information, specialists, and treatment plans. Today’s Baby Boomers are living longer, staying active, and want to remain independent decision-makers in their healthcare. However, they often face a fragmented medical landscape: cardiologists, endocrinologists, dermatologists, rheumatologists, primary care, urgent care, personal training coaches, dieticians, and various diagnostic centers all generate separate notes, recommendations, and visit summaries. 

Without a central person or system to connect these dots, important information can remain siloed, overlooked, or misunderstood.

This project aims to create an AI-driven multi-agent system to help older independent adults, perhaps without the assistance of a caretaker or trusted health adviser, gain a clear understanding of their total health picture. Instead of filtering through pages of jargon, users will be provided with an organized, patient-friendly overview of their diagnoses, medications, symptoms, test results, and follow-up instructions. To be clear, this multi-agent system only provides medical INFORMATION and helps a user organize their own collected medical data. In no way does this system replace the diagnoses or patient care of medical professionals. 

The system leverages multiple specialized agents: the extractor, educator, cross-checker, and summarizer. Each agent aims to ultimately process documents to produce a cohesive health brief for the user. 

The long-term vision is to empower older adults who may not have nearby family support or find it difficult to understand the guidance of their caregivers. The system promotes independence by providing a structured and holistic view of a user's health across various specialties. This aids users in recognizing potential concerns earlier, reduces confusion and information overload, and encourages more effective communication with a user's healthcare provider team.

### Problem Background & Context

#### Demographics: Size and Age of Boomer Population 
According to Wikipedia, the generation known as Baby Boomers generally comprises Americans born between 1946 and 1964 and is one of the largest living cohorts in U.S. history. As of recent estimates, there are about 76.4 million Baby Boomers in the United States.

#### Changing Living Arrangements & Decline of Traditional Family Networks
According to the organization Rise, a significant share of older Americans live alone: as of 2023, about 28% of people aged 65 and older live by themselves rather than in institutional settings. Historically, many people relied on adult children or extended family to help coordinate care. Indeed, in 2022, adult children remained the largest group of family caregivers for older adults, but the share has declined over time. Broader societal changes have contributed to this shift, including an increase in “solo aging”, described as childless seniors, divorced or widowed, or those whose children live far away; higher female life expectancy; mobility; changes in marital patterns; and smaller families. Many older adults no longer have immediate nearby family who can consistently help interpret their medical information, coordinate appointments, or provide oversight of multiple treatments. This increases the risk of fragmented care, missed medication conflicts, and overlooked test results.

#### Typical Age for Increased Medical Needs 
Boomers presently range in age from about 61 to 79 years old. The U.S. Census Bureau currently projects that the baby boom population will total 61.3 million in 2029, when the youngest reach age 65.

People need more regular and complex medical care around retirement age and beyond, indicating that Americans are on the brink of a substantial increase in demand for health services, chronic disease management, and care coordination. With aging, there is an increased likelihood of multiple comorbidities, overlapping medications, specialist visits, diagnostic tests, and follow-up care. This often overwhelms even the most engaged individuals and can result in a fragmented medical history across different providers. Ultimately, this makes it difficult to maintain a cohesive view of a person's comprehensive health picture.

#### Are Boomers Living Longer But Necessarily Healther Than Previous Generations
U.S. life expectancy increased from 68 years in 1950 to 79 years in 2013 according to the Population Reference Bureau, an organization with the mission to analyze population data to ensure research and its applications are used widely by decisionmakers, advocates, and media. Actuarial estimates suggest substantial further longevity. For example: a non-smoking, healthy 60-year-old woman is estimated to have a > 50% chance of living to 90; a 60-year-old man with similar characteristics has a roughly 42% chance of reaching 90.

A recent multi-generation study (covering the U.S., UK, and Europe) found that compared with earlier-born cohorts, Boomers are more likely to experience chronic diseases (cancer, heart disease, lung disease, diabetes, high cholesterol) as they enter their 50s and 60s. We must recognize that these numbers may also be significantly "off" because of the use of better diagnostic tools, more frequent and consistent medical care, and a higher expectation for a status quo state of health. The study concluded that although Boomers are living longer, they are living longer in poorer health, with higher rates of chronic disease, disability, and decreased ability to perform daily tasks. Another analysis suggests that gains in healthy life expectancy — years lived in full health — have not matched the gains in overall life expectancy. That is, more years are being added to life, but many of those years may include illness or disability.

#### What Boomers Want: Independence, Autonomy and Control
Many older adults have a strong desire to remain independent, age in their own homes or communities, and manage their lives rather than rely entirely upon institutional care. Independence in this context infers retaining control over daily living, health decisions, and being able to access and understand one's own medical information - even when cognitive or physical abilities start to decline. However, given the American modern medical landscape, with multiple specialists, disparate medical records, systems that don't talk to one another, complex jargon and an overwhelming amount of records, maintaining independence often becomes more challenging with age - especially without family nearby or a coordinator. 

#### Boomer Children Are Also Aging and Stretched
According to a 2025 report, roughly 1 in every 4 U.S. adults is a caregiver for an adult or child with illness or disability. The number of family caregivers caring for older adults increased from 18.2 million in 2011 to 24.1 million in 2022. However, the share of adult children among family caregivers has declined: while adult children remain the largest group providing care, their representation dropped over time (for example, from higher percentages in the past to ~ 40.7% in 2022 among caregivers for older adults). Many of these caregivers also have their own competing demands (work, children, other obligations), and as populations age, caregivers themselves are getting older.

### Problem Statement
The U.S. is entering a critical demographic transition as nearly 76 million Baby Boomers move into older adulthood, a stage of life characterized by increased medical needs, multiple chronic conditions, and frequent interactions with specialists. While Boomers are living longer than previous generations, research shows they are not necessarily living healthier; many are aging with complex comorbidities, fragmented care, and declining functional ability. At the same time, the traditional support structures that once helped older adults navigate the healthcare system are eroding. Nearly one-third of Americans over 65 now live alone, and although adult children remain the largest group of family caregivers, their capacity to provide ongoing care is diminishing due to geographic distance, work demands, or their own aging.

This convergence of factors—longer lifespan paired with higher rates of chronic disease, reduced informal caregiving, and a highly specialized, siloed medical system—creates a significant barrier to care coordination and personal health understanding. Older adults overwhelmingly express a desire to remain independent and in control of their health decisions, yet the complexity of modern healthcare documentation makes this independence difficult to maintain without support. Many Boomers must interpret jargon-heavy notes, reconcile information from multiple specialists, and track medications and follow-up plans on their own, often without a comprehensive view of their overall health.

As both older adults and their adult children face mounting pressures, there is a widening gap in the tools available to help aging individuals manage and understand their medical information in a clear, accessible, and holistic way. This gap underscores the need for systems that can consolidate, interpret, and clearly summarize cross-specialty health data so older adults can make informed decisions, maintain autonomy, and anticipate potential issues that might otherwise go unnoticed.

The Boomer Health Summary Multi-Agent System is designed to address this gap by providing an AI-driven solution capable of extracting, organizing, and simplifying complex medical information into a unified, patient-friendly overview. This system supports independence, enhances comprehension, and compensates for the shrinking availability of traditional caregiving networks—offering a timely and technologically feasible response to one of the most pressing challenges of an aging population.

## Citations

https://en.wikipedia.org/wiki/Baby_boomers

https://www.aarp.org/family-relationships/solo-aging

https://www.prb.org/resources/fact-sheet-trends-in-family-care-for-older-americans/

https://www.prb.org/resources/just-how-many-baby-boomers-are-there

https://www.prb.org/resources/aging-baby-boomers-to-face-caregiving-obesity-inequality-challenges

https://www.risehealth.org/insights-articles/historic-numbers-of-americans-live-by-themselves-as-they-age

https://longevity.stanford.edu/life-planning-in-the-age-of-longevity-insights-for-boomers

https://pmc.ncbi.nlm.nih.gov/articles/PMC11869104

https://www.aarp.org/pri/topics/ltss/family-caregiving/caregiving-in-the-us-2025

https://www.caregiver.org/resource/caregiver-statistics-demographics


