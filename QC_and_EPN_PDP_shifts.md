# QC and EPN/PDP Shift Instructions

[Back to previous page](https://github.com/reynier0611/alice_shift_notes/blob/main/getting_trained_for_shifts.md)

First of all, connect via proxy. Instructions can be found [here](https://security.web.cern.ch/recommendations/en/ssh_browsing.shtml).
After proxy has been properly setup, go to a terminal and enter:

```ssh -D 8080 lxtunnel.cern.ch -N -l <username>```, followed by the password. Now we should have access to the Logbook, Grafana, ...


Daily instructions can be found [here](https://codimd.web.cern.ch/s/egBCjyIsU). This page is being updated every day, so make sure to refresh.

---

## Useful links:
- Zoom link for the ALICE Global commissioning shift: [https://cern.zoom.us/j/67442491687?pwd=MWFlTWFGQ0dwUytTRCtOWERGc3pUUT09](https://cern.zoom.us/j/67442491687?pwd=MWFlTWFGQ0dwUytTRCtOWERGc3pUUT09)
- Mattermost: [https://mattermost.web.cern.ch/](https://mattermost.web.cern.ch/)
Join the following channels:

   ```
   RC_PUBLIC
   SHIFT-CREW-ARC
   ShIFT-EPN/PDP
   SHIFT-QC
   ```

- InfoLogger: [http://alihlt-gw-prod.cern.ch:8081](http://alihlt-gw-prod.cern.ch:8081)
- Logbook: [https://ali-bookkeeping.cern.ch](https://ali-bookkeeping.cern.ch)
- Grafana: [http://alihlt-gw-prod.cern.ch:3320/](http://alihlt-gw-prod.cern.ch:3320/)
- Oncall contacts: [https://alice-glance.cern.ch/alice/sams/public/src-display](https://alice-glance.cern.ch/alice/sams/public/src-display)
- Run numbers can be found here: [https://alice-flp.docs.cern.ch/Shifters/aliecs/](https://alice-flp.docs.cern.ch/Shifters/aliecs/)

      Click on the appropriate detector currently taking data (e.g. TPC) and then click on ```AliECS GUI```

---

## Common for QC and EPN/PDP shifts:
- Write end-of-shift report. A template can be found [here](https://codimd.web.cern.ch/s/egBCjyIsU).

## QC shift specific tasks:
- Check histograms here: [https://qcg.cern.ch/?page=objectTree](https://qcg.cern.ch/?page=objectTree)

## EPN/PDP shift specific tasks:
- Check Grafana and Infologger

Grafana: click [here](http://alihlt-gw-prod.cern.ch:3320/d/8awXt_qGz/output-rates-and-sizes?orgId=1&refresh=5m&from=now-1h&to=now&var-hostname=All&var-run=All&var-partition=2SjV3CAUaRj).
If that does not work, click here: [http://alihlt-gw-prod.cern.ch:3320/](http://alihlt-gw-prod.cern.ch:3320/) and
search ```output rates and sizes```

InfoLogger: click [here](http://alihlt-gw-prod.cern.ch:8081/?q={%22severity%22:{%22in%22:%22W%20E%20F%22}})
- Unmark ```Info``` at the top-center
- Unmark ```Query``` at the top-left corner
- Mark ```Hostname``` at the top-left corner

## Other links:
- Indigo page (with [slides](https://indico.cern.ch/event/1056063/contributions/4438295/attachments/2291703/3896490/PDP-EPN_Shifter_Instructions.pdf)) from EPN/PDP class [here](https://indico.cern.ch/event/1056063/)
- Indico page (with [slides](https://indico.cern.ch/event/1065015/attachments/2291529/3896109/QC_class_29.07.2021.pdf)) from QC class [here](https://indico.cern.ch/event/1065015/)
- Booking classes: [https://alice-glance.cern.ch/alice/sams/classes/calendar](https://alice-glance.cern.ch/alice/sams/classes/calendar)
- Booking trainings: [https://alice-glance.cern.ch/alice/sams/shift/booking](https://alice-glance.cern.ch/alice/sams/shift/booking)
