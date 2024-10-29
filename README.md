In this project I built stochastic model based on cellular Cellular automaton to study spread of plague using SIR model.

The SIR model is a type of compartmental model used in epidemiology to describe the spread of infectious diseases. This model helps in understanding the dynamics of disease outbreaks and the impact of interventions like vaccination and social distancing

SIR_modeling_GUI.py will start a GUI that shows an aXb matrix with S amount of healthy cells (blue), I amount of sick cells (red), and R amount of immune cells (green). 
All the parameters can be changed by the user.

The GUI will be opened and with a scroll of the mouse will, generation will strat running, meaning each populated cell can move to any of the direction with wrap around model.

If a sick cell is near a healthy cell it can infect it with X probebilty. After some generations, a sick cell becomes immuned.
The sum of each state is printed on the screen:
![image](https://github.com/user-attachments/assets/40fc5f98-3fd3-4c08-9c94-d7ed4c02f1bd)


SIR_modeling_write_to_file.py will run in the background (without GUI) and perform 5 repeats for more reliable results. The results will be saved in an excel file for further research.
