# Instructions to deploy
1. oc new-project demo
2. wget https://raw.githubusercontent.com/praveensiddu/sampleapp-aws-ocp/main/demo/pod.yaml
3. wget https://raw.githubusercontent.com/praveensiddu/sampleapp-aws-ocp/main/demo/demo-pvc.yaml
4. oc create -f demo-pvc.yaml
5. oc create -f pod.yaml

