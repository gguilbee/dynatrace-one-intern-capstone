# Dynatrace ONE Intern Capstone

Congratulations! It’s time to showcase your skills as a Product Specialist and show your team you’re ready to become an L2 PS. As next steps we will ask you to setup and demo an environment of your choosing to the Dynatrace ONE West Coast team. The goal of this demo is to highlight your technical aptitude by demonstrating the core concepts and feature functionality of the Dynatrace platform and your ability to present value of the Dynatrace platform to customers across multiple business units in a single presentation.

See below for further instructions and expectations of this demo and reach out to your manager with any questions.

1. Mandatory Prerequisites
    - Build your Kubernetes foundation. Choose one of the following introductory courses to study the fundamentals of K8s.
        - [Dynatrace Advanced Galaxy - K8s Learning Path (10 Hours)](https://dynatrace.sharepoint.com/sites/AdvanceGalaxy/SitePages/Kuberneteslearningpath-Mandatorybasics.aspx)
        - [Udemy - K8s for Beginners (6 Hours)](https://dynatrace.udemy.com/course/learn-kubernetes/learn/lecture/9703196#overview)
        - [YouTube - K8s Tutorial for Beginners (4 Hours)](https://www.youtube.com/watch?v=X48VuDVv0do)

1. Sign up for a free Dynatrace SaaS trial 
    - https://www.dynatrace.com/trial/

1. Spin up a Kubernetes Cluster. You can use any cloud provider you’d like, for example, AWS, Azure, GCP, etc. To get access to the Dynatrace Cloud accounts of youre choosing reach out to the [Guardians of the Clouds](https://dev-wiki.dynatrace.org/x/egvmCQ). They have built Slack workflows that help streamline this process. Slack Channel: #help-gotc
    - [How to request AWS / Azure / Alibaba / GCP access?](https://dev-wiki.dynatrace.org/x/CYE4Cw)
    - Dynatrace's AWS Account. Follow the steps below to gain access
        - [New AWS login for employees](https://dynatrace.sharepoint.com/sites/gotc/SitePages/AWS-Console-Login.aspx)
        - [Dynatrace DevOps - AWS Credentials Manager for Developers](https://bitbucket.lab.dynatrace.org/projects/DOPS/repos/com-dynatrace-devops-awscredentialsmanager/browse)
    - Alternatively, you can create your own free tier accounts.  
        - [GCP](https://cloud.google.com/free/docs/gcp-free-tier/#free-trial) 
        - [Azure](https://azure.microsoft.com/en-us/offers/ms-azr-0044p/)
        - [AWS](https://aws.amazon.com/free/)
        
       
1. Deploy the OneAgent Operator to your environment
    - [Kubernetes](https://www.dynatrace.com/support/help/shortlink/full-stack-dto-k8)
    - [OpenShift](https://www.dynatrace.com/support/help/shortlink/full-stack-dto-k8)

1. Deploy a Web Application. You can leverage Dynatrace’s EasyTravel application for this demo
    - <strike>[Easy Travel - Standalone](https://community.dynatrace.com/t5/Getting-started/easyTravel-Documentation-and-Download/td-p/181271)</strike>
    - <strike>[Easy Travel - Docker](https://github.com/Dynatrace/easyTravel-Docker)</strike>
    - [Easy Travel - Kubernetes](https://github.com/gguilbee/easytravel-kubernetes)

1. Alternatively, you can choose to use any other web frontend you have already worked with or built for this demo

    Requirements of the test application if not using Easy Travel
    - Front End browser web component 
    - http service level calls 
    - Backend Database
    - Ideally, the application will be capable of generating errors/ crashes/ outages
    - Check [Dynatrace's list of supported technologies](https://www.dynatrace.com/support/help/technology-support/supported-technologies-and-versions/) for technology compatibility

   Other public web applications:
    - [Kona Kart](https://github.com/BraydenNeale/dynatrace_konakart_docker)
    - [Google's Hipster Shop](https://github.com/lightstep/hipster-shop)
    - [Google's Online Boutique](https://github.com/GoogleCloudPlatform/microservices-demo)

1. External integrations and extensions

    Below we have listed key Dynatrace integrations and extensions that you’ll need to setup and demo in your environment. These are intended to be challenging and highlight/showcase your level of experience and knowledge of the Dynatrace platform. Below is a list of integrations tiered by challenge level of time and technical ability to implement. Dynatrace documentation links are included. Please note, these are only examples. Feel free to review the Dynatrace [How to Use Dynatrace](https://www.dynatrace.com/support/help/how-to-use-dynatrace/networks/) and [Product News](https://www.dynatrace.com/news/blog/) pages and come up with your own integration ideas for you demo.

    Requirements
        
    - [Configure a problem notification systems outbound from Dynatrace, that is NOT email](https://www.dynatrace.com/support/help/shortlink/problem-notifications)
    - [Create a Management Zone](https://www.dynatrace.com/support/help/how-to-use-dynatrace/management-zones/)
    - [Add a Synthetic check to your web application](https://www.dynatrace.com/support/help/how-to-use-dynatrace/synthetic-monitoring/browser-monitors/create-a-single-url-browser-monitor/)
    - [Setup Tagging Rules for your environment](https://www.dynatrace.com/support/help/how-to-use-dynatrace/tags-and-metadata/)
    - [Define User Tags for your application](https://www.dynatrace.com/support/help/shortlink/user-tagging)
    - [Enable Session Replay Capture](https://www.dynatrace.com/support/help/how-to-use-dynatrace/real-user-monitoring/setup-and-configuration/web-applications/additional-configuration/configure-session-replay-for-personal-data-protection/)
    - [Configure Conversion Goals](https://www.dynatrace.com/support/help/how-to-use-dynatrace/real-user-monitoring/how-to-use-real-user-monitoring/web-applications/define-conversion-goals/)
    - [Define Session Properties](https://www.dynatrace.com/support/help/how-to-use-dynatrace/real-user-monitoring/setup-and-configuration/web-applications/additional-configuration/define-user-action-and-session-properties/)
    - [Define Availability & Performance SLO’s](https://www.dynatrace.com/support/help/shortlink/objectives-hub)
    - [Define a Request Attribute for your application](https://www.dynatrace.com/support/help/shortlink/request-attributes)
    - [Create a Log Event & Custom Metric](https://www.dynatrace.com/support/help/shortlink/log-management-and-analytics)
 
    Additional Integration Requirements - Pick 3

    - [Add any metric data point(s) to your environment using Metric Ingestion](https://www.dynatrace.com/support/help/how-to-use-dynatrace/metrics/metric-ingestion/)
    - [Instrument a Python application with OneAgent](https://github.com/dynatrace-oss/OneAgent-SDK-Python-AutoInstrumentation)
    - [Add a Synthetic check to you web app via a *Private* active gate](https://www.dynatrace.com/support/help/how-to-use-dynatrace/synthetic-monitoring/private-synthetic-locations/create-a-private-synthetic-location/)
    - [Use the Events API to add Event data to an entity](https://www.dynatrace.com/support/help/dynatrace-api/environment-api/events/)
    - [Integrate Dynatrace with a Cloud Account](https://www.dynatrace.com/support/help/technology-support/cloud-platforms/)
    - [Integrate your environment with Ansible Tower or AWX](https://www.dynatrace.com/support/help/setup-and-configuration/integrations/third-party-integrations/problem-notification-systems/ansible-tower-integration/)
    - Integrate your environment with [LoadRunner](https://www.dynatrace.com/support/help/setup-and-configuration/integrations/third-party-integrations/test-automation-frameworks/dynatrace-and-loadrunner-integration/), [JMeter](https://www.dynatrace.com/support/help/setup-and-configuration/integrations/third-party-integrations/test-automation-frameworks/dynatrace-and-jmeter-integration/) or [Neotys](https://www.dynatrace.com/support/help/setup-and-configuration/integrations/third-party-integrations/test-automation-frameworks/neotys-integration/)
    - [Leverage the Dynatrace Terraform Provider](https://registry.terraform.io/providers/dynatrace-oss/dynatrace/latest)
    - [Extend OneAgent to instrument a non-native language through the OneAgent SDK](https://www.dynatrace.com/support/help/extend-dynatrace/oneagent-sdk/)
    - [Service Now CMDB](https://www.dynatrace.com/support/help/setup-and-configuration/integrations/third-party-integrations/problem-notification-systems/servicenow-integration/)
    - [Prometheus](https://www.dynatrace.com/support/help/shortlink/extend-prometheus)
    - [Integrate business dashboards to really highlight value](https://dynatrace.github.io/BizOpsConfigurator/)
 

1. Presentation Overview

    Again, your presentation should highlight your technical aptitude and expertise by demonstrating the core concepts and feature functionality of the tool. However, the primary focus of your presentation will be to demonstrate the value of the data provided by Dynatrace to multiple business units, teams and stakeholders for any given organization. For the purposes of this demo Dynatrace’s West Coast PS team will be role playing as stake holders of an existing customer with growth opportunities in the roles of:  
    
    - Technology Operations
    - C Level Management
    - Software Development
    - DevOps
    - SRE
    - Infrastructure Support
    - Business Analytics & Intelligence

    Tailor your presentation to demonstrate how each of these teams’ day-to-day jobs could be easier and drive better business outcomes with the Dynatrace platform. Additionally, be prepared to field live questions from these business units' stakeholders about the Dynatrace platform from their specific lens. 

1. Presentation requirements: 

    - Present a problem card and the related application, user, service and business impact 
    - Build a dashboard that showcases your environment and it's data
    - Explain the value of the [Dynatrace Smartscape](https://www.dynatrace.com/support/help/how-to-use-dynatrace/smartscape/visualize-your-environment-topology-through-smartscape/)
    - Walk through the application service flow you've instrumented with one agent from front end (Real users) to the database calls
    - Highlight 5 data points or features or learned about during setup
    - Explain why these 5 data points are relevant to the audience & business units 
    - Demo the 4 (or more) integrations you setup
    - Present one item from your environment under ["Profiling and Optimization"](https://www.dynatrace.com/support/help/how-to-use-dynatrace/diagnostics/) or ["Multidimensional Analysis"](https://www.dynatrace.com/support/help/how-to-use-dynatrace/diagnostics/)
    - The over arching theme of your presentation should hinge of the business value the above requirements will provide to your prospect

    Additional Notes:

    - Please Ensure that you have enabled [Real User Monitoring (RUM)](https://www.dynatrace.com/support/help/how-to-use-dynatrace/real-user-monitoring/setup-and-configuration/web-applications/initial-configuration/configure-dynatrace-real-user-monitoring-to-capture-xhr-actions/) for you web app
    - Make sure to expose your frontend microservices so they are publicly accessible. *(Hint: Load balancer or Node Port, make sure your load balancer is in the same availability zone as your cluster ;) )*
    - [Take a look at YouTube for Sample Demos](https://www.youtube.com/results?search_query=dynatrace+demo)
    - Have fun!
