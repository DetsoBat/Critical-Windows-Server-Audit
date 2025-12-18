✅ Server Retirement Checklist

🔹 Preparation
☐ Identify all server roles (DNS, DHCP, file shares, printers, apps)
☐ Run and save audit report
☐ Notify stakeholders of planned changes
☐ Take full server backup (system + data)

🔹 Migrate / Replace Services
☐ Move DHCP to firewall/router and verify leases
☐ Migrate DNS zones or confirm clients use new DNS
☐ Migrate or archive file shares
☐ Migrate printers to new print host or cloud solution
☐ Update client configs (DNS, mapped drives, printers)

🔹 Validation
☐ Confirm clients get IPs from new DHCP server
☐ Verify DNS resolution from multiple workstations
☐ Test file access and permissions
☐ Test printing from user devices
☐ Monitor for errors or user issues

🔹 Decommission
☐ Stop and disable server roles/services
☐ Leave server powered on (services disabled) for observation period
☐ Remove server from domain
☐ Power off server
☐ Decommission or repurpose hardware/VM

🔹 Documentation
☐ Update network and system documentation
☐ Record retirement date and actions taken
☐ Confirm no dependencies remain
