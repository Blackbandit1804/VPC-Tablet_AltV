# wgc_ui
Alt:V Standalone Ingame UI for VPC/Copnet/Medicnet/Carnet.

# How to use:
```
alt.emit('WGC:Client:Tablet:open', [TYPE], [SYSTEM], [PUBLICID]);
```

`[SYSTEM]` You can choose between Copnet ( **cop**), Medicnet (**medic**) and Carnet (**car**).

`[TYPE]` You can choose between a Tablet (**tab**) and PC (**pc**) design.

`[PUBLICID]` Only needed for carnet.


You can close it with:
```
alt.emit('WGC:Client:Tablet:close');
```

*If you make mistakes, the system will report to you automatically.*
