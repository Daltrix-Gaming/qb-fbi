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
