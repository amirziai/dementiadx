# Dementia Dx
Better dementia diagnosis through data

## Prediction
> http://dementia.ml/predict2

Post the following 85 variables:
```javascript
{"BEAGIT":"No","BEAHALL":"No","BEANX":null,"BEAPATHY":"No","BEDEL":"No","BEDEP":"No","BEDISIN":"No","BEIRRIT":"No","BEPERCH":"No","BEREM":"No","BEVHALL":"No","BEVWELL":null,"BRADY":null,"CDRGLOB":0.5,"CDRSUM":0.5,"COMMUN":0.0,"CORTDEF":null,"CORTVISL":null,"CORTVISR":null,"CVDMOTL":null,"CVDMOTR":null,"CVDSIGNS":null,"DECCLBE":null,"DECCLMOT":null,"EYEMOVE":null,"FOCLDEF":null,"FRSTCHG":"Cognition","GAITDIS":null,"HOMEHOBB":0.0,"JUDGMENT":0.0,"MEMORY":0.5,"MOFALLS":"No","MOGAIT":"No","MOSLOW":"No","MOTREM":"No","NACCAGE":43.0,"NACCID":"NACC828200","ORIENT":0.0,"PARKGAIT":null,"PARKSIGN":null,"PERSCARE":0.0,"POSTCORT":null,"POSTINST":null,"RESTTRL":null,"RESTTRR":null,"RIGIDL":null,"RIGIDR":null,"SIVDFIND":null,"SLOWINGL":null,"SLOWINGR":null,"SMOKYRS":0.0,"SOMATL":null,"SOMATR":null,"animals":15.0,"beage":-4.0,"bemode":"No behavior symptoms","bmi":1862.0,"decage":43.0,"decline":"Gradual","digiblen":6.0,"digiflen":7.0,"educ":"high school","handed":"left","independ":"independent","living_sit":"partner","logimem":16.0,"memunits":16.0,"mmseorda":5.0,"mmseorlo":5.0,"momode":"No behavior symptoms","naccbehf":"No behavioral symptoms","naccmmse":29.0,"naccmotf":"No behavior symptoms","pentagon":1.0,"race":1.0,"sex":"Male","traila":15.0,"trailali":24.0,"trailarr":0.0,"trailb":65.0,"trailbli":24.0,"trailbrr":1.0,"udsbenrs":null,"udsbentc":-999.0,"udsbentd":-999.0,"vegetables":12.0}
```

## Prediction by file
Post a CSV file to this endpoint:
> http://dementia.ml/predict2_file

A sample CSV file is available here:
> http://dementia.ml/samplecsv