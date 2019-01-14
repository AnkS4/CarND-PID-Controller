# CarND-PID-Controller

## Implementation of PID algorithm

### Choosing hyperparameters
I manually tuned the PID coefficients, starting each with 0.

At the end, the hyperparameters Kp_ = -0.15, Ki_ = 0, Kd_ = -2 worked well for the project.

## The effect of the P, I, D component of the PID algorithm

* The P component tries to make the vehicle turn towards the intended path in proportion to the CTE.
* The D component tries to avoid the overshoot by noticing the reduced error.
* The I component tries to adjust the bias created by the vehicle.
