helm install chart1 /tmp/chart1-0.1.0.tgz
helm package /tmp/chart1 
helm upgrade chart1 /tmp/chart1-0.1.0.tgz
