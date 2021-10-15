English
Contact Us
Get started for free
Google Cloud Platform Services Summary

The complete list of services that form Google Cloud Platform is shown below. While Google offers many other services and APIs, only the services below are covered by the Google Cloud Platform terms of service, service level agreements (if applicable), and support offerings. Offerings identified below as Software or Premium Software are not Services under the Google Cloud Platform Terms of Service and the Data Processing and Security Terms.

Services marked in *asterisks* are not available for resale under the Google Cloud Partner Advantage program, unless specifically authorized in writing by Google.

Compute

App Engine: App Engine enables you to build and host applications on the same systems that power Google applications. App Engine offers fast development and deployment; simple administration, with no need to worry about hardware, patches or backups; and effortless scalability.

Compute Engine: Compute Engine offers scalable and flexible virtual machine computing capabilities in the cloud, with options to utilize certain CPUs, GPUs, or Cloud TPUs. You can use Compute Engine to solve large-scale processing and analytic problems on Google's computing, storage, and networking infrastructure.

Google Cloud VMware Engine (GCVE) is a managed VMware-as-a-Service that is specifically designed for running VMware workloads on Google Cloud Platform. GCVE enables customers to run VMware virtual machines natively in a dedicated, private, software-defined data center.

Storage

Cloud Storage: Cloud Storage is a RESTful service for storing and accessing your data on Google's infrastructure. The service combines the performance and scalability of Google's cloud with advanced security and sharing capabilities.

Persistent Disk is durable and high performance block storage for Google Cloud Platform. Persistent Disk provides SSD and HDD storage that can be attached to instances running in either Compute Engine or Google Kubernetes Engine.

Cloud Filestore: Cloud Filestore is a scalable and highly available shared file service fully-managed by Google. Cloud Filestore provides persistent storage ideal for shared workloads. It is best suited for enterprise applications requiring persistent, durable, shared storage which is accessed by NFS or requires a POSIX compliant file system.

*Cloud Storage for Firebase: Cloud Storage for Firebase adds customizable Google security (via Firebase Security Rules for Cloud Storage) to file uploads and downloads for your Firebase apps, as well as robust uploads and downloads regardless of network quality through the Firebase SDK. Cloud Storage for Firebase is backed by Cloud Storage, a service for storing and accessing your data on Google's infrastructure.

Databases

Cloud Bigtable: Cloud Bigtable is a fast, fully-managed, highly-scalable NoSQL database service. It is designed for the collection and retention of data from 1TB to hundreds of PB.

Datastore: Datastore is a fully-managed, schemaless, non-relational datastore. It provides a rich set of query capabilities, supports atomic transactions, and automatically scales up and down in response to load. It can scale to support an application with 1,000 users or 10 million users with no code changes.

Firestore: Firestore is a NoSQL document database for storing, syncing, and querying data for mobile and web apps. Its client libraries provide live synchronization and offline support, while its security features and integrations with Firebase and Google Cloud Platform accelerate building serverless apps.

Memorystore: Memorystore, which includes Memorystore for Redis and Memorystore for Memcached, provides a fully-managed in-memory data store service that allows customers to deploy distributed caches that provide sub-millisecond data access.

Cloud Spanner: Cloud Spanner is a fully-managed, mission-critical relational database service. It is designed to provide a scalable online transaction processing (OLTP) database with high availability and strong consistency at global scale.

Cloud SQL: Cloud SQL is a web service that allows you to create, configure, and use relational databases that live in Google's cloud. It is a fully-managed service that maintains, manages, and administers your databases, allowing you to focus on your applications and services.

Networking

Cloud CDN: Cloud CDN uses Google's globally distributed edge points of presence to cache HTTP(S) load balanced content close to your users.

Cloud DNS: Cloud DNS is a high performance, resilient, global, fully-managed DNS service that provides a RESTful API to publish and manage DNS records for your applications and services.

Cloud IDS (Cloud Intrusion Detection System): Cloud IDS is a managed service that aids in detecting certain malware, spyware, command-and-control attacks, and other network-based threats.

Cloud Interconnect: Cloud Interconnect offers enterprise-grade connections to Google Cloud Platform using Google Services for Dedicated Interconnect, Partner Interconnect and Cloud VPN. This solution allows you to directly connect your on-premises network to your Virtual Private Cloud.

Cloud Load Balancing: Cloud Load Balancing provides scaling, high availability, and traffic management for your internet-facing and private applications.

Cloud NAT (Network Address Translation): Cloud NAT enables instances in a private network to communicate with the internet.

Cloud Router: Cloud Router enables dynamic Border Gateway Protocol (BGP) route updates between your VPC network and your non-Google network.

