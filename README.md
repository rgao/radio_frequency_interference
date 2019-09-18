# Background

This repository condenses the work that I've done on topics involving radio frequency interference and other astronomy topics during my undergraduate years and in my post-graduation internship. 

These files are taken from my larger berkeley repository at https://github.com/rgao/berkeley.

Identifying radio frequency interference is central to most work involving radio astronomy. Due to the proliferation of radio technology in this digital era, radio sources from Earth (along with some of extraterrestrial origins) must be filtered as noise before work is done to detect target extraordinary signals.

### sdr_stations and hack_rf

These Jupyter Notebooks are produced during my internship at Breakthrough Listen. They serve as tutorials for future interns who engage in the basics of scientific computing and radio frequency interference. 

The sdr_stations project uses the Realtek RTL2838 hardware to receive signals in the range emitted by radio stations to track them in a nearby radius. I plotted and identified about 20 stations surrounding the San Francisco East Bay region, then made a waterfall plot displaying the corresponding frequencies.

The hack_rf notebook teaches using the HackRF hardware, along with GNU Radio software, to detect and process cellphone transmissions. HackRF outputs data in I/Q binary format and has first to be converted to floats. The end result of the notebook displays the received cellband transmissions as a function of frequency.

### 21cm line

One of the most fascinating aspects of space is the omnipresent [21cm hyperfine transition radiation emitted from dust containing neutral hydrogen](https://en.wikipedia.org/wiki/Hydrogen_line). Connecting my HackRF to a rooftop telescope at the university and using the gqrx visualization software, I displayed the 21cm line. 

!(https://github.com/rgao/radio_frequency_interference/blob/master/21cm.png)

### Interferometry

This is one of my undergraduate lab reports. 



