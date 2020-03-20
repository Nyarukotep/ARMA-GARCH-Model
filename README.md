# ARMA-GARCH-Model
A stock price prediction model based on ARMA and GARCH.
#
The combination of ARMA and GARCH could be used as a tool to predict stock
prices, which is better than AR and MA models.\
The ARMA-GARCH model used ARMA for the linear part and GARCH
for the residual part.\

$\begin{eqnarray} r_t & = & \mu + \epsilon_t + \theta\epsilon_{t-1} \\ \epsilon_t & = & \sigma_t e_t \\ \sigma^2_t & = & \omega + \alpha \epsilon_{t-1}^2 + \beta \sigma^2_{t-1} \end{eqnarray}$

## Prediction result

### AR model(Goldman Sachs):
<p align="center">
	<img src="https://github.com/Akiha-tohno/ARMA-GARCH-Model/blob/master/images/AR.png" width="800">
</p>

### MA model(Goldman Sachs):
<p align="center">
	<img src="https://github.com/Akiha-tohno/ARMA-GARCH-Model/blob/master/images/MA.png" width="800">
</p>

### ARMA model(Goldman Sachs):
<p align="center">
	<img src="https://github.com/Akiha-tohno/ARMA-GARCH-Model/blob/master/images/ARMA.png" width="800">
</p>

### ARMA-GARCH model(Goldman Sachs):
<p align="center">
	<img src="https://github.com/Akiha-tohno/ARMA-GARCH-Model/blob/master/images/ARMAGARCH_1.png" width="800">
</p>

### ARMA-GARCH model(General Motors):
<p align="center">
	<img src="https://github.com/Akiha-tohno/ARMA-GARCH-Model/blob/master/images/ARMAGARCH_2.png" width="800">
</p>

### ARMA-GARCH model(IBM):
<p align="center">
	<img src="https://github.com/Akiha-tohno/ARMA-GARCH-Model/blob/master/images/ARMAGARCH_3.png" width="800">
</p>

### ARMA-GARCH model(Microsoft):
<p align="center">
	<img src="https://github.com/Akiha-tohno/ARMA-GARCH-Model/blob/master/images/ARMAGARCH_4.png" width="800">
</p>

### ARMA-GARCH model(Tesla):
<p align="center">
	<img src="https://github.com/Akiha-tohno/ARMA-GARCH-Model/blob/master/images/ARMAGARCH_5.png" width="800">
</p>
