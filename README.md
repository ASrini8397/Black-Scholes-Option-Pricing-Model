# Black-Scholes-Option-Pricing-Model
Implementing the Black-Scholes Option Pricing Model to price an American Call Option on GOOGL stock expiring July 15th (the day of the 20-1 Stock Split)

The implied Volatility was calculated by reverse engineering the Black-Scholes Formula using the current market price from yahoo finance of 
C0 (Call Option Price) and a basic assumption of Sigma (implied volatility), which resulted in the actual implied volatility.
<img width="1201" alt="Screenshot 2022-05-23 at 13 05 10" src="https://user-images.githubusercontent.com/98121213/169897459-c78ab2ae-fd14-4eb3-93b0-602f3d2ac2a4.png">

After implementing the Black-Scholes Model, the delta, gamma, theta, vega, and rho values were calculated and compared against the calculations from a
library called py-volllib (The check is the value on the right side of the tuple and my calculated values are on the left)
<img width="719" alt="Screenshot 2022-05-23 at 13 15 54" src="https://user-images.githubusercontent.com/98121213/169898985-a7a3a955-f033-440c-9431-f517be57e0eb.png">
