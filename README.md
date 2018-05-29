# Network STP configuration

Ansible role that configures STP for networking devices. 

The configuration of the role is done so that it shouldn't be necessary to modify the role for any configuration.
All settings can be configured by changing role parameters or by declaring new config as variable.

Please report any issues or send PR.

## Examples

```yaml
---

- name: Example of how to configure basic STP



```

## Role variables

```yaml
# Define the vlan range to be added in STP, these should already be present as vars from the vlan role (see README for examples)
vlan_range:  {}

# Define the vlans to be added in STP, these should already be present as vars from the vlan role (see README for examples)
vlans: {}

# Define the STP parameters
stp_config: {}

# If you want to see what config is being pushed to the device, set this var true
stp_display_config: {}
```


## License

Apache


## Author

Dan Murarasu
