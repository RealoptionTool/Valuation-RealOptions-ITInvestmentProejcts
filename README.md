# ITprojectevaluationtool
The [IT project evaluation tool](https://personal-2u8rb8tg.outsystemscloud.com/ITInvestmentprojectEvaluation/Login) estimates the value of strategic growth options for IT investment projects (ITIPs). The tool is based on modified assumptions of the typical Black-Scholes Model (BSM) which are derived in [Müller et al. (2016): Decision Support for IT Investment Projects](https://link.springer.com/article/10.1007/s12599-016-0423-7). In the evaluation tool, all inflows and outflows follow either a geometric Brownian motion (GBM) or an exponential mean reversion (EMR). Also, each in- and outflow can be subjected to unforeseeable events (referred to as jumps in the valuation of the respective in- or outflow) that may affect the value of the strategic growth option. These "shocks" are modelled using a lognormally distributed random variable. The evaluation tool considers a complete market, which implies that all risk subjected to the strategic growth option is hedgeable. Further, the tool assumes the option runtime to be uncertain but fixed by a lower bound. This means that while the tool accounts for events that can increase the runtime of the strategic growth option, there are no events that lead to the IT investment project being completed before initially planned.  

To use the tool, users can log in the public account "Andrea McKenzie" or register and use an own account, to only see options for ITIPs that have been created by them. After the log in, users can either calculate the option value of new ITIPs or calculate the value for an existing option for an ITIP that has already been created. When creating a new strategic growth option for an IITP that should be calcualted, one has to provide the tool with a name, the risk-free interest rate which should be used for calculation and the minimum option runtime. If the option runtime is uncertain, users are forwarded to determine risk scenarios that can increase the option runtime. Afterwards, users have to provide the tool with all cash in- or outflows that are subjected to the ITIPs. For each in- and outflow that is subjected to uncertainties one has to determine whether the cash flow can increase limitlessly and whether unpredictable events can impact the value of the cash flow. This determines whether the cash flow follows GMB or GMR and whether jumps should be modelled or not. After providing the system with some characteristics on the cash flows, the expected option value is simulated based on 100,000 iterations. The tool returns the expected option value, the return on investment as well as the 95% confidence interval for the estimation. 
