# Elyne Lab Director — evidence and limits

**English · [Français](evidence.md)**

| Dated source | Observation | Limit |
| --- | --- | --- |
| Demonstration kit G, October 2026 | Internal kit traces describe a timed sequence and Red-oracle classifications. | The product owner clarified that no new qualifying Red Team campaign took place on 19 October. These counts are not published as defense results. |
| Demonstration kit G, restoration | The operator restored the snapshot in VMware; host/guest checks were then observed. | The ELD process remained in restoration/verification; automatic closure was not demonstrated. |
| Demonstration kit H, 19 October 2026 | Snapshot restoration was attested by the operator. | ELD remained `RESTORING` with `SAFE_TO_CONTINUE=false`; no final PASS. |
| Public catalogue, checked 24 October 2026 | ELD is labelled “Laboratory”. | Declared commercial status. |

The kit documents short demonstration orchestration; it does not establish a fully automatic one-click demo or a new Red Team campaign verdict. Launcher exit code `0` only means that process ended: it does not turn `RESTORING` or an **INCONCLUSIVE** defense outcome into PASS.
