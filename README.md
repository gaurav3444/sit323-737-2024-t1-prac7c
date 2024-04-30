# Application Verification 

To ensure your application is running smoothly, follow these steps:

1. **Check Pods:**
   Use the following command to display the list of Pods in your Kubernetes cluster along with their statuses:
   ```bash
   kubectl get pods

2. **Check Services:**
   Execute the command below to view the list of Services in your Kubernetes cluster, including their ClusterIPs and external endpoints:
   ```bash
   kubectl get services

3. **Access Application in Web Browser:**
   Open your web browser and enter 'localhost:<local port>' in the address bar, replacing '<local port>' with the port number specified in the 'create service.yaml' file.
   
   <img width="577" alt="Screenshot 2024-04-30 at 3 38 05 pm" src="https://github.com/gaurav3444/sit323-737-2024-t1-prac7c/assets/66586901/222dccd3-44de-488b-8ebc-e21088fdb0eb">
   
