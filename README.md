# uSDX-EX-SDR RADIO

This project are in attempt to integrate USDX HF transceiver version from WB2CBA with the following features:

01 - Automatic 6 bands LPF and RF PA LPF selection.

02 - RF power amplifier (RFPA) controlling process, since it is crucial for the proper RF transition sequence.

03 - SWR measurements, with a simplified LED indicator - 1->1.5 (BEST), 1.5->1.9 (BETTER), 1.9->3 (GOOD), >3 (POOR).

04 - 30W SSB RF linear power amplifier. 

05 - RF spectrum display experimentation.

Below are the first prototype image:

![WhatsApp Image 2023-08-20 at 12 53 13 AM](https://github.com/bahari/USDX-CNTRL-MCU/assets/3076739/5cad0087-fde6-4f5a-9aa8-bb502913f045)

# Brief Information - SDR Radio

The uSDX-EX SDR radio (EX means EXTRA/EXPERIMENTATION) was adopted from the well known projects known as micro SDX (uSDX) - Micro Software Defined Transceiver, 
which you can get the information via the following link:

https://github.com/threeme3/usdx

The base radio firmware was taken from expand/additions version made by Rob Colclough GW8RDI, hence you can see the copyright term written in the code itself.
But the concept of copyright are still open source as stated below:

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Maintaining the spirit of open source

The main board for SDR radio was a self assembled board develop by WB2CBA and the kit can be purchased online. The further information
regarding this developments you can get via the following link:

https://antrak.org.tr/blog/usdx-an-arduino-based-sdr-all-mode-hf-transceiver-pcb-iteration-v1-02/

The modification was been done as following:

01 - Maintaining using Si5351 signal genarator module as been suggested by WB2CBA for signal debugging and verification process.

02 - Replacing 