Cloud VPN: Cloud VPN allows you to connect to your Virtual Private Cloud (VPC) network from your existing network, such as your on-premises network, another VPC network, or another cloud provider's network, through an IPsec connection using (i) Classic VPN, which supports dynamic (BGP) routing or static routing (route-based or policy-based), or (ii) HA (high-availability) VPN, which supports dynamic routing with a simplified redundancy setup, separate failure domains for the gateway interfaces, and a higher service level objective.

Google Cloud Armor: Google Cloud Armor offers a policy framework and rules language for customizing access to internet-facing applications and deploying defenses against denial of service attacks as well as targeted application attacks. Components of Google Cloud Armor include: L3/L4 volumetric DDos Protection, preconfigured web-application firewall (WAF) rules, and custom rules language.

Google Cloud Armor Managed Protection Plus is a managed application protection service subscription that bundles Google Cloud Armor WAF and DDoS Protection with additional services and capabilities including DDoS response support, DDoS bill protection, and Google Cloud Armor Adaptive Protection, which is Google’s machine-learning based solution to protect internet-facing endpoints from network and application-based attacks.

Network Connectivity Center (Preview): Network Connectivity Center is a hub-and-spoke model for network connectivity management in Google Cloud that facilitates connecting a customer's resources to its cloud network.

Network Intelligence Center: Network Intelligence Center is Google Cloud’s comprehensive network monitoring, verification, and optimization platform across the Google Cloud, multi-cloud, and on-prem environments.

Network Service Tiers: Network Service Tiers enable you to select different quality networks (tiers) for outbound traffic to the internet: the Standard Tier primarily utilizes third party transit providers while the Premium Tier leverages Google's private backbone and peering surface for egress.

Service Directory is a managed service that offers customers a single place to publish, discover and connect their services in a consistent way, regardless of their environment. Service Directory supports services in Google Cloud, multi-cloud, and on-prem environments and can scale up to thousands of services and endpoints for a single project.

Traffic Director: Traffic Director is Google Cloud Platform's traffic management service for open service meshes.

Virtual Private Cloud: Virtual Private Cloud provides a private network topology with IP allocation, routing, and network firewall policies to create a secure environment for your deployments.

Operations

Cloud Debugger: Cloud Debugger connects your application's production data to your source code by inspecting the state of your application at any code location in production without stopping or slowing down your requests.

Cloud Logging: Cloud Logging is a fully-managed service that performs at scale and can ingest application and system log data, as well as custom log data from thousands of VMs and containers. Cloud Logging allows you to analyze and export selected logs to long-term storage in real time. Cloud Logging includes the Error Reporting feature, which analyzes and aggregates the errors in your cloud applications and notifies you when new errors are detected.

Cloud Monitoring: Cloud Monitoring provides visibility into the performance, uptime, and overall health of cloud-powered applications. Cloud Monitoring collects metrics, events, and metadata from certain Services, hosted uptime probes, application instrumentation, alert management, notifications and a variety of common application components.

Cloud Profiler: Cloud Profiler provides continuous profiling of resource consumption in your production applications, helping you identify and eliminate potential performance issues.

Cloud Trace: Cloud Trace provides latency sampling and reporting for App Engine, including per-URL statistics and latency distributions.

Developer Tools

Artifact Registry: Artifact Registry is a service for managing container images and packages. It is integrated with Google Cloud tooling and runtimes and comes with support for native artifact protocols. This makes it simple to integrate it with your CI/CD tooling to set up automated pipelines.

Cloud SDK: Cloud SDK is a set of tools to manage resources and applications hosted on Google Cloud Platform. It includes the gcloud, gsutil, and bq command line tools. The gcloud command-line tool provides the primary command-line interface to Google Cloud Platform.

Container Registry: Container Registry is a private Docker image storage system on Google Cloud Platform. The registry can be accessed through an HTTPS endpoint, so you can pull images from your machine, whether it's a Compute Engine instance or your own hardware.

Cloud Build: Cloud Build is a service that executes your builds on Google Cloud Platform infrastructure. Cloud Build can import source code from Cloud Storage, Cloud Source Repositories, GitHub, or Bitbucket; execute a build to your specifications; and produce artifacts such as Docker containers or Java archives.

Cloud Source Repositories: Cloud Source Repositories provides Git version control to support collaborative development of any application or service, including those that run on App Engine and Compute Engine.

*Firebase Test Lab: Firebase Test Lab lets you test your mobile app using your test code or automatically on a wide variety of devices and device configurations hosted in a Google data center, with test results made available in the Firebase console.

Test Lab: Test Lab enables you to test mobile applications using physical and virtual devices in the cloud. It runs instrumentation tests and script-less robotic tests on a matrix of device configurations, and reports detailed results to help improve the quality of your mobile app.

