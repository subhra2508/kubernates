## kubernates

### kubernates architechture and terminology :

- kubernates: The whole orchestration system
  - k8s "k-eights" or kube for short
- kubectl: CLI to configure kubernates and manage apps
  - using "cube control" official pronounciation
- Node: Single server in the kubernates cluster
- Kubelet : Kubernates agent running on nodes
- Control Plan(master): Set of container that manage the cluster
  - Includes API server,scheduler,controller manager,etcd,core DNS and more
  - Sometimes called the "master"
### Install Kubernates Locally :
- Docker Desktop : Enable in settings
  - Sets up everything inside Docker's existing Linux VM
- Docker ToolBox on Windows: MiniKube
  - Uses VirtualBox to make Linux VM
- Own Linux Host or VM : MicroK8's
  - Installs Kubernates right on the OS
- Kubernates In A Browser
  - Try http://play-with-k8s.com or katacoda.com in browser
  - Easy to get started
  - Doesn't keep your enviroment
 
