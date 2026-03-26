Circuit (KiCad project) to detect door chime or warble tone from a PK543A or similar
apartment intercom amplifier.
To be wired in parallel with apartment intercom.

Based on information from [this post by Chris Whong](https://chris-m-whong.medium.com/connecting-an-apartment-door-buzzer-to-a-smarthome-hub-4664cf6a3ce4).
This board provides the same functionality as the discontinued Alpha Communications RY014B.

Inputs: X and 1 from intercom.

Outputs: dry contact relay (normally-open and normally-closed terminals).

Panelize with KiKit:

```sh
kikit panelize \
    --layout 'hspace: 0.5mm; vspace: 0.5mm; cols: 2' \
    --tabs 'type: fixed; vcount: 4; hcount: 4' \
    --cuts 'type: mousebites' \
    $(pwd)'/doorbellsensor.kicad_pcb' $(pwd)'/panelized/Untitled.kicad_pcb'
```