Data Analytics

BigQuery: BigQuery is a fully-managed data analysis service that enables businesses to analyze Big Data. It features highly scalable data storage that accommodates up to hundreds of terabytes, the ability to perform ad hoc queries on multi-terabyte datasets, and the ability to share data insights via the web.

Cloud Composer: Cloud Composer is a managed workflow orchestration service that can be used to author, schedule, and monitor pipelines that span across clouds and on-premises data centers. Cloud Composer allows you to use Apache Airflow without the hassle of creating and managing complex Airflow infrastructure.

Cloud Data Fusion: Cloud Data Fusion is a fully-managed, cloud native, enterprise data integration service for quickly building and managing data pipelines. Cloud Data Fusion provides a graphical interface to help increase time efficiency and reduce complexity and allows business users, developers, and data scientists to easily and reliably build scalable data integration solutions to cleanse, prepare, blend, transfer, and transform data without having to wrestle with infrastructure.

Cloud Life Sciences (formerly Google Genomics) provides services and tools for managing, processing, and transforming life sciences data.

Data Catalog: Data Catalog is a fully-managed and scalable metadata management service that empowers organizations to quickly discover, manage, and understand their data in Google Cloud. It offers a central data catalog across certain Google Cloud Services that allows organizations to have a unified view of their data assets.

Dataflow: Dataflow is a fully-managed service for strongly consistent, parallel data-processing pipelines. It provides an SDK for Java with composable primitives for building data-processing pipelines for batch or continuous processing. This service manages the life cycle of Compute Engine resources of the processing pipeline(s). It also provides a monitoring user interface for understanding pipeline health.

Datalab: Datalab is an interactive tool for exploration, transformation, analysis and visualization of your data on Google Cloud Platform. It runs in your cloud project and enables you to write code to use other Big Data and storage services using a rich set of Google-authored and third party libraries.

Dataproc: Dataproc is a fast, easy to use, managed Spark and Hadoop service for distributed data processing. It provides management, integration, and development tools for unlocking the power of rich open source data processing tools. With Dataproc, you can create Spark/Hadoop clusters sized for your workloads precisely when you need them.

Dataproc Metastore: Dataproc Metastore provides a fully-managed metastore service that simplifies technical metadata management and is based on a fully-featured Apache Hive metastore. Dataproc Metastore can be used as a metadata storage service component for data lakes built on open source processing frameworks like Apache Hadoop, Apache Spark, Apache Hive, Presto, and others.

Pub/Sub: Pub/Sub is designed to provide reliable, many-to-many, asynchronous messaging between applications. Publisher applications can send messages to a "topic" and other applications can subscribe to that topic to receive the messages. By decoupling senders and receivers, Pub/Sub allows developers to communicate between independently written applications.

AI and Machine Learning

AI Building Blocks

AutoML: AutoML is a machine learning product suite that enables developers with limited machine learning expertise to provide their data sets and obtain access to quality trained models produced by Google's transfer learning and Neural Architecture Search (Google's technology for finding, generating, evaluating, and training numerous neural architectures to automatically select a solution for the customer's application):

AutoML Natural Language: AutoML Natural Language enables customers to categorize input text into their own custom defined labels (supervised classification). Users can customize models to their own domain or use case.

AutoML Tables: AutoML Tables enables your entire team of data scientists, analysts, and developers to automatically build and deploy state-of-the-art machine learning models on structured data at increased speed and scale.

AutoML Translation: AutoML Translation is a simple and scalable translation solution that allows businesses and developers with limited machine learning expertise to customize the Google Neural Machine Translation (GNMT) model for their own domain or use-case.

AutoML Video: AutoML Video is a simple and flexible machine learning service that lets businesses and developers easily train custom and scalable video models for their own domain or use cases.

AutoML Vision: AutoML Vision is a simple and flexible machine learning service that lets businesses and developers with limited machine learning expertise train custom and scalable vision models for their own use cases.

Recommendations AI: Recommendations AI enables you to build an end-to-end personalized recommendation system based on state-of-the-art deep learning ML models, without a need for expertise in ML or recommendation system architecture.

Cloud Natural Language API: Cloud Natural Language API provides powerful natural language understanding as an easy to use API. This API enables application developers to answer the following questions: 1) What are the entities referred to in the block of text?; 2) What is the sentiment (positive or negative) for this block of text?; 3) What is the language of this block of text?; and 4) What is the syntax for this block of text (including parts of speech and dependency trees)? Users can call this API by passing in a block of text or by referring to a document in Cloud Storage.

Cloud Translation (including Cloud Translation v2 or any subsequent general availability version/release): Cloud Translation is a RESTful API that automatically translates text from one language to another language (e.g. French to English). You can use the API to programmatically translate text in your webpages or apps.

