# Example #4

## Basic template with references to other objects

This template uses up to 2021-04-16 of the HOT specification

The versions supported by your Openstack system can be found in the Project/Orchestration/Template Versions link

Details for the OS::Nova::Server can be found here:
https://docs.openstack.org/heat/latest/template_guide/openstack.html#OS::Nova::Server

This template will deploy a basic server and a security group with the option of providing parameters. The get_resource intrinsic function is used to link resources.

Details for the get_resource can be found here:
https://docs.openstack.org/heat/latest/template_guide/hot_spec.html#get-resource

Before deploying this template, ensure you have a key called default_key, or use a parameter to override the key name.

The parameters are entered on the Launch Stack page when launching the stack.

This template can be deployed via the dashboard Project/Orchestration/Stacks/Launch Stack

Once deployed, the parameters used are shown in the Overview/Stack Parameters section.
