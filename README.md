# K8s-Resource-Quota

********

Resource quota is an object in kubernetes which enables the administrator to restrict the 
resource usage per namespace. In simple words, resource quota defines the limit of resource.
you can limit memory, compute, storage.

you can define the limit of namespace with the resourcequota.yml file.
 
*******

<h3>Resources for container </h3>

Generally, A pod in kubernetes will run with no limit of cpu and memory.But one can optionally decide how much cpu and ram each container needs. Then scheduler of master node 
decides in which node this pod will be placed . This will be possible when the node has enough resources according to pod needs.

********