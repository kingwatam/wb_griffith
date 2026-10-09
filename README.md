# Consulting with The World Bank & Griffith University (2022-2026)

Documentation from work carried out remotely for Griffith University and The World Bank across two engagements. The first ran from late 2022 and continued through 2024, and the second covered late 2025 to 2026. The work modelled the health consequences of health tax policy, mainly sugar-sweetened beverage taxation, using Global Burden of Disease estimates and DisMod II to translate policy scenarios into projected disease burden, deaths and healthcare costs.

## At a glance

- **Institutions:** Griffith University and The World Bank
- **Countries and regions:** Egypt, Nigeria, Indonesia, Mongolia, India, Australia, Estonia, Kyrgyzstan, and 48 sub-Saharan African countries
- **Workflow:** GBD data extraction, DisMod II disease modelling with output verification, BMI distribution fitting, and proportional multi-state life table modelling in Excel
- **Analysis:** Tax scenario comparison across rates, with uncertainty intervals from Monte Carlo sampling
- **Tools:** R for extraction and distribution fitting, DisMod II for disease modelling, Excel for life table workbooks, Ersatz for Monte Carlo simulation
- **Outputs:** Country output sheets, technical appendices, presentation slides, manuscript drafts and a peer-reviewed publication

## Egypt, Nigeria, Indonesia and Mongolia

The first engagement opened with Egypt in late 2022, where GBD 2019 estimates for the country were pulled, entered into DisMod II and checked before transfer into an Excel life table. Nigeria, Indonesia and Mongolia followed through the first half of 2023 and into 2024 using the same sequence. Tax scenarios were compared across a range of rates, with uncertainty intervals from Monte Carlo sampling.

Each country produced a technical appendix and a set of output tables. The Egypt analysis was carried through to a peer-reviewed publication.

## Australia and India

Alongside the beverage tax work, a parallel line covered alcohol tax interventions in Australia and salt tax interventions in India during early 2023. The same GBD extraction and DisMod II sequence was used, and the resulting disease burden outputs supplied the input data for cost-effectiveness and simulation models built by other members of the team. The Australian component drew on GBD 2009 as well as GBD 2019.

## Sub-Saharan Africa

From July to December 2023 the focus shifted to 48 sub-Saharan African countries, principally in Central, Southern and West Africa.

The bottleneck in earlier country work had been the manual repetition of GBD extraction and DisMod setup for each country in turn. That was consolidated into a single script handling extraction across all 48 countries, and the full preprocessing pipeline was completed in 21 hours. DisMod outputs were produced for every country in the set and checked against the source data before being released for modelling.

## Estonia

Estonia was worked through between February and July 2024. The GBD 2019 extraction and DisMod build followed the same workflow as the earlier countries, with a second round of output checking and workbook updates in mid-2024. This work extended beyond the original engagement period.

## Kyrgyzstan and Australia

The second engagement began with Kyrgyzstan in October 2025. GBD 2023 replaced GBD 2019 as the data vintage, so the extraction scripts were updated, the DisMod II models were rebuilt and the Excel tables were regenerated. The whole sequence was completed in roughly four weeks, and BMI distributions were fitted alongside the disease models.

Australia followed in 2026 under the same procedure, with an additional Australian Type 2 Diabetes Risk Calculator classification carried through the modelling. The DisMod work was finalised in April 2026.

## Presentation

- **Online symposium, 2023:** Walked the World Bank and Griffith University teams through the standardised preprocessing pipeline built for the 48-country exercise, covering GBD extraction, DisMod II output generation and verification, and how the consolidated approach reduced the manual repetition that had constrained earlier country work.

## Related publication

Dalugoda Y, Tam KW, Mandeville KL, El-Saharty S, Hamza MM, Veerman JL. The potential health effects of taxing sugar-sweetened drinks in Egypt: An epidemiologic-economic modelling study. *Public Health in Practice*. 2026;11:100786. https://doi.org/10.1016/j.puhip.2026.100786