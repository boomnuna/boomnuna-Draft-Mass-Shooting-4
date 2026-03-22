# US Mass Shootings: 60 Years of a Growing Crisis

> *"Mass shootings are a uniquely American problem."*

---

## 📌 Introduction

> **On average, a mass shooting occurs every 86 days in the United States. In the past decade (2015–2025), that number has accelerated to once every 34 days.**

This project explores patterns, trends, and insights from a cleaned dataset of **254 US mass shootings** spanning 1966–2026, sourced from [Mother Jones](https://www.motherjones.com/politics/2012/12/mass-shootings-mother-jones-full-data/) and [The Violence Project](https://www.theviolenceproject.org/).

The goal is to understand how incidents have evolved over time, where they occur, how severe they are, and who is behind them.

---

## 📈 Incident Trends: 1966–2026

![Incidents Over Time](images/num_incident_over_time.png)

<p align="center"><em>Fig 1: Number of mass shooting incidents per year — frequency rises sharply after 2010.</em></p>

**Why after 2010?**
Before 2010 the US averaged **2.7 incidents/year**. After 2010 that jumped to **8.4 incidents/year** — a 3× increase. Several factors converge around this period: the rise of **24/7 social media** gave perpetrators a platform for infamy and enabled copycat behavior; **24-hour news cycles** amplified each incident far beyond what previous generations experienced; the **expiry of the Federal Assault Weapons Ban in 2004** gradually widened access to high-capacity firearms; and growing research points to a **contagion effect**, where a high-profile shooting measurably increases the probability of another within days. None of these factors alone explains the shift — together they created the conditions for the acceleration we see in the data.

---

![Victims Over Time](images/num_victim_overtime.png)

<p align="center"><em>Fig 2a: Total fatalities and injuries per year — 2017 stands out as the deadliest year, driven by the Las Vegas Massacre.</em></p>

![Victims Over Time No Las Vegas](images/num_victim_overtime_no_lv.png)

<p align="center"><em>Fig 2b: Same chart with the Las Vegas Massacre removed — revealing the underlying trend without the extreme outlier.</em></p>

**Why does 2017 spike so dramatically?**
The Las Vegas Strip Massacre on October 1, 2017 is a singular statistical outlier — a single gunman firing from a hotel window into a crowd of 22,000 caused **60 deaths and 546 injuries**. Without it, 2017's injury count drops from 692 to just 146. Fig 2b shows what the trend actually looks like: a steady, sustained rise in both fatalities and injuries, without one event dominating the picture. The key takeaway is that **2017 is not an anomaly in intent — it is an anomaly in scale**. The underlying trajectory was already worsening before Las Vegas.

Between 1966 and 2026, the US recorded **254 mass shooting incidents**, resulting in **1,680 fatalities** and **2,060 injuries** — totaling over **3,700 victims**.

- 📅 **Peak frequency year: 2018** — 15 incidents recorded
- 💀 **Deadliest year: 2017** — 132 fatalities
- 🔺 Rate increased from **2.7/yr** (pre-2010) to **8.4/yr** (post-2010)

---

## 🏆 Top 10 Deadliest Incidents

![Top 10 Most Victims](images/top10_most_victim_incident.png)

<p align="center"><em>Fig 3: The 10 incidents with the highest total victims — average of 26 killed and 87 injured per incident. Las Vegas 2017 dwarfs all others at 606 total victims.</em></p>

**Why are these incidents so much more deadly?**
The top 10 share common traits: **outdoor or large-venue settings** (concert, nightclub, parade), **semi-automatic rifles** with high-capacity magazines, and in several cases **tactical preparation**. The average fatality count in the top 10 is **26 killed** vs **6 killed** in the dataset overall — a 4× multiplier. This gap is largely explained by weapon type: incidents involving rifles produce significantly higher casualty counts than handgun-only incidents because of rate of fire and magazine capacity.

| Rank | Incident | Year | Killed | Injured | Total |
|------|----------|------|--------|---------|-------|
| 1 | Las Vegas Strip Massacre | 2017 | 60 | 546 | **606** |
| 2 | Orlando Nightclub Massacre | 2016 | 49 | 53 | **102** |
| 3 | Aurora Theater Shooting | 2012 | 12 | 70 | **82** |
| 4 | Virginia Tech Massacre | 2007 | 32 | 23 | **55** |
| 5 | Highland Park July 4 Shooting | 2022 | 7 | 46 | **53** |

> **Avg across top 10:** ~26 killed · ~87 injured · ~113 total victims per incident

---

## 🗺️ State & Geography

![Incidents Per State](images/num_incident_per_state.png)

<p align="center"><em>Fig 4: California leads with 37 incidents, followed by Texas (25) and Florida (16). The dashed line shows the national average of 5.6 incidents per state.</em></p>

**Why do California, Texas, and Florida dominate?**
The simplest explanation is **population size** — these are the three most populous states in the US. More people means more workplaces, schools, public venues, and therefore more potential sites for incidents. California and Texas also have **large urban centers** where economic inequality, crowding, and stress are concentrated. It is important to note that this chart shows *raw counts*, not per-capita rates — a per-capita analysis would likely produce a different ranking, with smaller states like Nevada and Colorado ranking higher relative to their population size.

| State | Incidents | Fatalities |
|-------|-----------|------------|
| **California** | 37 | 232 |
| **Texas** | 25 | 228 |
| **Florida** | 16 | 142 |
| New York | 13 | 76 |
| Pennsylvania | 13 | 64 |

---

## 📍 Place & Location

![Top 10 Places](images/top10_most_place.png)

<p align="center"><em>Fig 5: Workplace is the most common setting (57 incidents), followed by schools (31). "Other" category excluded for clarity.</em></p>

**Why are workplaces and schools the most targeted?**
**Workplaces** top the list because they concentrate a specific set of risk factors: interpersonal conflict, financial stress, grievances about termination or demotion, and easy familiarity with the layout. Many workplace shootings are preceded by a dismissal or demotion. **Schools** are alarming for a different reason — they are perceived as **soft targets** with predictable schedules and limited security, and school shootings receive disproportionate media coverage, which research links to copycat incidents. Notably, while schools rank 2nd in *frequency*, they rank higher in average *fatalities per incident* (9.1 killed/incident vs 6.0 for workplaces), suggesting that when school shootings happen, they tend to be more lethal.

| Location Type | Incidents | Avg Fatalities |
|---------------|-----------|----------------|
| **Workplace** | 57 | 6.0 |
| **School** | 31 | 9.1 |
| Outdoors | 18 | — |
| Retail | 18 | — |
| Restaurant/Bar | 17 | — |
| Religious | 14 | — |

---

## 🔫 Shooter Profile

![Race & Gender](images/shooter_race_and_gender.png)

<p align="center"><em>Fig 6: 97.6% of perpetrators are male (248 cases). White perpetrators make up 53.5% of cases, roughly proportional to their share of the US population.</em></p>

**Why are nearly all perpetrators male?**
This is one of the most consistent findings in mass shooting research worldwide. The leading explanations center on **socialized masculinity** — cultural scripts that link male identity to dominance, retaliation, and public display of power. When men experience humiliation, rejection, or failure, the mass shooting becomes — for a small number — a distorted act of reclaiming power. Female perpetrators are rare (6 cases, 2.4%) and tend to have distinct motivational profiles, often domestic in nature.

![Average Age of Shooter](images/average_age_of_shooter.png)

<p align="center"><em>Fig 7: Shooter age ranges from 11 to 72, with a mean of 34 years old. 11 perpetrators (4.3%) were under 18 — all involved school settings.</em></p>

**Why does the under-18 group matter?**
All 11 juvenile perpetrators committed their attacks **inside schools** — from Columbine (1999, age 17) to Apalachee High School (2024, age 14). Their average fatality count is **6.4 per incident**, higher than the dataset average of **6.6**, meaning juvenile shooters are not less lethal. This group is particularly important for policy: these individuals were still in school systems that had daily contact with them, suggesting that **early identification and intervention** could have intercepted some of these incidents.

---

## 🔧 Weapons Used

![Weapon Types](images/weapon_type.png)

<p align="center"><em>Fig 8: Handguns are the most used weapon (210 incidents), followed by rifles (149). Most perpetrators use more than one weapon type.</em></p>

**Why are handguns the most common weapon?**
Handguns are the most **accessible and concealable** firearm in the US — they can be legally purchased in most states with minimal background checks and are legal to carry concealed in many jurisdictions. However, it is rifles that drive the highest casualty counts: incidents involving rifles produce on average **4× more victims** than handgun-only incidents. The fact that both are prevalent reflects two different shooter profiles — opportunistic perpetrators typically use handguns they already own, while premeditated mass casualty attacks increasingly involve rifles.

![Weapons Obtained Legally](images/weapon_obtained_legally.png)

<p align="center"><em>Fig 9: 63.4% of perpetrators (161 cases) obtained their weapons through legal channels.</em></p>

**Why does legal acquisition dominate?**
This finding challenges the narrative that mass shooters are primarily obtaining weapons illegally. The majority legally purchased their firearms — meaning they **passed background checks**. This points to gaps in existing screening systems: the background check system does not account for most mental health records (which are rarely submitted to federal databases), does not include a waiting period in most states, and does not flag radicalization indicators. The 16.9% who obtained weapons illegally represent a smaller but still significant channel, often through straw purchases or theft.

| Weapon | Times Used |
|--------|------------|
| **Handgun** | 210 |
| **Rifle** | 149 |
| **Shotgun** | 49 |
| **Revolver** | 40 |
| **Knife** | 3 |

---

## 🧠 Motivation

![Motivation Behind Shooting](images/motivation_behide_shooting.png)

<p align="center"><em>Fig 10: Workplace/financial grievances and domestic conflicts are the two most clearly identifiable motives. "Other/Not Specified" excluded for clarity.</em></p>

**Why are workplace and domestic motivations the most common?**
These two categories share a common thread — **personal grievance against specific people** the perpetrator knows. Workplace shootings are frequently triggered by a termination, demotion, or perceived humiliation. Domestic shootings often escalate from intimate partner violence or custody disputes. Together they account for **116 incidents (45.7%)** of all cases with a known motive, reflecting that most mass shootings are not ideologically motivated — they are the endpoint of a personal crisis that went unaddressed.

![Mental Health Pie Chart](images/piechart_mental_health_issue.png)

<p align="center"><em>Fig 11: 69.7% of perpetrators (177 cases) showed prior signs of mental health issues before the incident.</em></p>

**What does "prior signs" actually mean?**
It is critical to note that **mental illness does not cause violence** — the vast majority of people with mental health conditions never harm anyone. What this finding shows is that in nearly 70% of cases, there were **observable warning signs** before the attack: documented psychiatric history, prior hospitalizations, threats made to others, or concerning behavior reported to schools or law enforcement. This is a finding about **missed intervention opportunities**, not a finding about dangerousness of mental illness in general.

| Motivation | Incidents |
|------------|-----------|
| **Workplace / Financial** | 60 |
| **Domestic / Relationship** | 56 |
| **Paranoia** | 42 |
| **Revenge / Anger** | 36 |
| **Hate / Racism** | 16 |
| **Terrorism / Ideology** | 9 |

---

## 💡 Suggestions & Policy Implications

Based on the patterns in this dataset, the following areas stand out as the most data-supported intervention points:

**1. Early Warning Systems**
69.7% of perpetrators showed prior mental health warning signs. Schools, workplaces, and healthcare providers need **structured threat assessment protocols** — not to stigmatize mental illness, but to connect at-risk individuals with support before crises escalate. The 11 juvenile perpetrators in this dataset all attended schools that had contact with them before the incident.

**2. Background Check Reform**
63.4% of perpetrators obtained weapons legally. Strengthening background checks to include mental health records, adding **universal background checks** for private sales, and introducing **waiting periods** could reduce access for individuals in acute crisis. The data does not support the claim that illegal procurement is the dominant route — legal purchase is.

**3. Red Flag / Extreme Risk Laws**
Many states now have Extreme Risk Protection Orders (ERPOs) that allow courts to temporarily remove firearms from individuals showing warning signs. Given that most perpetrators had **documented prior signs**, these laws — if consistently enforced — represent a direct evidence-based intervention.

**4. Workplace Intervention Programs**
With 57 incidents occurring in workplaces, **employee assistance programs (EAPs)**, de-escalation training for managers, and clear anonymous reporting channels for concerning behavior are practical, non-legislative measures that employers can implement immediately.

**5. Media Reporting Guidelines**
Research consistently shows a **contagion effect** — mass shootings cluster in time following high-profile incidents. Responsible media reporting that avoids naming perpetrators, showing their manifestos, or ranking incidents by body count may help reduce the copycat dynamic that partly explains the acceleration seen after 2010.

> *"The data does not point to a single cause. It points to a system of overlapping failures — in mental health, in gun access, in early intervention — each of which is fixable."*

---

## 📊 Summary

| Metric | Value |
|--------|-------|
| Total Incidents | **254** |
| Total Fatalities | **1,680** |
| Total Injured | **2,060** |
| Year Range | **1966–2026** |
| Avg rate before 2010 | **2.7 incidents/year** |
| Avg rate after 2010 | **8.4 incidents/year** |
| Most Incidents in a Year | **15 (2018)** |
| Deadliest Year | **2017 (132 killed)** |
| Most Common Perpetrator | **White Male, ~34 yrs old** |
| Under-18 Perpetrators | **11 cases (4.3%)** |
| Most Common Weapon | **Handgun (210 incidents)** |
| Most Common Location | **Workplace (57 incidents)** |
| Weapons Obtained Legally | **63.4%** |
| Prior Mental Health Signs | **69.7%** |

---

## 📂 Data Sources

- [Mother Jones — US Mass Shootings Database](https://www.motherjones.com/politics/2012/12/mass-shootings-mother-jones-full-data/)
- [The Violence Project Database](https://www.theviolenceproject.org/databases/)
- [Brady United — Gun Violence Statistics](https://www.bradyunited.org/fact-sheets)

---
