Tutorial for Synthesizer and Test Scripts

1. First start the Jack client with the following command:
`$ jackd -d also`

2. Next you need to start up webmapper. First switch to the dependencies/webmapper directory and run the following command:
`$ python webmapper.py`

3. Now you can open the webmapper user interface in your browser by going to localhost:portnumber, replacing port number with the number that appears in your terminal.

4. Next you can run one of the dummy data python scripts with either of the following commands:
`$ python square_wave_test.py`
`$python ramp.py`

5. Next you need to run the synthesizer with the following sequence of commands:
`$ g++ karplus_strong.cpp`
`$ ./a.out`

6. Now you can go to the web mapper UI and connect the lib mapper devices, namely the output device from the python dummy data script and the synthesizer input device. 

7. To hear the output audio connect your headphones to the headphone jack on the Raspberry Pi. 
