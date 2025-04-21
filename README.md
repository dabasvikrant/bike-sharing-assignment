# bike-sharing-assignment


A bike-sharing system provides bikes for short-term use, either for a fee or for free. In many bike-share programs, users can pick up a bike from a "dock," which is typically computer-controlled. To unlock the bike, the user enters their payment details, and the system grants access. Once finished, the bike can be returned to any other dock within the same network.



## General Information

The company aims to understand the factors influencing the demand for shared bikes in the American market. Specifically, they want to identify:
The key variables that significantly predict bike demand.

How accurately these variables explain the fluctuations in bike demand.


## Conclusions

-  The linear regression model was able to predict bike demand precisely with an R2 Score of more than 80%.

- Final Equation
```
cnt = yr*0.237132 + temp*0.388947 + windspeed*(-0.160217) + Jan*(-0.050699) + July*(-0.064112) + Oct*0.052266 + Sept*0.060748 + Sat*0.023058 + Cloudy*(-0.078506) + Light_snow_rain*(-0.290117) + spring*(-0.121727) + 0.297184 
```
