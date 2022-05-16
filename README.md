# spring-gumball ci/cd example

### This example demonstrates the following two GitHub Workflows.

* https://help.github.com/actions/language-and-framework-guides/building-and-testing-java-with-gradle

* https://github.com/google-github-actions/setup-gcloud/tree/master/example-workflows/gke

### Build Dependencies

* Gradle 5.6
* JDK 11

# CI Workflow (Part 1)

## Top part of build screen 
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(464).png)

## Build screen continued complete
![](https://github.com/richardtran298/spring-gumball/raw/main/lab10screenshots/Screenshot%20(467).png)

##
![]()

# CD Workflow (Part 2)

## GCP Service Accoumt & JSON Service Account Key
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(471).png)

## GCP Service Keys
![](https://github.com/richardtran298/spring-gumball/raw/main/lab10screenshots/Screenshot%20(472).png)

## GitHub Action Secrets
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(473).png)

## GCP Clusters
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(469).png)

## Github release make
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(474).png)

## Github release created
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(475).png)

## Github Release Build Start
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(477).png)

## Github build error
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(481).png)

Initially encountered this error which was due to me putting the incorrect project id

## Github build another error 
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(485).png)

Also encontered this error after figuring out the previous error. This error was related to the lack of priveleges in the GCP account

## Fixed Issue
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(487).png)

I was able to fix this issue by giving the spring-gumball owner permissions

## Another build issue involving project id
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(495).png)

I encountered this issue after solving the previous issue and I was able to overcome this by inputting the correct project ID for the GKE_SECRET key.

## Github buildling 
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(503).png)

## Github complete
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(500).png)

## spring-gumball-deployment shown successful in GCP workload page
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(504).png)

## spring-gumball-deployment details screen
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(505).png)

## spring-gumball-service succesful shown in service & ingress screen
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(506).png)

## Ingress creation screen
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(511).png)

## Loadbalancer successfully created 
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(517).png)

## Top part of spring gumball main screen
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(518).png)

## Bottom part of spring gumball main screen
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(519).png)

## White Label error page after cranking 
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(520).png)

The spring-gumball page was able to perform one insert of a quarter and crank but consequent ones seem to crash and I was unable to resolve this issue

## spring-gumball-lb log 
![](https://github.com/richardtran298/spring-gumball/blob/main/lab10screenshots/Screenshot%20(523).png)

I tried looking the the spring-gumball-lb logs to see the source of the error, but there was not much info aside from the 500 error 
