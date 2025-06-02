# connector-fortinet-fortirecon-aci

## Changelog

### 2.1.1

Edit: <anonyges@gmail.com>

#### Code Changes

- API endpoint change
  - reports.py, get_reports, endpoint was changed to "/aci/{org_id}/intel/reports"
  - reports.py, get_reports_with_iocs, endpoint was changed to "/aci/{org_id}/intel/reports"
  - ioc.py, get_iocs, endpoint was changed to "/aci/{org_id}/intel/iocs"
  - reference: <https://fndn.fortinet.net/index.php?/fortiapi/2232-fortirecon/5042/2232/ACI/>
