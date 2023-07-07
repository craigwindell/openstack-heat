# Example #5

## Basic template with forced dependencies to other objects

This template uses up to 2021-04-16 of the HOT specification

The versions supported by your Openstack system can be found in the Project/Orchestration/Template Versions link

When the get_resource function is used, the dependent resource is created before the calling object. It is possible to control the order of resource creation with the depends_on attribute. This ensures the order of dependent resources.

This template will deploy a two basic servers and with security groups with Server01 needs to be running before Server02 can be built as there might be services running on it, such as a database.

Details for the depends_on can be found here:
https://docs.openstack.org/heat/latest/template_guide/hot_spec.html#resource-dependencies

This template also takes advantage of the security group referencing. Rather than specify a fixed IP address or range, a security group can use another security group for the access. What a server is assigned the remote security group, it will have access.

Before deploying this template, ensure you have a key called default_key, or use a parameter to override the key name.

The parameters are entered on the Launch Stack page when launching the stack.

This template can be deployed via the dashboard Project/Orchestration/Stacks/Launch Stack

Once deployed, the parameters used are shown in the Overview/Stack Parameters section.
