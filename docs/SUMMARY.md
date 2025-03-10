# Table of contents

* [Introduction](README.md)
* [Getting Started](setup/getting-started/getting-started.md)
* [Install Devtron](setup/install/README.md)
  * [Install Devtron with CI/CD](setup/install/install-devtron-with-cicd.md)
  * [Install Devtron with CI/CD and GitOps (Argo CD)](setup/install/install-devtron-with-cicd-with-gitops.md)
  * [Install Devtron without Integrations](setup/install/install-devtron.md)
  * [Install Devtron on Minikube, Microk8s, K3s, Kind](setup/install/Install-devtron-on-Minikube-Microk8s-K3s-Kind.md)
  * [Demo on Popular Cloud Providers](setup/install/demo-tutorials.md)
  * [Backup for Disaster Recovery](setup/install/devtron-backup.md)
  * [Uninstall Devtron](setup/install/uninstall-devtron.md)
  * [FAQs](setup/install/faq-on-installation.md)
* [Devtron Kubernetes Client](setup/install/install-devtron-Kubernetes-client.md)
* [Configurations](setup/configurations/configurations-overview.md)
  * [Installation Configurations](setup/install/installation-configuration.md)
  * [Override Configurations](setup/install/override-default-devtron-installation-configs.md)
  * [Ingress Setup](setup/install/ingress-setup.md)
* [Global Configurations](user-guide/global-configurations/README.md)
  * [Host URL](user-guide/global-configurations/host-url.md)
  * [GitOps](user-guide/global-configurations/gitops.md)
  * [Projects](user-guide/global-configurations/projects.md)
  * [Clusters & Environments](user-guide/global-configurations/cluster-and-environments.md)
  * [Git Accounts](user-guide/global-configurations/git-accounts.md)
  * [Container/OCI Registry](user-guide/global-configurations/container-registries.md)
  * [Chart Repositories](user-guide/global-configurations/chart-repo.md)
  * [Custom Charts](user-guide/global-configurations/custom-charts.md)
  * [SSO Login Services](user-guide/global-configurations/sso-login.md)
    * [Example - Okta SSO](user-guide/global-configurations/okta.md)
  * [Authorization](user-guide/global-configurations/authorization/README.md)
    * [User Permissions](user-guide/global-configurations/authorization/user-access.md)
    * [Permission Groups](user-guide/global-configurations/authorization/permission-groups.md)
    * [API Tokens](user-guide/global-configurations/authorization/api-tokens.md)
  * [Notifications](user-guide/global-configurations/manage-notification.md)
  * [External Links](user-guide/global-configurations/external-links.md)
  * [Scoped Variables](user-guide/global-configurations/scoped-variables.md)
  * [Tags Policy](user-guide/global-configurations/tags-policy.md)
* [Devtron Upgrade](setup/upgrade/README.md)
  * [Update Devtron from Devtron UI](setup/upgrade/upgrade-devtron-ui.md)
  * [0.5.x-0.6.x](setup/upgrade/devtron-upgrade-0.5.x-0.6.x.md)
  * [0.4.x-0.5.x](setup/upgrade/devtron-upgrade-0.4.x-0.5.x.md)
  * [0.4.x-0.4.x](setup/upgrade/devtron-upgrade-0.4.x-0.4.x.md)
  * [0.3.x-0.4.x](setup/upgrade/devtron-upgrade-0.3.x-0.4.x.md)
  * [0.3.x-0.3.x](setup/upgrade/devtron-upgrade-0.3.x-0.3.x.md)
  * [0.2.x-0.3.x](setup/upgrade/devtron-upgrade-0.2.x-0.3.x.md)

## Usage

