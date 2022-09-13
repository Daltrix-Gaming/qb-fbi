# qb-fbi
A new FBI / FIB job needs to add to your fivem QBUS server.


add this to your qb/qb-core/shared/job.lua
in 
QBShared.Jobs={
	    ['fbi'] = {
        label = 'Federal Investigation Bureau',
        defaultDuty = true,
        offDutyPay = false,
        grades = {
            ['0'] = {
                name = 'Trainee',
                payment = 50
            },
            ['1'] = {
                name = 'Agent',
                payment = 75
            },
            ['2'] = {
                name = 'Field Agent',
                payment = 100
            },
            ['3'] = {
                name = 'Special Agent',
                payment = 125
            },
            ['4'] = {
                name = 'Director',
                isboss = true,
                payment = 150
            },
        },
    }
}


## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core) -To implement the job
- [qb-bossmenu](https://github.com/qbcore-framework/qb-bossmenu) - For the boss menu
- [qb-garages](https://github.com/qbcore-framework/qb-garages) - For the vehicle spawner
- [qb-clothing](https://github.com/qbcore-framework/qb-clothing) - For the locker room
- [qb-phone](https://github.com/qbcore-framework/qb-phone) - For the MEOS app and notifications etc.
- [qb-log](https://github.com/qbcore-framework/qb-logs) - For logging certain events
- [qb-menu](https://github.com/qbcore-framework/qb-menu) - For the vehicle menus
- [qb-input](https://github.com/qbcore-framework/qb-input) - For accessing evidence stashes
