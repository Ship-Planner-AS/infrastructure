
# Instructions
1 Launch the AWS CloudFormation stack using the [vpc-peereng-*-sg.yaml](cloudformation/VPC/peering/vpc-peereng-security-group/vpc-peereng-sg.yaml) template file as
   the source, to create the security groups for communications with the VPC peering connection.

2 Launch the AWS CloudFormation stack using the [vpc-peering-requester-Infra-to-uat.yaml](cloudformation/VPC/peering/infra-to-uat/vpc-peering-requester-Infra-to-uat.yaml) template file as
   the source, to create the VPC peering connection in the requester account.

3 Launch the AWS CloudFormation stack using the [vpc-peering-updates-route-uat.yaml](cloudformation/VPC/peering/infra-to-uat/vpc-peering-updates-route-uat.yaml) template file as the source, to
   update the specified route tables & security groups for communications with the VPC peering connection in the requester account.

4 Launch the AWS CloudFormation stack using the [vpc-peering-updates-route-infra.yaml](cloudformation/VPC/peering/infra-to-uat/vpc-peering-updates-route-infra.yaml) template file as the source, to
   update the specified route tables & security groups for communications with the VPC peering connection in the accepter account.

