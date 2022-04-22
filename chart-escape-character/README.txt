helm install chart-escape-character /tmp/chart-escape-character-0.1.0.tgz
helm package /tmp/chart-escape-character 
helm upgrade chart-escape-character /tmp/chart-escape-character-0.1.0.tgz
