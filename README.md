# Enabling Datapower on AWS

## Steps to install Openshift on AWS
- Use the AWS console to create a Hosted Zone Domain using Route 53
- Connect your DNS server to all of the NS records for the Hosted Zone or follow the documentation - https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/dns-configuring.html
- Alternatively you can register a domain with Route 53 by using the documentation - https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/registrar.html

- docs.aws.amazon.comdocs.aws.amazon.com
- Configuring Amazon Route 53 as your DNS service - Amazon Route 53
- Configure Route 53 to check the health of your resources and to respond to DNS queries using only healthy resources.
docs.aws.amazon.comdocs.aws.amazon.com
- Registering domain names using Amazon Route 53 - Amazon Route 53
- Register new domain names using Amazon Route 53.
- find the 4.8.34 on ocp https://mirror.openshift.com/pub/openshift-v4/clients/ocp/4.8.34/
- Find the `install-config.yaml` and add it to the openshift-install folder.
- run that command 
  ```bash
  ./openshift-install create cluster --dir=.
  ```
- Make sure to 
