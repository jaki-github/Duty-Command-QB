# Duty-Command-QB

Use /duty command to qbcore to go in duty. I have made it easy for all to use. 

You can put that code in qb-policejob/client/main.lua. That's what I've done and it works

```
RegisterCommand("duty", function()
    TriggerServerEvent("QBCore:ToggleDuty")
end, false) 
