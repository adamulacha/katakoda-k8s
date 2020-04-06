Check if this test environment is properly provisioned:
`kubectl get nodes`{{execute}}

You should see 2 nodes (master and node01) in Status Ready. If not - try to refresh this page and try again.

Clone the Pluralsight training (https://app.pluralsight.com/library/courses/kubernetes-developers-core-concepts/table-of-contents) repository:
`git clone https://github.com/DanWahlin/DockerAndKubernetesCourseCode.git && cd ./DockerAndKubernetesCourseCode/samples/`{{execute}}
