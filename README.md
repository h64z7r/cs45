java c
Climate Change Economics
Undergraduate Assignment 3
Overview
This assignment has two parts: 1) you will extend the Excel model you started in previous assignments to include a component that computes emissions and 2) decompose the major drivers of future emissions using your model.
Part I: Modeling
Overview
You will add a component that computes anthropogenic CO2 emissions over time to your model.
The output of the emissions component will replace the forcing for the carbon cycle component you build last week, i.e. instead of using a forcing provided by me for emissions, you will couple the carbon cycle component to the emissions component.
The new component will rely on various forcings, and those are provided to you in the Excel file “CCE – Assignment 3 – Forcings.xlsx.”
This week’s assignment will have less detailed descriptions of what to do and more things for you to figure out yourself. If you are stuck at any point, please ask the GSIs for help!
Emissions model
The emissions component starts out with the Kaya identity:

EtKAYA are industrial CO2 emissions in Mt C at time t, Pt is population at time GDP t, Yt is output (or GDPor income) at time t and Energyt is energy use in EJ (exajoule) at time t.
I will provide you with forcings for all components of the Kaya identity. But, the forcings are not provided in a way that you can input into equation (1) straight away. There are two issues you need to be careful about: a) units and b) levels vs. growth rates.
The forcing for population is provided as the initial level for 2015, and then yearly growth rates of population for all future years. The initial population level for 2015 is 7340 million people. Growth  rates are given in the usual format, i.e. a value of 0.1 corresponds to 10%, 0.01 is 1% and 1.0 is 100%.
The initial level of per capita income in 2015 is 10.2 thousand dollars per capita, for later years you need to compute the levels yourself from the yearly growth rate of per capita income that is provided as a forcing.
The initial level of energy intensity for the year 2015 is 7.69 EJ per trillion $ of output. Careful with units at this poin代 写Climate Change Economics Undergraduate Assignment 3
代做程序编程语言t, you will have to adjust the Kaya identity a bit to make units match. For years later than 2015, I provide you with yearly growth rates of energy intensity which allows you to compute energy intensity levels for future years.
The initial level of carbon intensity is 16.84 Mt C per EJ of energy for the year 2015. You need to use the growth rate of emission intensity provided to you as a forcing to compute the carbon intensity for future years.
At this point we have computed emissions from industrial activities, assuming no specific climate policy is implemented. There is a second source of anthropogenic CO2 emissions that we are not going to model explicitly, but instead include as another forcing: Land use emissions (ELt), which are provided to you as a forcing in Mt C. This category mostly covers extra emissions caused by deforestation. Total business as usual (BAU) emissions are therefore given as:

Coupling
The last step is to couple the carbon cycle component with the emissions component; instead of using a forcing for the carbon cycle, you now use the emissions computed in the emissions component.
Part II: Policy Analysis
Question 1: Decompose the main drivers of climate change in the scenario used in the model and rank their relative contribution to future climate change.
First create four copies of the model, so that altogether you now have five copies of the model. Each copy of the model should be a separate Excel sheet in the same Excel file.
Now change each of the four copies such that one of the Kaya identity factors is kept constant at 2015 levels in a sheet. This amounts to assuming that e.g. population stays constant, or per capita output stays constant, etc.
Finally, create another empty sheet and add a graph that plots world average temperature above pre-industrial levels over time for each of the five cases: BAU, population constant, per capita output constant, energy intensity constant and emission intensity constant.
Briefly describe the effect each of these has on average temperatures and rank them in terms of the size of their effect.







         
加QQ：99515681  WX：codinghelp