Cloud Vision: Cloud Vision enables developers to understand the content of an image by encapsulating powerful machine learning models in an easy to use API. It quickly classifies images into thousands of categories (e.g., "sailboat", "lion", "Eiffel Tower"), detects individual objects and faces within images, and finds and reads printed words contained within images. You can build metadata on your image catalog, moderate offensive content, or enable new marketing scenarios through image sentiment analysis. You can also analyze images uploaded in the request and integrate with your image storage on Cloud Storage.

Contact Center AI (CCAI): CCAI is a solution for improving the customer experience in your contact centers using AI. CCAI encompasses Dialogflow Essentials, Dialogflow Customer Experience Edition (CX), Speech-to-Text, and Text-to-Speech.

Dialogflow Essentials: Dialogflow is a development suite for voice and text conversational apps including chatbots and voicebots. Dialogflow is cross-platform and can connect to your own apps (on the web, Android, iOS, and IoT) or existing platforms (e.g., Telephony platforms like Genesys, Avaya, Cisco and digital platforms like Actions on Google, Facebook Messenger, Slack). Dialogflow Essentials Edition is a paid enterprise tier of Dialogflow provided under the Google Cloud Platform Terms of Service. (The free tier of Dialogflow (Dialogflow Trial Edition) is not offered via the Google Cloud Platform Terms of Service and is instead provided under the Dialogflow Trial Edition Terms of Service).

Dialogflow Customer Experience Edition (CX): Dialogflow CX is an advanced development suite for creating conversational AI applications including chatbots and voicebots. It includes a visual bot building platform, collaboration and versioning tools, bot modularization tools, advanced IVR feature support (like DTMF, barge-in, etc.), and is optimized for enterprise scale and complexity. Dialogflow CX is cross-platform and can connect to your own apps (on the web, Android, iOS, and IoT) or existing platforms (e.g., telephony platforms like Genesys, Avaya, Cisco and digital platforms). Dialogflow CX is provided under the Google Cloud Platform Terms of Service.

Document AI: Document AI classifies and extracts structured data from documents to help discover insights and automate business processes.

Human-in-the-Loop AI : Human-in-the-Loop AI provides a user interface and workflow tools for human verification of data extracted from documents using Document AI.

Media Translation API: Media Translation API is a gRPC API that automatically translates audio from one language to another language (e.g., French to English) and supports streaming real time. You can use the API to programmatically translate audio in your apps.

Speech-to-Text: Speech-to-Text allows developers to convert audio to text by applying powerful neural network models in an easy to use API.

Text-to-Speech: Text-to-Speech synthesizes human-like speech based on input text in a variety of voices and languages.

Video Intelligence API: Video Intelligence API makes videos searchable, and discoverable, by extracting metadata with an easy to use REST API. It quickly annotates videos stored in Cloud Storage, and helps you identify key noun entities of your video and when they occur within the video.

Vertex AI, AI Platform, and Accelerators

AI Platform Data Labeling: AI Platform Data Labeling is a service that helps developers obtain high quality data to train and evaluate their machine learning models. It supports labeling for image, video, text, and audio as well as management of all of your labeled data in one place.

AI Platform Deep Learning Container: AI Platform Deep Learning Container is a Docker image with the most popular AI frameworks. Machine learning developers and data scientists can customize AI Platform Deep Learning Container and use it with Notebooks, Google Kubernetes Engine (GKE), Vertex AI, Cloud Run, Compute Engine, Kubernetes, and Docker Swarm.

AI Platform Neural Architecture Search (NAS): NAS is a managed service leveraging Google's neural architecture search technology to generate, evaluate, and train numerous model architectures for a customer's application. NAS training services facilitate management of large-scale experiments.

AI Platform Training and Prediction: AI Platform Training and Prediction is a managed service that enables you to easily build and use machine learning models. It provides scalable training and prediction services that work on large scale datasets.

Notebooks: Notebooks is a managed service that offers an integrated JupyterLab environment in which machine learning developers and data scientists can create instances running JupyterLab that come pre-installed with the latest data science and machine learning frameworks in a single click.

Vertex AI: Vertex AI is a service for managing the entire lifecycle of AI and machine learning development. With Vertex AI, you can (i) manage image, video, text, and tabular datasets and associated labels, (ii) build machine learning pipelines to train and evaluate models using Google Cloud algorithms or custom training code, and (iii) deploy models for online or batch use cases all on scalable managed infrastructure (including additional discovery points and API endpoints for functionality replacing the legacy services of AI Platform Data Labeling, AI Platform Training and Prediction, AutoML Natural Language, AutoML Video, AutoML Vision, and AutoML Tables).

Industry Solutions

