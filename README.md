# SDR
Repositorio para configuración de SDR para entornos linux


Usando las librerias:

https://github.com/Rtone/sdr4iot-ble-rx




using external librarys. 


    Calculate the start/end indexes of IQ BLE data into the global IQ data
    Record timestamped robot positions into a csv file
    Record BLE packet information ['Timestamp','Start_trame','End_trame','Channel frequency','Sample_rate'] into a csv file
    Use a linear interpolation method for robot position estimation for a detected packet
    Tag the IQ BLE data by using the estimaded robot positions
    Extract IQ BLE data from the global IQ data by using the csv file and the whole IQ data file
    Save the extracted IQ BLE data and useful information (Start_Frame, Sample count, Central Frequency, Sample rate, robot positions X & Y) into a descriptive format(sigmf)

# install sigmf via pip
pip install sigmf
