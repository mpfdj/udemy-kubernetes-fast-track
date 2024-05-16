https://inglearn.udemy.com/course/kubernetes-fast-track
https://github.com/addamstj/kubernetes-course

# Intellij kubernetes plugin
https://plugins.jetbrains.com/plugin/10485-kubernetes



ingress controller
kube proxy
kube dns


kubectl get pods -o wide

kubectl exec -it <POD ID> -- /bin/bash
kubectl logs -f <POD ID>
kubectl logs -f <POD ID> -c <CONTAINER NAME>  # When running multiple containers in a pod
kubectl describe pod <POD ID>
kubectl get pod <POD ID> -o yaml > mypod.yml
kubectl edit deployment <DEPLOYMENT ID>

minikube addons enable metrics-server
kubectl top pod
watch kubectl top pod <POD ID>
watch kubectl top pod <POD ID> --containers
watch kubectl top node

minikube dashboard

kubectl label nodes <NODE ID> mylabel=hello






Stay up to date
Technology is changing fast, are you keeping up? Or you can’t track the latest trends because you have so little time?

Change that today. It’s me – TJ Addams and I will help you navigate the complex world of DevOps.

Check out and subscribe to the Warp 9 YouTube channel for game-changing career advice and DevOps news and tools: https://www.youtube.com/channel/UCqKggOZpJKvZSPxb9hrN37A

Keep up to date with our Facebook page for the latest news: https://www.facebook.com/Warp-9-107345530978685

Ask questions, get advice and ask me directly in the official Facebook Group: https://www.facebook.com/groups/warp9training

And if you're on LinkedIn and want to get in-touch with me, personally. Here's my link: https://linkedin.com//in/tjaddams

Stay safe and I'll see you soon.

Kind regards,
TJ