Talent Solution: Talent Solution offers access to Google's machine learning, enabling company career sites, job boards, ATS, staffing agencies, and other recruitment technology platforms to improve the talent acquisition experience.

Retail Search: Retail Search, powered by Google’s Retail API, allows retailers to leverage Google’s search capabilities on their own retail websites and mobile applications. With Retail Search, retailers receive fast, accurate, and high quality search results that help improve conversion and increase customer engagement.

API Management

*Apigee is a full-lifecycle API management platform that lets customers design, secure, analyze, and scale APIs, giving them visibility and control. Apigee is available as Apigee, a fully-managed service, Apigee hybrid, a hybrid model that's partially hosted and managed by the customer, or Apigee Private Cloud, an entirely customer hosted Premium Software solution.

API Gateway is a fully-managed service that helps you develop, deploy, and secure your APIs running on Google Cloud Platform.

Cloud Endpoints: Cloud Endpoints is a tool that helps you to develop, deploy, secure and monitor your APIs running on Google Cloud Platform.

Hybrid and Multi-cloud

Anthos: Anthos is a solution designed for building and managing modern applications running across hybrid cloud environments. Anthos is an integrated platform incorporating cloud-based services and software components, including:

Anthos Config Management: Anthos Config Management is a policy management solution for enabling consistent configuration across multiple Kubernetes clusters. Anthos Config Management allows you to specify one single source of truth and then enforce those policies on your cluster.
Anthos Identity Service: Anthos Identity Service is an authentication service that lets customers bring existing identity solutions for authentication to multiple Anthos environments. Users can log in to and access their Anthos clusters from the command line or from the Cloud Console, all using their existing identity providers.
Anthos Integration with Google Cloud Platform Services: Google Cloud Platform services and components may be used in connection with Anthos deployments, including Google Kubernetes Engine (GKE), Cloud Logging, Cloud Monitoring, Traffic Director, and Google Cloud Platform Marketplace.
Anthos Premium Software: Anthos includes the software components listed below as Premium Software.
Anthos Service Mesh:This is a managed service mesh service that includes (i) a managed certificate authority that issues cryptographic certificates that identify customer workloads within the Anthos Service Mesh for mutual authentication, and (ii) telemetry for customers to manage and monitor their services. Customers receive details showing an inventory of services, can understand their service dependencies, and receive metrics for monitoring their services. For clarity this service does not include Anthos Service Mesh -- Software (see below regarding Premium Software).
Google Kubernetes Engine: Google Kubernetes Engine, powered by the open source container scheduler Kubernetes, enables you to run containers on Google Cloud Platform. Kubernetes Engine takes care of provisioning and maintaining the underlying virtual machine cluster, scaling your application, and operational logistics such as logging, monitoring, and cluster health management.
Connect: Connect is a service that enables both users and Google-hosted components to interact with clusters through a connection to the in-cluster Connect software agent.
Hub: Hub is centralized control-plane that enables a user to register clusters running in a variety of environments, including Google’s cloud, on premises in customer datacenters, or other third party clouds. Hub provides a way for customers to centrally manage features and services on customer-registered clusters.

Cloud Run for Anthos: Cloud Run for Anthos on Google Cloud lets you run stateless containers on Anthos.

Google-Managed Multi-Cloud Services

BigQuery Omni: BigQuery Omni is a Google-managed multi-cloud analytics solution that enables analysts to access and analyze data stored on other supported public clouds from a singular BigQuery control-plane on GCP.

Bare Metal

Bare Metal Solution: Bare Metal Solution allows you to operate and manage dedicated bare metal hardware (servers and attached storage) in Google's subprocessors' data centers to run specialized workloads with low latency.

Migration

BigQuery Data Transfer Service automates data movement from SaaS applications to BigQuery on a scheduled, managed basis. With the BigQuery Data Transfer Service, you can transfer data to BigQuery from SaaS applications including Google Ads, Campaign Manager, Google Ad Manager, and YouTube.

Database Migration Service: Database Migration Service is a fully-managed migration service that makes it simple to perform high fidelity, minimal-downtime migrations at scale. You can use Database Migration Service to migrate from your on-premises environments, Compute Engine, and other clouds to certain Google Cloud-managed databases with minimal downtime.

Migrate for Compute Engine V5.0 and up is a fully-managed migration service that enables you to migrate workloads at scale into Google Cloud Compute Engine with minimal down time by utilizing replication-based migration technology.

Storage Transfer Service enables you to import large amounts of online data into Cloud Storage, quickly and cost-effectively. With Storage Transfer Service, you can transfer data from locations reachable by the general internet (e.g., HTTP/HTTPS), including Amazon Simple Storage Service (Amazon S3), as well as transfer data between Google Cloud products (e.g., between two Cloud Storage buckets). You can also use Storage Transfer Service to move data between private data center storage (e.g., NFS) and Google Cloud products (e.g., transfer from NFS to Cloud Storage).

