# codeigniter-operator
Codeigniter Operator for Kubernetes built with Ansible and the Operator SDK.

This Codigniter Operator makes it super easy to manage Codeigniter running within
a Kubernetes cluster.

### Motivation

In 2021, Operators in Kubernetes is the new deal. I decided to build a sample operator
as a way to understand Operator SDK and the Ansible Operator. Guessing I most not be
Go proficient in order to build an Operator.

To understand exactly how this operator has been built, please have a look at the
following documentation [Ansible operator](https://sdk.operatorframework.io/docs/building-operators/ansible/tutorial/)
and ofcourse the official Operator SDK documentation.

The motivation to build a CodeIgniter Operator was greatly influenced by works from the Drupal Operator found [here](https://www.jeffgeerling.com/blog/2019/drupal-operator-kubernetes-ansible-operator-sdk)