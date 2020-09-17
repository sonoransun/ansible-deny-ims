# ansible-deny-ims

Ansible play to block access to instance metadata service on AWS for non-root
users.

Many new to AWS are surprised to learn that unprivileged access to the
instance metadata service can be used to completely destroy your instances
and network.

By restricting access to root users only, you avoid a service vulnerability
from becoming a critical hole in your infrastructure.

For more information on this type of attack, see:
 https://medium.com/@shurmajee/aws-enhances-metadata-service-security-with-imdsv2-b5d4b238454b

