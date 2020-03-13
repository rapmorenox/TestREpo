# Project AIM
This is a flow on how a Risk is created.

This is a flow on how a Risk is created. AA

## Actors


User | Designation               | User Group    | Company Name  | Country
-----|---------------------------|---------------|---------------|----------
Sam  | Division CEO              | Local Heads   | Forge Finance | Singapore
Jony | Associate Director, Audit | Risk Managers | Forge Finance | Singapore
Carl | Director, Sale            | Risk Owner    | Forge Finance | Singapore
Lyn  | Associate, Audit          | Contributor   | Forge Finance | Singapore

---

### Risk Creation Overview AA

![](https://www.plantuml.com/plantuml/svg/XP9RRzf048MVmw_ON5wh0gRc4lN1yOLO9IOoH8YdQcDFx2rcJNONB5hwtxiN2CQALFo2lprpvinuh-yU9Yy--evkRjkMvVQjczRrNHXvuNYgeMrtsa5NmUUN-7bYb7RGwxeT3SFeXqR-mF87haAnxsdYzZjkLrTEOoSQcyh0w_kTde9BVpAPBZJql6zskwtWEFRzIBE-vGoieM9ptvber6sxms5V8NVf65KtS7g-Hel7S7vi4GJ6obd-z9pOnBDwbjDhdxX60tlW3sqzH1m-EV6ouJZptMdadRW_z5rV6yzUNDUVpHefmoYODhQuSE8eZCQD4JsrYxYneKauVfoRz8DW63X6sCZUuYj2DvZXDU8vJikAq0ozuO93xQHYUBCWgSXHPz2-A87tBT04q9_MbSDOMRbbKJBa0Mncg_r3iOMhrjzwWPC8iYDYBmkG_3sKB0LcYlITgT5vJf8L1SvHHzEWf696VWFgs1_lfZ9Zi3U5E5bbhDpIr1mK9Ck5kyVqCWIloBh053u9eIi-_EP4573kOsxrvObEr6rhMEaLSRm6rQzrk9LRbyy1JSe45-WHS8eE2jk16mG751E-Ga-OuWoOEJZgzS6qeYTyrBko7oElMr4gBXjS6e_25AWWRmGu4ZaWfbnAxV85EPoJZFBBdg942GCiGElLqRssRGGRkLfaN35D4OECSA4CZcKef6ybMsD1Iee8hVETp5Io_VrdldESyRDMfb7_JMAHOu4gp14v3PMYrxqMd8S-cvwMDOfXHw0wHjKpoq8jKS4LeVMU7XIGoTcqq-L-Ho7TR8NHKaY0OoRxOrb41Apb3jwtX9rJnUTjgquSQChHgxoGI6v6gbMi_-GbjILkMBcJet_OrxFfIP84DW9zbSw_815Qa-IOPi1bbz5CjrVmZL32yzCIwYrqkEFIzU7w-6K-2rpxQgV8vp6Rdx1sBPMNZ21VyKRDX8lxVm00)



---

### Risk Update Overview

```plantuml
skinparam shadowing false
skinparam ActivityBorderColor blue



| Local Head |
| Risk Manager |
| Risk Owner |
| Contributor |

| Risk Owner |
:Assigns section to delegate ;

| Contributor |
:Makes changes;

:Sends back for approval;

| Risk Owner |
:Reviews and approve;
:Send to Risk Manager;

| Risk Manager |
:Acknowledge;

```

