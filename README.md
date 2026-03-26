Panelize with KiKit:

```sh
kikit panelize \
    --layout 'hspace: 0.5mm; vspace: 0.5mm; cols: 2' \
    --tabs 'type: fixed; vcount: 4; hcount: 4' \
    --cuts 'type: mousebites' \
    $(pwd)'/doorbellsensor.kicad_pcb' $(pwd)'/panelized/Untitled.kicad_pcb'
```
