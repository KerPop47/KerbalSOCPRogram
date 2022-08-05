Design:
This project aims to add a SOC-like experience to KSP. To do so involves 2-3 domains:

1. Server:
    a. runs KSP and sends relevant information to a webserver to be rendered by the Ops UI
    b. takes commands posted to it from the Operators and converts it into commands for KSP
2. Ops UI: in-browser, provided by server
    a. renders the information provided by the server for the Operators
        i. orbital propagation
        ii. contact times
        iii. upcoming maneuvers
        iv. sat stats
    b. provides an interface for them to build commands to the spacecraft
        i. upload contact schedule
        ii. upload preplanned commands
        iii. initiate piloting mode
        iv. kOs terminal
    c. posts commands to the Server
    d. auto mode?
        i. generate station-keeping maneuvers, etc.
    e. direct command mode
        i. ie for piloting + driving
3. In-game mod:
    a. modifies the operations of the world:
        i. change location of ground stations
    b. modifies physics:
        i. non-spherical effects (j2, j4, etc)
        ii. 3rd-body effects
        iii. photon pressure effects
        iv. drag effects
    c. provides extra information from game if needed
