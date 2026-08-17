# Climate Anomalies as a Factor in Changing Public Attitudes Toward Global Warming

This repository contains the Python source code used in the coursework  
**"Climate Anomalies as a Factor in Changing Public Attitudes Toward Global Warming"**.

The code is designed for the collection, preprocessing, and spatiotemporal analysis of social media data and climate anomalies. The main objective is to assess how the frequency of climate anomalies influences public attitudes toward global warming.

---

## Abstract

Global warming is one of the major challenges facing humanity in the 21st century. According to the report “Climate Change 2022: Impacts, Adaptation and Vulnerability” by the Intergovernmental Panel on Climate Change (IPCC), the Earth could warm by 1.5 °C between 2021 and 2040 under a moderate scenario (IPCC, 2022). Climate change is being felt around the world, manifesting itself, among other things, in an increase in the frequency of extreme weather events and anomalies that are noticeable to everyone. The economic damage from global warming will only increase in the coming years and, according to researchers, could reach $38 trillion per year (Kotz M., 2024).

To mitigate the effects of global warming, policies that are supported by the public are needed (Bernauer T., 2013). However, society still has differing attitudes toward the problem of global warming. Some people do not believe that global warming exists or deny its anthropogenic nature (Johnson D., 2009). Therefore, it is important to understand what determines and how people's attitudes toward climate change change.

Public attitudes toward global warming are influenced by many factors, both individual and socioeconomic (Hornsey M. J., Lewandowsky S., 2022). One such factor is personal experience with climate anomalies (Zanocco C. et al., 2018). However, its influence is not always detectable in big data (Effrosynidis D., Sylaios G., Arampatzis A., 2022) and may manifest differently depending on the regional context (Hamilton L. C., Keim B. D., 2009).

This work helps to understand the extent to which public opinion on climate change depends on the severity of climate anomalies in different regions of the United States, based on social media data.

**Research object:** public perception of climate change.  
**Research subject:** the dependence of public attitudes toward global warming on climate anomalies.

**Research question:**  
How does the frequency of climate anomalies affect people's attitudes toward global warming?

**Hypothesis:**  
The higher the frequency of climate anomalies, the more people believe that global warming exists and has an anthropogenic character.

---

## Goal and Objectives

**Goal:** to determine the degree and direction of the influence of climate anomalies on public attitudes toward global warming based on big social media data.

**Objectives:**
1. Study the factors influencing people's attitudes toward global warming.
2. Collect and study information on climate anomalies.
3. Study the available data on social media posts about global warming.
4. Study spatial analysis methods applied to social media data and climate anomalies.
5. Analyze spatial patterns between the frequency of climate anomalies and people's attitudes toward global warming.

---

## Data

### 1. Twitter Climate Change Dataset
- **Source:** Effrosynidis D. et al., 2022.
- **Description:** a dataset of Twitter (now X) posts devoted to global warming and climate change.
- **Usage:** extracting text messages, determining sentiment/attitude of authors toward global warming, geolocating posts.

### 2. nClimGrid-Daily
- **Source:** Durre I., 2022.
- **Description:** daily climate data on a regular grid for the United States.
- **Usage:** calculating climate anomalies, frequency of extreme weather events, building climate indicators by region.

---

## Repository Structure
