# Initial testing

## Running on the simulator.
1. [Clone](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone), compile and run the [simulator](https://github.com/TTK4145/Simulator-v2).
2. Run the `test.sh` script from [the c client](https://github.com/TTK4145/driver-c) to verify that the simulator is working properly.
3. The simulated elevator should now move between the top and bottom floor.

## Running on the actual elevator.
1. Start the [elevator server](https://github.com/TTK4145/elevator-server) by calling `elevator_server` on one of the computers on the real time lab.
2. Run the `test.sh` script now and verify that you get the same behaviour on the hardware as you had on the simulated elevator.

## Tips & Tricks
 - If an `elevator_server` is already running the new server will not be able to bind to the socket. If you need to kill it, you can do so by calling `pkill elevator_server`.
