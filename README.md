# Software Sustainability and Open Source Hardware

Notes and links supporting an Open Source Hardware themed application to the SSI Fellowship scheme. 

The Fellowship scheme offers participants a £4K bursary, intended mainly to be used to organise or participate in workshops and events.

## Micro pitch - "Open Source Hardware for Environmental Monitoring"

A series of [workshops](WORKSHOPS.md) bringing together research engineers working on tools for environmental sensor data analysis, and open source hardware and networking enthusiasts working on low-power, low-bandwidth micro devices. Discuss and document potential novel applications while simultaneously engaged in a hands-on prototyping exercises, with most of the workshop budget going towards a small repurposable kit per attendee. Workshops to run over the course of a week (likely in late Spring 2025) in three or four different locations across the UK.




## Prior art 

### Workshops and seminars

* [Wave Farm residency](https://zachpoff.com/artwork/wave-farm-residency-2013/?highlight=hydrophone%20experiments) - 2013 New York State workshop by Zach Poff and N.B. Aldrich, lightweight sensor building, smartphone based
* [Wuthering Bytes / Open Source Hardware Camp](https://wutheringbytes.com/news/2024/open-source-hardware-camp-2024-programme-announced) 2024
* ["The Three Ingredients for Scaling-Up Water Sensor Networks: People, Platform, and Protocols"](https://digitalenvironment.org/cde-webinar-dr-scott-ensign-and-shannon-hicks/) - NERC seminar covering EnviroDIY / WikiWatershed, see below
* [Gathering for Open Science Hardware](https://openhardware.science/)
  
  
### Labs and Networks

* [Openly Published Environmental Sensing](https://open-sensing.org/) Oregon State, College of Agricultural Sciences. "_From soldering stations to 3D printers to laser cutters, our lab provides the tools necessary for students, professors, and researchers alike to develop tools used locally and worldwide by the ecological science and engineering community._"
* [EnviroDIY](https://www.envirodiy.org/) - Stroud Water Research Center
* [Bristol Wireless](https://www.bristolwireless.net/) - Social enterprise to build a LoRaWAN/IoT backbone for Bristol, evolving from community wifi
* [BreathLondon](https://www.breathelondon.org/) - London Air Quality monitoring community network run by the Environmental Research Group, at Imperial College London

### Sampling devices

* [Mayfly](https://www.envirodiy.org/mayfly/) data logger, "comprised of sensors for measuring conductivity, temperature, depth, and turbidity"
* [AudioMoth](https://www.openacousticdevices.info/audiomoth) low-cost, full-spectrum acoustic logger, ultrasonic frequencies, underwater plans
* [PiZero Air Quality Sensor](https://www.cemac.leeds.ac.uk/home/project-summaries/sensormon/pi-zero-portable-air-quality-sensor-construction-in-10-simple-steps/) DIY temperature and humidity sensor based on Raspberry Pi zero
* [Airgradient](https://www.airgradient.com/documentation/diy/) DIY sensor that measures temperature, humidity, CO2 and particulate matter.
* [EmonPi](https://github.com/openenergymonitor/emonpi) Energy monitoring sensor based on Raspbery Pi (not required but comes with its own [software stack](https://github.com/emoncms/emoncms)

## SSI scheme and application 

* [SSI Fellowship programme 2025](https://www.software.ac.uk/news/ssi-fellowship-programme-2025-applications-now-open)

This required a 6 minute recorded voiceover slideshow presentation which includes 2 minutes self-promotion and professional context setting.

### Presentation

[Quarto presentation markdown](index.qmd)

* [Install Quarto from packages](https://quarto.org/docs/download/index.html) 

```
wget https://github.com/quarto-dev/quarto-cli/releases/download/v1.5.57/quarto-1.5.57-linux-amd64.deb
dpkg -i quarto-1.5.57-linux-amd64.deb
```

* [Install reveal.js from git repository](https://revealjs.com/installation/) - follow the "Full Setup" instructions

* With `index.qmd` copied into the `reveal.js` directory, run `quarto render index.qmd --to revealjs`




