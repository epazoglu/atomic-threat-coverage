| Title          | RA_0037_containment_block_ip_on_ips                                                                                                      |
|:---------------|:-----------------------------------------------------------------------------------------------------------------|
| Stage    | containment                                                            |
| Automation | None |
| Author    | @atc_project                                                          |
| Creation Date    | 31.01.2019                                            |
| References     | None                                  |
| Description    | Block ip on IPS.                                                               |
| Linked Response Actions | None |
| Linked Analytics |<ul><li>MS_ips</li></ul> |


### Workflow

Block ip on IPS using native filtering functionality.
Warning: 
- If not all corporate hosts access internet through the IPS, this Response Action cannot guarantee containment of threat.
- Be careful blocking IP address. Make sure it's not cloud provider or hoster. In this case you have to use blocking by URL something more specific.