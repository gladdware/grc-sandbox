# GNU Radio Companion Sandbox

Workspace for my GNU Radio Companion flow graphs. I figured other people
starting out in the world of SDR may find these useful.

## Dependencies

1. Osmocom RTL-SDR driver and gr-osmocom (http://sdr.osmocom.org/trac/wiki/rtl-sdr)
  * The RTL-SDR blocks could be swapped out for other SDRs
2. GNU Radio 3.6.3 with GNU Radio Companion (http://gnuradio.org/redmine/projects/gnuradio/wiki)
  * Older versions may work also, but I'm using 3.6.3

## GRC Files

* **nbfm_file**: Narrowband FM receiver from a file (see voice_spec.grc)
* **nbfm_rx**: Narrowband FM receiver using the RTL-SDR
* **spec_fft**: Simple FFT dump; adjustable range covers typical RTL-SDR frequency range
* **voice_spec**: Narrowband FM "transmitter"; just dumps to a file (for use in nbfm_file.grc)
* **wbfm_rx**: Wideband (broadcast) FM receiver; good for listening to local FM stations

## Copyright

Copyright 2013 Alex Gladd (unless otherwise noted)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

