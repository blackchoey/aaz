# [Command] _network cross-region-lb address-pool address update_

Update the backend address into the load balance backend address pool.

## Versions

### [2022-05-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2xvYWRiYWxhbmNlcnMve30vYmFja2VuZGFkZHJlc3Nwb29scy97fQ==/2022-05-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/loadbalancers/{}/backendaddresspools/{} 2022-05-01 properties.loadBalancerBackendAddresses[] -->

#### examples

- Update the frontend ip of the backend address into the load balance backend address pool.
    ```bash
        network cross-region-lb address-pool address update -g MyResourceGroup --lb-name MyLb --pool-name MyAddressPool -n MyAddress --frontend-ip-address /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/cli_test_lb_address_pool_addresses000001/providers/Microsoft.Network/loadBalancers/regional-lb/frontendIPConfigurations/fe-rlb2
    ```