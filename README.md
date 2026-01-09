# cagr_calculator

CAGR Calculator is a small browser extension that helps calculate CAGR on investments through Fidelity, Schwab, and other brokerages.

The idea is smple:
- Each lot of stocks purchased (and not sold) get a CAGR calculated
- The CAGR's are then put under a weighted average.
- The result is an "effective CAGR" that shows the growth rate adjusting for compounding.

The goal of the tool is to provide a simple CAGR for typical buy and hold investments. Why? Because total gain/loss % is not accounting for the time value of money. This obfuscates the actual performance of buy and hold investments.
When securities are disposed of, this affects the CAGR as those lots sold will be now removed from the weighted average.
