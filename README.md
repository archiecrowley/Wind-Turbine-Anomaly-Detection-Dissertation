# Machine Learning for Predictive Maintenance in Wind Turbines

Final-year dissertation, Nottingham Trent University (2026), First Class.

This project investigates whether machine learning can detect wind turbine faults from SCADA sensor data across multiple fault types and wind farms, using the public Care to Compare dataset. Traditional classifiers (KNN, Random Forest, One-Class SVM) peaked at 41-61% accuracy, traced to file-level labelling where most rows in fault files were actually normal operation. Reframing detection as sustained deviation over time, with a KNN model trained only on healthy data, achieved 86-91% accuracy on Farm A and 87% when the same methodology was retrained on Farm B, while keeping the original sensor variables so that anomalies stay physically interpretable.

Libraries and Tech Used: Python · scikit-learn · pandas · NumPy · SciPy · matplotlib · seaborn · Jupyter
