# spring-gumball

1. CI Workflow <br />
![](images/spring-gumball_CIworkflow.png) <br />
![](images/spring-gumball_CIworkflowaction.png) <br />

2. CD Workflow <br />
 ![](images/spring-gumball_CDworkflow.png) <br />
 ![](images/spring-gumball_CDworkflowbuild.png) <br />
 
 2.1 GCP Service Account & Service Key <br />
  ![](images/spring-gumball_gcpservice.png) <br />
  ![](images/spring-gumball_gcpkey.png) <br />
  
 2.2 GitHub Action Secrets 
  ![](images/spring-gumball_actionsecrets.png) <br />
  
 2.3 GKE Cluster 
  ![](images/spring-gumball_gkecluster.png) <br />
  
 2.4 GitHub Release
  ![](images/spring-gumball_githubrelease.png) <br />
  ![](images/spring-gumball_githubrelease2.png) <br />
 
 2.5 GitHub Workflows & build 
  ![](images/spring-gumball_2.3workflow.png) <br />
  ![](images/spring-gumball_builderror.png) <br />
  
 2.6 Build Error 
  ![](images/spring-gumball_2.4workflow.png) <br />
  ![](images/spring-gumball_2.4builderror.png) <br />
  ![](images/spring-gumball_2.4builderrordetail.png) <br />
  
 3. Discussion 
  Even tough I put the correct value on GKE_PORJECT and GKE_SA_KEY, the build was failed. I guess the reason of failure is the version of gcloud. 
