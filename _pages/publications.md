---
layout: page
title: "Publications"
permalink: /publications/
---

You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.

{% assign pubs = site.data.publications | sort: "date" | reverse %}
{% for p in pubs %}
  {% include pub_entry.html pub=p %}
{% endfor %}

<!---
 - Implementation and adherence to regular asymptomatic testing in a COVID-19 vaccine trial \
   LR Williams et al. \
   *Vaccine* (2024)
 - Multi-omics analysis reveals COVID-19 vaccine induced attenuation of inflammatory responses during breakthrough disease \
   RE Drury et al. \
   *Nature Communications* (2024)
 - Improved estimates of COVID-19 correlates of protection, antibody decay and vaccine efficacy waning: a joint modelling approach \
   DJ Phillips, MD Christodoulou, S Feng, AJ Pollard, M Voysey, D Steinsaltz. \
   *Preprint* (2024)
 - Efficacy of ChAdOx1 nCoV-19 (AZD1222) vaccine against SARS-CoV-2 lineages circulating in Brazil \
   SAC Clemens et al. \
   *Nature Communications* (2021)
 - Correlates of protection against symptomatic and asymptomatic SARS-CoV-2 infection \
   S Feng et al. \
   *Nature Medicine* (2021)
 - Efficacy of ChAdOx1 nCoV-19 (AZD1222) vaccine against SARS-CoV-2 variant of concern 202012/01 (B.1.1.7): an exploratory analysis of a randomised controlled trial \
   KRW Emary et al. \
   *The Lancet* (2021)
 - Single-dose administration and the influence of the timing of the booster dose on immunogenicity and efficacy of ChAdOx1 nCoV-19 (AZD1222) vaccine: a pooled analysis of four randomised trials \
   M Voysey et al. \
   *The Lancet* (2021)
 - T cell and antibody responses induced by a single dose of ChAdOx1 nCoV-19 (AZD1222) vaccine in a phase 1/2 clinical trial \
   KJ Ewer et al. \
   *Nature Medicine* (2021)
 - Phase 1/2 trial of SARS-CoV-2 vaccine ChAdOx1 nCoV-19 with a booster dose induces multifunctional antibody responses \
   JR Barrett et al. \
   *Nature Medicine* (2021)
 - Safety and efficacy of the ChAdOx1 nCoV-19 vaccine (AZD1222) against SARS-CoV-2: an interim analysis of four randomised controlled trials in Brazil, South Africa, and the UK \
   M Voysey et al. \
   *The Lancet* (2021)
 - Safety and immunogenicity of ChAdOx1 nCoV-19 vaccine administered in a prime-boost regimen in young and old adults (COV002): a single-blind, randomised, controlled, phase 2/3 trial \
   MN Ramasamy et al. \
   *The Lancet* (2021)
-->

