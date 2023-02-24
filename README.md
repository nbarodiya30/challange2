# challange2
This YAML code creates a Namespace called my-namespace and a ConfigMap called sample-data in that namespace to store the sample data in the form of a CSV file. 
The three pods pod-a, pod-b, and pod-c are also created in the my-namespace namespace, and their resource requirements are set to 400 MB, 200 MB, and 400 MB respectively,
using the resources field in the YAML code. Finally, a Pod called mediawiki is created that needs to access the sample data CSV file. 
To make the CSV file available to this Pod, a volume is created with the configMap field that references the sample-data ConfigMap, 
and the volume is mounted to the container's file system using the volumeMounts field.
