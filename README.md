# trial_gbd
Classifier of clinical trial records towards categories of diseases and injuries from the Global Burden of Diseases (GBD) 2010 study (Lozano et al. 2012, Lancet), based on the classification process described at:
[Atal I, Zeitoun JD, Névéol A, Ravaud P, Porcher R, Trinquart L. Automatic classification of registered clinical trials towards the Global Burden of Diseases taxonomy of diseases and injuries. BMC Bioinformatics (2016) 17:392](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-1247-7)

# Introduction
Here you will find codes to conduct the classification of clinical trial records downloaded either at the [WHO International Clinical Trials Registry Platform (ICTRP)](www.who.int/trialsearch/), either at [clinicaltrials.gov](https://clinicaltrials.gov/).
The classifier maps clinical trial records to either a 28- or a 171-class grouping of the GBD cause list.

The classifier is based on the Unified Medical Language System® (UMLS) knowledge source from the National Library of Medicine (NLM) (Bodenreider et al. 2004, Nucleic Acids Res). An interactive figure illustrating the methodological stages of the classifier is available [here](http://clinicalepidemio.fr/gbd_graph).

The use of the classifier needs the installation of MetaMap (Aronson et al. 2010, JAMIA), and in when needed the use of IntraMap (Fung et al. 2005, AMIA Annu Symp Proc), both developed at NLM based on the UMLS. Both programs request the user to sign to the UMLS license agreement.

An online interface to optimize manual classification of clinical trials records registered at the WHO ICTRP is available [here](http://www.clinicalepidemio.fr/gbd_study_who/).

# Instructions
To conduct the classification of clinical trial records, you must first follow the instructions from each script included in the folder "Preparing_data_for_classification". This includes codes to format for classification data as downloaded from WHO ICTRP or clinicaltrials.gov, and to update the classifier according to your data.
Then, you have to follow the instructions from the main script to conduct the classification.

# Further improvements
Adding stop conditions when data is not correctly formatted
Adding a folder with an example
