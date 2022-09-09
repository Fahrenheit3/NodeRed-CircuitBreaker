# NodeRed-CircuitBreaker
One of my Node-Red subflows for Google Summer of Code. (Circuit Breaker pattern implemented...)

DESCRIPTION: 
This subflow checks the technical fail percentage of a flow. At its optimum use the flow has a function which counts every fail and success. The subflow takes these numbers every 15 seconds and calculates if the fail percentage threshold is exceeded. If yes the flow is stopped for some time(which is chosen by user) to cooldown. After that time ends the subflow gives the flow a go and then the cycle begins again.

(FOR A DETAILED DESCRIPTION PLEASE VISIT MY NODE-RED PAGE)
