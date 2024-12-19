# HomeWork 3: Secure memory


-  A) What were you able to get working and why do you think that you couldn't get the final objective?
    - I implemented the basic secure memory and added extra functions. The code compiled but didn't run. I spent too much time on the base model and lacked context and time to fully understand the implementation.
-  B) Describe the experiment that you would run if everything was working.
    - If everything worked, I would compare the base secure memory to an enhanced version with metadata caching using a traffic generator. The goal would be to evaluate memory requests and execution time.
- C) Run some applications (getting started suite works, or matrix multiply) using the baseline and discuss
     the impact that you believe the secure memory changes will have.
    - Running the workload suite from Homework 2 with secure memory would likely reduce performance due to frequent memory access. A metadata cache could mitigate this but wouldn’t eliminate the overhead.
