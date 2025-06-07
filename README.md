# argocd-superapp


ArgoCD application of applications.
Instead of managing multiple "applications" through argocd, use this Superapp to manage all the microservices under the same project.
A bit more robust as compared to ArgoCD applicationSets as we have complete control over the version.txt file, which can be populated directly from Bitbucket, also straightforward rollbacks.
