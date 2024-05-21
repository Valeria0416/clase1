import stata_setup
stata_setup_config"C:\Program Files\Stata16\StataIC-64.exe"


cd"C:\Users\Estudiante\Downloads\pib_ecu.dta"
use pib_ecu
tsset año, yearly
gen lpib = log(productointernobruto)
