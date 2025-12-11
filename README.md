# SETechAssessment

Cloud Native Security encompasses many, many things these days. We do not expect anyone to be an expert in everything--that is impossible! Rather, we look for key traits:

**GRIT** - We are a scale-up. It's fun, challenging, and demanding. GRIT is the number one trait we look for when finding someone who we believe will be successful, contributing to a world class organization.  Learn more about GRIT: https://angeladuckworth.com/grit-book/

**Creativity** - Successful individuals are those that think outside the box. They are willing to question the norms and speak up about their thoughts and ideas in an effort to make everyone better.

**Coachable** - We want people who want to be better, learn from their peers, and educate them selves. This space evolves fast, we must evolve with it.

**Mentors** - In order to be successful we have to mentor each other. Again, this space is vast, no one person can know it all. We expect everyone to contribute their knowledge back to their peers. Some people will be more knowledgeable in some areas, that's not only great, it's expected. You need to be willing to coach your peers to raise everybody up.

**Cultural Contribution** - We have a lot of fun, everyone supports each other and lifts each other up, and we work hard to help everyone be as successful as they can be. Many of us come from different backgrounds and we're stronger for that. We don't tolerate negative behaviour and we encourage collaboration and team ethic. This isn't just about technical knowledge, but also professional experiences.

# The Project

To get a handle on who you are, what your drive is, and how we can best support your success, we have a few asks.. Get as far as you can, and be honest with yourself about how much time you have. We're happy to give you more if you need it, just communicate with us when you're ready! At a high level, we'd like you to attempt the following:

1. Create Managed Kubernetes cluster in your cloud provider of choice - Do this however you want (AWS/EKS, Azure/AKS, GCP/GKE - Lots of free 'credit' options out there.)
    - (Note: A node with 4cpu and 8 gigs of ram should be fine to run the Sysdig agent on with the below voting app)
    - If you're building in the cloud, and you're new to the cloud, learn about security and billing alerts!
    - Turn off or scale down your cluster when you're not using it, but **don't destroy it!**
3. Request a Sysdig Trial, from your hiring team.
4. Connect your cloud account to Sysdig using the onboarding Wizard (https://docs.sysdig.com/en/sysdig-secure/integrations-sysdig-agents/)
5. Install the Sysdig Shields to your Kubernetes cluster. Once again, we suggest using the onboarding Wizard.(https://docs.sysdig.com/en/sysdig-secure/integrations-sysdig-agents/)
6. Install the classic *voting app* into your K8s cluster (https://github.com/dockersamples/example-voting-app). Try to expose the app so you can browse to the UI and see it working
7. Get Creative and build some stuff in Sysdig.
    - Analyze the vulnerability scan results of the images being used for the Voting App
    - Compliance? Setup a Zone for your App & repo. Configure a benchmark to run. Review the results and understand which reccomendation can be used to fix the findings
    - Enable the Runtime Threat Detection Policies, including the medium severity ones, and generate some events. Then investigate what detected and play around with process tree, activity audit and everything you find interesting to reposnd to threats or triage the event?
8. Prepare a short demo around the findings you have discovered. Put the focus on how the the platform can be used and integrated into potential client processes and workflows. So, don't destroy your cluster! We'd like to look at it with you.

# Additional Resources

By no means are we saying you need to do these things. These are resources you might find helpful to learn about K8s and the Cloud Native world.

**Sysdig - Learn Cloud Native** - https://sysdig.com/learn-cloud-native/

**Sysdig Docs** - https://docs.sysdig.com/

**Kube Academy** - https://kube.academy/

**Intro to Kubernetes** - https://acloudguru.com/course/introduction-to-kubernetes
