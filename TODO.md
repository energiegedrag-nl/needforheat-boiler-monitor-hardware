# TODO – needforheat-boiler-monitor-hardware

Open work for this repository, distilled from the old NeedForHeat Trello board (paraphrased and regrouped) and from the 2026 maintenance review.

Items that touch several repositories are written out in full in one *lead* repository; the others list them with a link (→). Keep the details up to date in the lead repository only.

## Later: features and ideas

- [ ] <a id="bmpcb"></a>**BoilerBASE electronics.** Add an 868 MHz transceiver to monitor wireless (Honeywell) thermostats; decide where the optocouplers go (BoilerBASE or splitter); reconsider the OpenTherm traffic LEDs; stretch goal: harvest power from the OpenTherm wire. Also affects: needforheat-boiler-monitor-firmware. *(Trello #299, #657, #1054, #1053, #1056, #566)*
- [ ] <a id="bmconn"></a>**Tool-free thermostat wire connection.** Make connecting the thermostat wires foolproof: polarity-independent inputs, lever clamps instead of screw terminals, or a non-cutting probe. *(Trello #562, #314, #1164)*
- [ ] <a id="clamps"></a>**Smaller pipe clamps with better heat transfer.** Clamps must fit short pipe sections (about 1 cm) and conduct heat well; enclosures orderable from a PCB/3D service; secure mounting to the CoreInk. *(Trello #297, #656)*
- [ ] <a id="protocols"></a>**Other boiler protocols.** Splitter modules for eBus, EMS and similar protocols besides OpenTherm. Also affects: needforheat-boiler-monitor-firmware. *(Trello #287)*
- [ ] <a id="modular"></a>**Modular enclosures and a battery base.** Enclosures that fit a letterbox parcel; a 3xAAA battery base for the CoreInk for battery-powered use. Also affects: needforheat-p1-base-hardware. *(Trello #298, #304)*
- [ ] → Helpdesk chart for thermostat wire polarity and crossover — see [needforheat-manuals](https://github.com/energiegedrag-nl/needforheat-manuals/blob/prd/TODO.md#polarity) *(Trello #269)*
- [ ] → Boiler monitor firmware backlog — see [needforheat-boiler-monitor-firmware](https://github.com/energiegedrag-nl/needforheat-boiler-monitor-firmware/blob/main/TODO.md#bmfw) *(Trello #567, #488, #563, #406)*
