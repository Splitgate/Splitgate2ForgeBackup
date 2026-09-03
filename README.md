# Splitgate 2 Forge Backup
> Archive of any/all Forge maps backend data from Splitgate 2.

If any data here is wrong or needs updating please create an issue [here](https://github.com/Splitgate/Splitgate2ForgeBackup/issues).  

## Details

For Splitgate 1 Forge data please refer to, [SplitgateForgeBackup](https://github.com/Splitgate/SplitgateForgeBackup).  

Each directory (except UGC) contains a formatted output of each Forge maps archive data neatly laid out for easy viewing and downloading.

The UGC directory is the raw backend path with the binary format stored on the backend (Standard ZIP archive) whilst preserving the URL path they were held on. 

For example (UGC):  
`/ugc/Rooster/MapCreator_Published/Epic/04548be5-c993-449c-95b1-b75f98706cb6/cd1d3268-ce17-4583-a9f9-2cbede4b6ee9`    
mapped to:      
`https://content-prod.maverick-global.prod.1047games.com/ugc/Rooster/MapCreator_Published/Epic/04548be5-c993-449c-95b1-b75f98706cb6/cd1d3268-ce17-4583-a9f9-2cbede4b6ee9`

This URL path breaks down to `/ugc/(Namespace)/(Group)/(Platform)/(FileId)/(SaveId)` with the end SaveId being the archive itself.

## Map Directory

