---
title: "Security"
date: 2025-02-17
draft: false
sidebar: false
showToc: false
translationKey: "security"
---

The Federal Science DataHub (FSDH) is hosted in Azure Enterprise Cloud. The Azure Enterprise solution is designed specifically for use within the Government of Canada and is designed to address central identity and access management, governance, data security, comprehensive logging, and network design/segmentation per Canadian Centre for Cyber Security ITSG-33 specifications. 

## The Federal Science DataHub (FSDH) practices continuous security 

We embed security specialists on our team and treat security priorities as design constraints. We use automation and metrics to facilitate security operations.  

Recognizing the role of communication in maintaining security, we: 

- Simplify language so non-specialist staff can participate. 
- Require you to read through our Terms & Conditions when signing up. You must also accept the Terms & Conditions each time you sign in. 
- Reduce paperwork to focus on useful and specific documents. 

We use a precise combination of security policies, practices, and products for the FSDH. This combination is referred to as security controls. 

To identify these controls, we considered the FSDH’s need for: 

- **Confidentiality** – Preventing unauthorized access to information. 
- **Integrity** – Preventing changes to or removal of information. 
- **Availability** – Maintaining operations during events such as power outages or natural disasters.  

The FSDH security profile was built and assessed by an independent security assessor based on these needs. The security requirement for the FSDH application is Unclassified Confidentiality, Low Integrity, Low Availability (ULL) security level and is designed to comply with security controls such as Technical Security controls, Operational Security controls and Management Security controls per Canadian Centre for Cyber Security ITSG-33 specifications. ULL is a security profile for the Government of Canada.  

With the use of these controls and other safeguards, the remaining or residual risk of operating the FSDH is acceptable. In 2025, SSC’s Security Management and Governance office granted the FSDH authority to operate (ATO). 

## Use the FSDH for Unclassified data and information 

When you use an FSDH workspace and the tools within it, your organization is responsible for: 

- Assessing context to decide what degree of injury could result from release of information, and 
- Based on your assessment, deciding on the sufficient level of security. If Unclassified or under is not sufficient, do not use the FSDH. 

Providing a more secure solution allowing you to host data classifications up to Protected B is on the roadmap and expected to be delivered in Q4 of the 2025/26 fiscal year. 

## We keep personal information for the duration of the FSDH workspace 

Personal information gathered for the creation and operation of an FSDH workspace will be retained for the duration of the workspace. After a workspace has been deleted, only non-identifying data will be retained for statistical purposes. 

We also dispose of personal information following the Appendix E: Standard on Privacy in Web Analytics of the Directive on Privacy Practices. We never give the information to another service provider, whether public or private. For more information, read the <gcds-link href="/about/privacy" variant="light" class="hydrated">FSDH Privacy Statement</gcds-link>. 

## We control access to information in the FSDH 

The FSDH controls access to information in the cloud. We prevent and detect unauthorized access using automated practices called guardrails.  

We restrict our staff’s access to information based on role and regularly audit access and permissions. We include safeguards to onboard and offboard FSDH staff. 

We also monitor the FSDH to record activity and receive alerts about anything suspicious. 

## We take steps to protect your account 

When you sign in, we send a one-time code to your email or phone. You’ll need to enter the code to finish signing in. 

We use a process called hashing to securely store and verify your password. Hashing ensures that passwords cannot be deciphered or reconstructed, even by FSDH staff. If you forget or lose your password, you’ll have to create a new one. 

If we suspect an account or workspace is compromised, we’ll immediately started the SSC security incident and event mgmt. process. This can include disabling of accounts and isolation of FSDH resources. 

## We prevent, detect, address, and minimize risks 

The enterprise cloud has put an architecture with centralized monitoring of all audit logs created within the enterprise cloud. The resource group employs Azure Monitor service to collect security logs of the platform. Azure Monitor is a comprehensive monitoring service provided by Microsoft Azure that helps you maximize the performance and availability of your applications and infrastructure resources running in Azure. It collects telemetry data from various sources, analyzes this data to provide insights, and enables you to take proactive actions to optimize the performance, identify security issues, and troubleshoot problems effectively.  

Network Monitoring service is also employed in the FSDH platform solution. It provides a set of tools and capabilities to help us monitor and troubleshoot network connectivity, security, and performance issues.  

On the application side, the platform employs Azure Application Insights service as an application performance monitoring (APM) and application analytics service. It enables you to monitor and gain insights into the performance and usage of your applications in real-time.  

Developers conduct manual testing to ensure that the system functions correctly and securely. This hands-on approach involves systematically examining the system's features, functionalities, and security measures to identify and address any potential issues. By manually testing the system, developers can validate its behavior under various scenarios, verify that it meets functional requirements, and detect and mitigate security vulnerabilities. The plan in later stages is to automate these tests and avoid manual testing.  

A vulnerability assessment scan is conducted yearly to ensure the system remains secure.  

## If you suspect a security breach or discover a vulnerability 

Incidents must be reported via telephone to the ESD via the toll-free number 1-855-830-7782. The ESD provides support 24 hours a day, 7 days a week. To determine the severity of the incident (High, Critical), refer to the SSC Priority matrix (Appendix B, C and D - SSC Priority Matrix).  

The minimum information required to log a ticket can be found on the ESD GCPedia site, Shared Services Canada Enterprise Service Desk Service Request and Incident Template. (MS Word Download)  

Additional information regarding the ESD processes may be found on the ESD GCpedia site, Enterprise Service Desk.  

FAQ https://www.gcpedia.gc.ca/wiki/SSC_IM_FAQ 

## You have security responsibilities 

As per the FSDH Terms & Conditions, you have the following security responsibilities: 

- Use a modern, secure web browser.  
- Run an antivirus scan on the data or information files before uploading them to the workspace. If an infected file is detected, it must not be uploaded. 
- Know IT Security directives for password management and protection and agree to the Terms and conditions 
- Ensure access tokens related to storage are managed securely. If any questions arise, contact your departmental security team for advice.  
- Verify the departmental security team has developed and documented:  
   - An incident response policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and  
   - Procedures to facilitate the implementation of the incident response policy and associated incident response controls.  
- Report incidents to the departmental security team as soon as they occur and following the departmental incident reporting process.  
- Ensure all users within a workspace have security awareness training, specifically the following courses:  
   - Security Awareness (COR310) 
   - Discover Cyber Security (DDN235) 
   - Access to Information and Privacy Fundamentals (COR502)  
- Manage database credentials. Database credentials are encrypted in transit and at rest and must be safeguarded. 