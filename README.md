# HP-ISO-Channel v0.99 — fabrication files

A small isolation board. It sits between the HiPIMS controller and the gate-driver boards
(HP-Power / HP-Channel). Generated with KiCad 10.0.8 from `HP-ISO-Channel-v099.kicad_pcb`.

## Board

| Parameter | Value |
|---|---|
| Layers | 2 |
| Size | 65.92 × 82.78 mm, rectangle |
| Thickness | 1.6 mm, FR4 |
| Copper | 35 µm (1 oz), both sides |
| Min track / clearance | 0.2 / 0.2 mm |
| Min drill | 0.3 mm (vias) |
| Vias (pad / drill) | 55 × 0.6 / 0.3, 16 × 0.8 / 0.4, 4 × 1.0 / 0.5 mm |
| Plated holes | components 0.7–1.0 mm; 2 × 3.5 mm (mounting holes H3, H4) |
| Non-plated holes | 2 × 3.5 mm (mounting holes H1, H2) — separate file |
| Slots / oblong holes | none |
| Components | top side only |
| Impedance control | not required |
| Surface finish, colours | not specified in the design — choose at order |

## Files

| File | Content |
|---|---|
| `HP-ISO-Channel-v099-F_Cu.gtl` | Top copper |
| `HP-ISO-Channel-v099-B_Cu.gbl` | Bottom copper |
| `HP-ISO-Channel-v099-F_Mask.gts` | Top solder mask |
| `HP-ISO-Channel-v099-B_Mask.gbs` | Bottom solder mask |
| `HP-ISO-Channel-v099-F_Silkscreen.gto` | Top silkscreen |
| `HP-ISO-Channel-v099-B_Silkscreen.gbo` | Bottom silkscreen (empty) |
| `HP-ISO-Channel-v099-F_Paste.gtp` | Top paste — stencil only |
| `HP-ISO-Channel-v099-B_Paste.gbp` | Bottom paste (empty) |
| `HP-ISO-Channel-v099-Edge_Cuts.gm1` | Board outline |
| `HP-ISO-Channel-v099-PTH.drl` | Plated holes, Excellon, metric |
| `HP-ISO-Channel-v099-NPTH.drl` | Non-plated holes, Excellon, metric |
| `HP-ISO-Channel-v099-job.gbrjob` | Gerber job file |

Gerber RS-274X (X2 attributes), units mm, format 4.6. All layers share the same origin.
