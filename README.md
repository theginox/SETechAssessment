# SETechAssessment

Cloud Native Security encompasses many, many things these days. We do not expect anyone to be an expert in everything-that is impossible! Instead, we look for key traits:

**GRIT** - We are a scale-up. It's fun, challenging, and demanding. GRIT is the number one trait we look for when finding someone we believe will be successful and contribute to a world-class organization.

**Creativity** - Successful individuals think outside the box. They are willing to question norms and speak up with their thoughts and ideas to make everyone better.

**Coachable** - We want people who want to be better, learn from their peers, and educate themselves. This space evolves fast; we must evolve with it.

**Mentors** - To be successful, we have to mentor each other. Again, this space is vast; no one person can know it all. We expect everyone to contribute their knowledge back to their peers. Some people will be more knowledgeable in some areas; that's not only great, but it's also expected. You need to be willing to coach your peers.

**Cultural Contribution** - We have a lot of fun, support each other, and work hard to help everyone be as successful as they can be. Many of us come from different backgrounds, and we're stronger for that. We don't tolerate negative behaviour, and we encourage collaboration and team ethic. This isn't just about technical knowledge, but also professional experience.

# The Project

To get a handle on who you are, what your drive is, and how we can best support your success, we have a few asks.. Get as far as you can, and be honest with yourself about how much time you have. We're happy to give you more if you need it. Communicate with us when you're ready! The objective is not about performing a perfect or complex setup. The goal is to understand how comfortable you are with cloud-native technologies, how you think, how you communicate security concepts, and how effectively you would guide a customer through Sysdig’s value.

## 1 - Prepare the prerequisites
- Create a Managed Kubernetes cluster in your cloud provider of choice - Do this however you want (AWS/EKS, Azure/AKS, GCP/GKE - Lots of free 'credit' options out there.)
    - (Note: A node with 4CPU and 8GB of RAM should be fine to run the Sysdig agent on with the below voting app)
    - If you're building in the cloud, and you're new to the cloud, learn about billing alerts!
    - Turn off or scale down your cluster when you're not using it, but **don't destroy it!**
- Install the classic *voting app* into your K8s cluster (https://github.com/dockersamples/example-voting-app)
- Request a Sysdig Trial from your hiring team.

## 2 - Integrate the Sysdig Components:
- Connect your cloud account to Sysdig using the onboarding Wizard (https://docs.sysdig.com/en/sysdig-secure/integrations-cloud-accounts/)
- Install the Sysdig Shields in your Kubernetes cluster. Once again, we suggest using the onboarding Wizard (https://docs.sysdig.com/en/sysdig-secure/integrations-sysdig-agents/)

## 3 - Prepare a short demo track (core part of the assessment)
- Explore the platform and build a small demo track that highlights what you find most interesting or relevant from a security perspective. Here are some examples:
    - Review the vulnerability scan results and identify what stands out: critical findings, base image issues, trends. Explain how you would prioritize fixes for a customer and what trade-offs you would highlight.
    - Create a Zone for your application and configure a compliance policy. Explore the results and understand which recommendations could improve the application's security posture.
    - Enable the Runtime Threat Detection Policies, including medium severity, and try to generate some events in the cluster. Then, investigate what was detected and explore the process tree, activity audit, and everything you find relevant to triage and respond to threats.
- Prepare a short demo (15–20 minutes) where you walk us through:
    - What you discovered
    - Why these findings matter
    - How would you explain the value to a customer
    - How an organization can enahnce security workflows and proccesses using Sysdig
    
Important: Do not destroy your cluster or delete components: we want to walk through your findings together.

## Additional Resources

By no means are we saying you need to do these things. These are resources you might find helpful to learn about K8s and the Cloud Native world.

- **Sysdig - Learn Cloud Native** - https://sysdig.com/learn-cloud-native/
- **Sysdig Docs** - https://docs.sysdig.com/en/docs/sysdig-secure/
- **Kube Academy** - https://kube.academy/
- **Intro to Kubernetes** - https://acloudguru.com/course/introduction-to-kubernetes
