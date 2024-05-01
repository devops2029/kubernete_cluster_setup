k create rolebinding insecure --serviceaccount kubernetes-dashboard:kubernetes-dashboard --clusterrole view -n kubernetes-dashboard
k create clusterrolebinding insecure --serviceaccount kubernetes-dashboard:kubernetes-dashboard --clusterrole view -n kubernetes-dashboard

