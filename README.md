# gomarkov

Prepare corpus by putting each string on a single line. Then indicate start/stops with

    sed -e 's/$/ ~~~/' -i corpus && sed -e 's/^/``` /' -i corpus


 
