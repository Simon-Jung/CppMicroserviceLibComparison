# CppMicroserviceLibComparison

This repositories tries to do some comparison regarding different microservice libraries for C++.
Most of the chosen libs come from this listing https://github.com/mfornos/awesome-microservices

In order to do the comparison a simple calculator shall be implemented with each library.
Here several things can be tested:
- Propagate an error to the caller when dividing by 0
- Comparing the complexity of the code and the effort to setup
- Measuring performance

Furthermore there should be tests for more complex yet important criteria for microservices like
- Individual scalability
- Incremental updates of microservices on their own / individual deployment
- Compensation of failure of a service
- The complexity of integration testing

This list may be added to or changed anytime
