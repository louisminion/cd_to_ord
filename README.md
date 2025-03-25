# cd_to_ord
Open source tool to Convert Circular Dichroism spectra to Optical Rotation via the Kramers-Kronig transform.

Usage:
```console
user@pc:~$ python ORDcalc.py $filename
#################-ORDcalc-#################
Input; csv file with two columns, wavelength and CD, no column labels
Output; csv file with two columns, wavelength and CB
WARNING; No background subtraction done here, input already subtracted CD data

Loading filename $filename
```