* [Applications](user-guide/applications.md)
  * [Create a New Application](user-guide/create-application.md)
  * [Clone an Existing Application](user-guide/cloning-application.md)
  * [Deploy a Sample Application](user-guide/Deploy-sample-app/nodejs\_app.md)
  * [App Configuration](user-guide/creating-application/README.md)
    * [Git Repository](user-guide/creating-application/git-material.md)
    * [Build Configuration](user-guide/creating-application/docker-build-configuration.md)
    * [Deployment Template](user-guide/creating-application/deployment-template.md)
      * [Deployment](user-guide/creating-application/deployment-template/deployment.md)
      * [Rollout Deployment](user-guide/creating-application/deployment-template/rollout-deployment.md)
      * [Job and Cronjob](user-guide/creating-application/deployment-template/job-and-cronjob.md)
      * [StatefulSets](user-guide/creating-application/deployment-template/statefulset.md)
    * [Workflow Overview](user-guide/creating-application/workflow/README.md)
    * [CI Pipeline](user-guide/creating-application/workflow/ci-pipeline.md)
      * [Pre-Build/Post-Build Stages](user-guide/creating-application/workflow/ci-build-pre-post-plugins.md)
      * [Override Build Configuration](user-guide/creating-application/container-registry-override.md)
    * [CI Pipeline (Legacy)](user-guide/creating-application/workflow/ci-pipeline-legacy.md)
    * [CD Pipeline](user-guide/creating-application/workflow/cd-pipeline.md)
    * [Config Maps](user-guide/creating-application/config-maps.md)
    * [Secrets](user-guide/creating-application/secrets.md)
      * [External Secret Operator (ESO)](user-guide/creating-application/eso/README.md)
        * [AWS Secrets Manager](user-guide/creating-application/eso/aws-eso.md)
        * [Google Secrets Manager](user-guide/creating-application/eso/gcp-eso.md)
        * [HashiCorp Vault](user-guide/creating-application/eso/hashicorp-eso.md)
    * [Protect Configuration](user-guide/creating-application/config-approval.md)
    * [Environment Overrides](user-guide/creating-application/environment-overrides.md)
    * [Deleting Application](user-guide/deleting-application.md)
  * [Build and Deploy](user-guide/deploying-application/README.md)
    * [Triggering CI](user-guide/deploying-application/triggering-ci.md)
    * [Triggering CD](user-guide/deploying-application/triggering-cd.md)
    * [Rollback Deployment](user-guide/deploying-application/rollback-deployment.md)
  * [App Details](user-guide/creating-application/app-details.md)
    * [Debugging Deployment And Monitoring](user-guide/debugging-deployment-and-monitoring.md)
    * [Using Ephemeral Containers](user-guide/app-details/ephemeral-containers.md)
    * [Application Metrics](user-guide/creating-application/app-metrics.md) 
  * [Overview](user-guide/creating-application/overview.md)
* [Jobs](user-guide/jobs/README.md)
  * [Create a new job](user-guide/jobs/create-job.md)
  * [Configurations](user-guide/jobs/configuration-job.md)
  * [Workflow Editor](user-guide/jobs/workflow-editor-job.md)
  * [Trigger Job](user-guide/jobs/triggering-job.md)
  * [Overview](user-guide/jobs/overview-job.md) 
* [Resource Browser](user-guide/resource-browser.md)   
* [Charts](user-guide/deploy-chart/README.md)
  * [Charts Overview](user-guide/deploy-chart/overview-of-charts.md)
  * [Deploy & Observe](user-guide/deploy-chart/deployment-of-charts.md)
  * [Examples](user-guide/deploy-chart/examples/README.md)
    * [Deploying Mysql Helm Chart](user-guide/deploy-chart/examples/deploying-mysql-helm-chart.md)
    * [Deploying MongoDB Helm Chart](user-guide/deploy-chart/examples/deploying-mongodb-helm-chart.md)
  * [Chart Group](user-guide/deploy-chart/chart-group.md)
* [Security](user-guide/security-features.md)
* [Clusters](user-guide/clusters.md)
* [Bulk Edit](user-guide/bulk-update.md)
* [Integrations](user-guide/integrations/README.md)
  * [Build and Deploy (CI/CD)](user-guide/integrations/build-and-deploy-ci-cd.md)
  * [GitOps (Argo CD)](user-guide/integrations/argocd.md)
  * [Vulnerability Scanning (Clair)](user-guide/integrations/clair.md)
  * [Notifications](user-guide/integrations/notifications.md)
  * [Monitoring (Grafana)](user-guide/integrations/grafana.md)


## Resources

* [Glossary](reference/glossary.md)
* [Troubleshooting](FAQs/devtron-troubleshoot.md)
* [Use Cases](user-guide/use-cases/README.md)
  * [Devtron Generic Helm Chart To Run CronJob Or One Time Job](user-guide/use-cases/devtron-generic-helm-chart-to-run-cron-job-or-one-time-job.md)
  * [Connect SpringBoot with Mysql Database](user-guide/use-cases/connect-springboot-with-mysql-database.md)
  * [Connect Expressjs With Mongodb Database](user-guide/use-cases/connect-expressjs-with-mongodb-database.md)
  * [Connect Django With Mysql Database](user-guide/use-cases/connect-django-with-mysql-database.md)
  * [Pull Helm Charts from OCI Registry](user-guide/use-cases/oci-pull.md)
* [Telemetry Overview](user-guide/telemetry.md)
* [Devtron on Graviton](reference/graviton.md)
* [Release Notes](https://github.com/devtron-labs/devtron/releases)