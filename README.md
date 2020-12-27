# qb-gundealerjob
Gundealer job script for QBCore - Stash , Armory , Vehicle Spawner , Blip

Add the job to qb-core folder after open shared.lua

For those who use qb server without JOB GRADES

["gundealer"]=  {
    label = "Gundealer",
    payment = 500,
    defaultDuty = true,
},

For those who use qb server with JOB GRADES

["gundealer"] = {
    label = "Gundealer",
    defaultDuty = true,
    grades = {
        [1] = {
            label = "Starter",
            payment = 500,
        },
    }
}, 
