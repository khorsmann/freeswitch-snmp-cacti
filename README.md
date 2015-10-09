# freeswitch-snmp-cacti


## Example picture

![Alt text](/freeswitch_graphs.png?raw=true "Example FreeSWITCH Cacti Graph")

## FreeSWITCH MIBs thats intressting

    .1: core
        .1.1: identity
            .1.3.6.1.4.1.27880.1.1.1: FreeSWITCH version string (eg. "1.0.head (git-0cf1d54 2011-01-19 16-36-04 -0500)")
            .1.3.6.1.4.1.27880.1.1.2: Core UUID as a string 
        .2: systemStats
            .1.3.6.1.4.1.27880.1.2.1: FreeSWITCH uptime as SNMP TimerTicks (hundredths of seconds)
            .1.3.6.1.4.1.27880.1.2.2: Number of sessions since FreeSWITCH was started
            .1.3.6.1.4.1.27880.1.2.3: Currently active sessions
            .1.3.6.1.4.1.27880.1.2.4: Maximum allowed sessions
            .1.3.6.1.4.1.27880.1.2.5: Currently active calls
            .1.3.6.1.4.1.27880.1.2.6: Current sessions per second
            .1.3.6.1.4.1.27880.1.2.7: Maximum allowed sessions per second
            .1.3.6.1.4.1.27880.1.2.8: Peak sessions per second
            .1.3.6.1.4.1.27880.1.2.9: Peak sessions per second Last Five Minutes
            .1.3.6.1.4.1.27880.1.2.10: Peak sessions
            .1.3.6.1.4.1.27880.1.2.11: Peak sessions Last Five Minutes 

## Links

FreeSWITCH mod_snmp documentation
https://freeswitch.org/confluence/display/FREESWITCH/mod_snmp

Cacti Graphing solution
http://www.cacti.net/