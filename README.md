Dataset Source – OpenDataSus - Registros de Vacinação Covid19 - Dados SC – Santa Catarina – Brasil (1)

Dataset downloaded on 04 Aug 2021 at 10:00 am.

Inicial master File named – sc040821_10am.csv (1)

Original total file size – 2.6 GB = 34 columns and 4.854.329 rows (or registrations)

The above master file was divided in 17 separated files. Each grouping all the registered data from the counties belonging to a DECENTRALIZED EPIDEMIOLOGICAL SURVEILLANCE UNITS (UDVE) in the state of Santa Catarina- Brasil.

# Introduction:

Per Alura Bootacamp Applied Data Sciences II plan, there was no project to be delivered for the Module 4.

Therefore this project was created as my personal bonus for Module 4 (out 6) of this Alura bootcamp.

It is a continuation and extension of the exploratory work I already done for the first 3 modules of this bootcamp, when I reviewed the OpenDataSus registers of covid19 vaccination in the Brazilian State of Santa Catarina(SC) up to 02 July 2021. The documentation of work done on the previous 3 modules can be find in the followint github links:

https://github.com/amf60/Vac_Covid19_BR_SC_Combinations_of_Concern_1
https://github.com/amf60/Vac_Covid19_BR_SC_Combinations_of_Concern_2
https://github.com/amf60/Vac_Covid19_BR_SC_Combinations_of_Concern_3

# My objectives for this module

My objectives for this personal Module 4 project are:

* to keep using only Google Colab notebook and Python related packages, to check the OpenDataSus registration;
* verify if the 12 % trend of 'Combinations of Concern' is still a matter for concern at end of July 2021.

# Brief Comments and conclusions:

DE-EXCELED !!! - With the help of the Alura Bootcamp DS II, Aluras courses Programming with Python, Python for DataSciences, services as stackoverflow, medium and others, I accomplished my objective to deliver this module project entirely within one Google Colab notebook (Combinations of Concern - sc04082021_10am.ipynb) using Python related packages. This notebook is also stored in My Drive > Alura DS Bootcamp > Combinations of Concern > Vac_C19_CoC_4_M4_AluraDSB_sc040821_10am

We notice that, in Santa Catarina, on 31 JUL 21, a small reduction (from 12% to 10%(467.103 (CoC_1 + CoC_3) out of a total of 4.854.329 registrations)) on the previous the overall trend of 12% registrations of covid_19 vaccinations with 'Combinations of Concern'.

UDVE 13 alone clusters 82% of the state total of 'Combinations of Concern' (398.908 out of 467.103). It seems a significant increase as end of June this % was 62%

"'No_issue'" - as already mentioned, from the pharmacovigilance point of view, is not totally correct, as I noticed some other 'combinations of worrying' (to distinguish of the definition of 'CoC'). So I may tackle 'combinations of worrying' in the projects of the next two modules of this bootcamp.

Finally, as explained, I am tailoring all the above with the end_user in mind: the SC UDVE manager and local teams at the each 'vaccination center'. Therefore, at the end of this bootcamp we may use the material above to easily identify and isolate all the registrations with 'combinations of concern' for appreciation at several levels - UDVE, county, vaccination center, etc. More about how that can be done in a sensitive way with efficiente Risk Based Monitoring techniques I use in clinical trials may be presented in the next two modules.
