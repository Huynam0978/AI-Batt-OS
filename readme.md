-Batt-OS: Autonomous Identification of Battery Life Models (Open-Source)

Open source implementation of some of the methods utilized by AI-Batt, a battery lifetime modeling and analysis toolkit provided by NREL.

This software demonstrates the use of bi-level optimization and symbolic regression techniques to semi-autonomously identify algebraic models predicting the capacity fade of lithium-ion batteries during calendar aging. Modeling the degradation of batteries is a complex task, due to the difficulty in separating the time-dependent and time-independent factors impacting cell level degradation, across multiple data series with different numbers of measurements and/or data quality. Bi-level optimization enables model parameters to be optimized to either the entire data set or to individual data series, allowing statistical disambiguation of global behaviors (data series independent) and local behaviors (data series dependent). Symbolic regression is used to automatically search for optimal low-dimesional models predicting the variation of locally optimized parameters versus time-independent experimental variables from millions of possible models, resulting in a more accurate and repeatable model identification process than is possible by a manual search. The provided tools also implement cross-validation and bootstrap resampling schemes, empowering statistical model comparison/selection and quantification of model uncertainties. 
An example script replicates the results from the manuscript "Challenging Practices of Algebraic Battery Life Models through Statistical Validation and Model Identification via Machine-Learning", submitted to ECS. 

All code is written in MATLAB. Requires the Statistics and Machine Learning Toolbox.

Contact Dr. Paul Gasper at Paul.Gasper@nrel.gov for any questions.