Transfer Appliance is a solution that uses hardware appliances and software to transfer large amounts of data quickly and cost-effectively into Google Cloud Platform.

Security and Identity

Security

Access Transparency captures near real-time logs of manual, targeted accesses by Google administrators, and serves them to customers via their Cloud Logging account.

Assured Workloads: Assured Workloads provides functionality to create security controls that are enforced on your cloud environment. These security controls can assist with your compliance requirements (for example, FedRAMP Moderate).

Binary Authorization helps customers ensure that only signed and explicitly-authorized workload artifacts are deployed to their production environments. It offers tools for customers to formalize and codify secure supply chain policies for their organizations.

Certificate Authority Service: Certificate Authority Service is a cloud-hosted certificate issuance service that lets customers issue and manage certificates for their cloud or on-premises workloads. Certificate Authority Service can be used to create certificate authorities using Cloud KMS keys to issue, revoke, and renew subordinate and end-entity certificates.

Cloud Asset Inventory is an inventory of cloud assets with history. It enables users to export cloud resource metadata at a given timestamp or cloud resource metadata history within a time window.

Cloud Data Loss Prevention: Cloud Data Loss Prevention is a fully-managed service designed to help you discover, classify, and protect your most sensitive data. You can inspect, mask, and de-identify sensitive data like personally identifiable information (PII).

Cloud External Key Manager (Cloud EKM): Cloud EKM lets you encrypt data in Google Cloud Platform with encryption keys that are stored and managed in a third-party key management system deployed outside Google's infrastructure.

Cloud HSM: Cloud HSM (Hardware Security Module) is a cloud-hosted key management service that lets you protect encryption keys and perform cryptographic operations within a managed HSM service. You can generate, use, rotate, and destroy various symmetric and asymmetric keys.

Cloud Key Management Service: Cloud Key Management Service is a cloud-hosted key management service that lets you manage cryptographic keys for your cloud services the same way you do on premises. You can generate, use, rotate, and destroy AES256, RSA 2048, RSA 3072, RSA 4096, EC P256, and EC P384 cryptographic keys.

Event Threat Detection helps detect threats in log data. Threat findings are written to Security Command Center and optionally to Cloud Logging.

Key Access Justifications (KAJ): KAJ provides a justification for every request sent through Cloud EKM for an encryption key that permits data to change state from at-rest to in-use.

Risk Manager allows customers to scan their cloud environments and generate reports around their compliance with industry-standard security best practices, including CIS benchmarks. Customers then have the ability to share these reports with insurance providers and brokers.

Security Command Center: Security Command Center is Google Cloud’s centralized vulnerability and threat reporting service. Security Command Center provides asset inventory and discovery and allows you to identify misconfigurations, vulnerabilities and threats, helping you to mitigate and remediate risks.

VPC Service Controls: VPC Service Controls provide administrators the ability to configure security perimeters around resources of API based cloud services (such as Cloud Storage, BigQuery, Bigtable) and limit access to authorized VPC networks, thereby mitigating data exfiltration risks.

Secret Manager: Secret Manager provides a secure and convenient method for storing API keys, passwords, certificates, and other sensitive data.

Web Security Scanner is a web application security scanner that enables developers to easily check for a subset of common web application vulnerabilities in websites built on App Engine and Compute Engine.

Identity & Access

Access Approval allows customers to approve eligible manual, targeted accesses by Google administrators to their data or workloads before those accesses happen.

Access Context Manager allows Google Cloud organization administrators to define fine-grained, attribute based access control for projects, apps and resources.

BeyondCorp Enterprise is a solution designed to enable zero-trust application access to enterprise users and protect enterprises from data leakage, malware and phishing attacks. BeyondCorp Enterprise is an integrated platform incorporating cloud-based services and software components, including:

On-premises Connector, which forwards Identity-Aware Proxy traffic from Google Cloud Platform to applications and VMs deployed in non-Google Cloud Platform environments.
Endpoint Verification, which allows administrators to build an inventory of devices and set the security posture of the devices.
Threat and Data Protection Services, which are a set of security services that work by aggregating threat intelligence and are designed to protect enterprise users from malware transfers, phishing, malicious site visits, and sensitive data leakage.
BeyondCorp Enterprise Integration with Chrome Browser Cloud Management, which enables malware, phishing, and data leakage protection for managed Chrome browsers.
Other features listed at https://cloud.google.com/beyondcorp-enterprise/pricing or a successor URL.

Cloud Identity Services are the services and editions as described at: https://cloud.google.com/terms/identity/user-features.html or such other URL as Google may provide.

