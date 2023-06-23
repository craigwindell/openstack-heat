# Example #2

## Basic template with outputs

This template uses up to 2021-04-16 of the HOT specification

The versions supported by your Openstack system can be found in the Project/Orchestration/Template Versions link

Details for the OS::Nova::Server can be found here:
https://docs.openstack.org/heat/latest/template_guide/openstack.html#OS::Nova::Server

This template will output details of the server via the outputs section using the get_attr function to obtain attributes from objects.

The get_attr is an intrinsic function:
https://docs.openstack.org/heat/latest/template_guide/hot_spec.html#hot-spec-intrinsic-functions

Before deploying this template, ensure you have a key called default_key

This template can be deployed via the dashboard Project/Orchestration/Stacks/Launch Stack

The outputs are found in the Overview of the stack
