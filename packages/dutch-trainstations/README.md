# Dutch Trainstations

This is an Espanso package.

It helps to convers the abrreviations Dutch railways uses for the railway stations in The Netherlands.

The conversion works in two directions:

- from abbreviation to station. The trigger #ab is used. For example '#abAtn' expands to 'Aalten'.
- from staton to abbreviation. The trigeer #st is used. For eexample '#stAalten' expands to 'Atn'. Spaces in the station names are removed. So in the case of 'Alkmaar Noord', '#stAlkmaarNoord' is expanded to 'Amrn'.

The conversions use word triggers. For example: '#abAmr' expands only after a delimiter to 'Alkmaar'. In that way, you can also type '#abAmrn' for 'Alkmaar Noord'. It also works that way from station to abbreviation.