*Firebase Authentication: Firebase Authentication provides a service as part of the Firebase platform to authenticate and manage users in your applications. It supports authentication using email & password, phone number and popular federated identity providers like Google and Facebook.

Google Cloud Identity-Aware Proxy is a tool that helps control access, based on a user's identity and group membership, to applications running on Google Cloud Platform.

Identity & Access Management (IAM) provides administrators the ability to manage cloud resources centrally by controlling who can take what action on specific resources.

Identity Platform: Identity Platform provides you with functionality and tools to manage your users' identities and access to your applications. Identity Platform supports authentication and management of users with a variety of methods, including email & password, phone number, and popular federated identity providers like Google and Facebook.

Managed Service for Microsoft Active Directory (AD) is a Google Cloud service running Microsoft AD that enables you to deploy, configure and manage cloud-based AD-dependent workloads and applications. It is a fully-managed service that is highly available, applies network firewall rules, and keeps AD servers updated with Operating System patches.

Resource Manager API allows you to programmatically manage Google Cloud Platform container resources (such as Organizations and Projects), that allow you to group and hierarchically organize other Google Cloud Platform resources. This hierarchical organization lets you easily manage common aspects of your resources such as access control and configuration settings.

User Protection Services

reCAPTCHA Enterprise helps detect fraudulent activity on websites.

Web Risk API is a Google Cloud service that lets client applications check URLs against Google's constantly updated lists of unsafe web resources.

Serverless Computing

Cloud Run: Cloud Run (fully-managed) lets you run stateless containers on a fully-managed environment.

Cloud Functions: Cloud Functions is a lightweight, event-based, asynchronous compute solution that allows you to create small, single-purpose functions that respond to cloud events without the need to manage a server or a runtime environment.

*Cloud Functions for Firebase: Cloud Functions for Firebase lets you write code that responds to events and invokes functionality exposed by other Firebase features, once you deploy JavaScript code in a hosted, private, and scalable Node.js environment that requires no maintenance.

Cloud Scheduler is a fully-managed enterprise-grade cron job scheduler. It allows you to schedule virtually any job, including batch, big data jobs, cloud infrastructure operations, and more. You can automate everything, including retries in case of failure to reduce manual toil and intervention. Cloud Scheduler even acts as a single pane of glass, allowing you to manage all your automation tasks from one place.

Cloud Tasks is a fully-managed service that allows you to manage the execution, dispatch, and delivery of a large number of distributed tasks. Using Cloud Tasks, you can perform work asynchronously outside of a user or service-to-service request. Cloud Tasks provides all the benefits of a distributed task queue such as task offloading wherein heavyweight, background and long running processes can be dispatched to a task queue, loose coupling between microservices allowing them to scale independently, and enhanced system reliability as tasks are persisted in storage and retried automatically, making your infrastructure resilient to intermittent failures.

Eventarc: Eventarc is a fully-managed service for eventing on Google Cloud Platform. Eventarc connects various Google Cloud services together, allowing source services (e.g., Cloud Storage) to emit events that are delivered to target services (e.g., Cloud Run or Cloud Functions).

Workflows is a fully-managed service for reliably executing sequences of operations across microservices, Google Cloud services, and HTTP-based APIs.

Internet of Things (IoT)

IoT Core: IoT Core is a fully-managed service that allows you to easily and securely connect, manage, and ingest data from internet connected devices. It permits utilization of other Google Cloud services for collecting, processing, analyzing, and visualizing IoT data in real time.

Management Tools

Cloud Console App is a native mobile app that enables customers to manage key Google Cloud services. It provides monitoring, alerting, and the ability to take actions on resources.

Cloud Deployment Manager is a hosted configuration tool which allows developers and administrators to provision and manage their infrastructure on Google Cloud Platform. It uses a declarative model which allows users to define or change the resources necessary to run their applications and will then provision and manage those resources.

Cloud Shell is a tool that provides command-line access to cloud resources directly from your browser. You can use Cloud Shell to run experiments, execute Cloud SDK commands, manage projects and resources, and do lightweight software development via the built-in web editor.

Recommenders automatically analyze your usage patterns to provide recommendations and insights across services to help you use Google Cloud Platform in a more secure, cost-effective, and efficient manner.

Service Infrastructure: Service Infrastructure is a foundational platform for creating, managing, securing, and consuming APIs and services. It includes:

Service Management API, which lets service producers manage their APIs and services;
Service Consumer Management API, which lets service producers manage their relationships with their service consumers; and
Service Control API, which lets managed services integrate with Service Infrastructure for admission control and telemetry reporting functionality.
Service Usage API, which lets service consumers manage their usage of APIs and services.
Healthcare and Life Sciences

