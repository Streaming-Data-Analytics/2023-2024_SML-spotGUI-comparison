# Hyper-parameter Tuning in Streaming Machine Learning Using the spotGUI Library

Optional project of the [Streaming Data Analytics](http://emanueledellavalle.org/teaching/streaming-data-analytics-2023-24/) course provided by [Politecnico di Milano](https://www11.ceda.polimi.it/schedaincarico/schedaincarico/controller/scheda_pubblica/SchedaPublic.do?&evn_default=evento&c_classe=811164&polij_device_category=DESKTOP&__pj0=0&__pj1=d563c55e73c3035baf5b0bab2dda086b).

Student: **Nicolò Francesco Resmini**

The project will use the Python library spotGUI ([paper](https://arxiv.org/pdf/2402.11594.pdf), [code](https://github.com/sequential-parameter-optimization/spotGUI/tree/main)) to test the hyper-parameter tuning in SML. The aim is to use the tool to find the best model with the best hyper-parameters values over time on two standard benchmarks.

The task consists in replicating the notebook 3 and 4 of the SML class applying the new spotGUI hyper-parameter tool. More in practice, for the NEWeather and Agrawal datasets, you have to find the best model with the best hyper-parameters values among Naïve Bayes, KNN, HT, HAT, ARF, Online Bagging, Leveraging Bagging, ARF, SRP.

You should use the same metrics used in the notebooks to make the results comparable:
- Accuracy, Balanced Accuracy, Geometric Mean, and CohenKappa for NEWeather dataset, and
- Accuracy, Balanced Accuracy, Geometric Mean, and CohenKappa with a Rolling window having size=50 for Agrawal dataset.

Moreover, you should keep track of the Time, CPU and RAM usage to test and train the models. The project must also include some plots to better show the results.

For each dataset, you are required to create a single .ipynb file. You must include comments for the principal instructions, and you are allowed to import external py modules. Additionally, ensure you thoroughly comment on the comparison results using various plots associated with the different metrics. Finally, again, within each .ipynb file, briefly discuss the conclusions that can be drawn from the experiment.

## Note for Students

* Clone the created repository offline;
* Add your name and surname into the Readme file;
* Make any changes to your repository, according to the specific assignment;
* Add a `requirement.txt` file for code reproducibility and instructions on how to replicate the results;
* Commit your changes to your local repository;
* Push your changes to your online repository.