Cloud Healthcare: Cloud Healthcare is a fully-managed service to send, receive, store, query, transform, and analyze healthcare and life sciences data and enable advanced insights and operational workflows using highly scalable and compliance-focused infrastructure.

Media and Gaming

Game Servers: Game Servers is a managed service that enables game developers to deploy and manage their dedicated game servers across multiple Agones clusters around the world through a single interface.

Transcoder API: Transcoder API can batch convert media files into optimized formats to enable streaming across web, mobile, and living room devices. It provides fast, easy to use, large-scale processing of advanced codecs while utilizing Google’s storage, networking, and delivery infrastructure.

Google Cloud Platform Premium Software

Below is a list of available software components subject to the Google Cloud Platform Service Specific Terms as Premium Software.

Anthos: Anthos includes the following Premium Software components:

Anthos core software: Anthos core software enables you to run containers on Kubernetes and can be deployed on premises in your own data center, as well as in both private and public clouds.
Anthos Service Mesh - Software: Anthos Service Mesh is a suite of tools to run a reliable service mesh on Anthos, to help you monitor, manage and secure traffic between the services deployed on Anthos.
Connect Software: Connect Software may be downloaded and installed in clusters to enable connectivity between the customer-registered cluster and Google Cloud.
Cloud Logging and Cloud Monitoring for Anthos: Cloud Logging and Cloud Monitoring can be deployed in a range of hybrid cloud environments to enable centralized log storage, log analysis, metrics capture, metrics trending, customized alerting, and application debug tracing.

*Apigee hybrid runtime: Apigee hybrid runtime enables you to run the Apigee runtime plane in containers on Kubernetes within your data center.

*Apigee Private Cloud: Apigee Private Cloud enables you to host and run Apigee entirely within your data center.

Cloud Vision OCR On-Prem: Cloud Vision OCR On-Prem enables you to run Cloud Vision OCR models within your data center and across multiple cloud environments.

Speech-to-Text On-Prem: Speech-to-Text On-Prem enables you to run Cloud Speech-to-Text models within your data center and across multiple cloud environments.

Google Cloud Platform Software

Below is a non-exclusive list of available software components subject to the Google Cloud Platform Service Specific Terms as Software.

Cloud Run for Anthos deployed on VMware enables you to run stateless containers on VMware.
Config Connector is a Kubernetes add-on that allows you to manage your Google Cloud resources through Kubernetes configuration files.
Kf enables you to migrate and run applications from the open-source Cloud Foundry platform into containers in Google Kubernetes Engine and Anthos.
Migrate for Anthos enables you to migrate and run applications from virtual machines on-premise or other clouds into containers in Google Kubernetes Engine and Anthos, while producing container and data artifacts for integration with modern CI/CD, Anthos and Google Cloud services. Migrated container images and artifacts are portable for use across a variety of Google Kubernetes Engine and Anthos hybrid configurations as listed in the applicable software documentation. With Migrate for Anthos, the need for application rewrite is minimized.
Migrate for Compute Engine v4.X enables you to validate, run, and migrate applications from on-premise or other clouds into Compute Engine while minimizing downtime and application rewrite.
PREVIOUS VERSIONS (Last modified October 8, 2021)
September 13, 2021 August 24, 2021 July 20, 2021 June 22, 2021 May 18, 2021 April 30, 2021 April 14, 2021 April 8, 2021 March 31, 2021 March 2, 2021 February 4, 2021 January 26, 2021 January 6, 2021 November 2, 2020 September 15, 2020 September 1, 2020 August 19, 2020 August 7, 2020 July 27, 2020 July 24, 2020 July 13, 2020 June 30, 2020 June 9, 2020 April 27, 2020 April 22, 2020 April 15, 2020 April 9, 2020 March 31, 2020 March 26, 2020 March 16, 2020 March 11, 2020 February 25, 2020 February 3, 2020 December 12, 2019 December 3, 2019 November 14, 2019 November 4, 2019 October 7, 2019 October 1, 2019 August 21, 2019 June 25, 2019 June 17, 2019 May 31, 2019 May 16, 2019 April 10, 2019 April 9, 2019 March 11, 2019 February 1, 2019 January 2, 2019 December 13, 2018 December 3, 2018 October 7, 2018 September 18, 2018 August 29, 2018 August 16, 2018 August 2, 2018 July 31, 2018 July 24, 2018 July 10, 2018 June 28, 2018 May 18, 2018 May 9, 2018 May 8, 2018 April 13, 2018 March 27, 2018 March 23, 2018 March 21, 2018 February 6, 2018 January 17, 2018 November 16, 2017 November 13, 2017 November 9, 2017 October 3, 2017 September 25, 2017 September 13, 2017 August 30, 2017