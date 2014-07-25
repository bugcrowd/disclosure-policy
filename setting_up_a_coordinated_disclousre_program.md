## Guide to setting up a Coordinated Disclosure Program

**Background** - Coordinated disclosure is the process of inviting security researchers to find and report security issues in your systems. A successful coordinated disclosure program relies on clear, easy to understand, and legally complete  guidelines, backed by an internal process that is equally simple and clear. This document is designed as a best practice guide for preparing and running a successful coordinated disclosure program.
##### 1. Prepare your organization
1. It’s important that senior leadership is aware of the disclosure policy. A high priority security issue handled improperly could damage the reputation of the organization. 
2. The development, IT and communications team are all critical components to a successful program. Make sure they are all aware of your efforts. It’s important to state the benefits clearly to all departments so everyone understands that the program is a measure to help increase the security of the company. 
3. It’s helpful to make the teams mindful of the fact that the researchers are helping them for free, and that the respect they treat them with ought to reflect this.
4. Discuss and formalize your response procedure.
	* Who will be responsible for ensuring a submission is answered?
	* How quickly will you be able to respond?
	* What happens when you get a high priority security issue?

##### 2. Create a public disclosure policy
1. Discuss with your security team what constitutes a security issue, and what areas of your business are off limits to public research. This policy guides interactions between your organization and researchers. 
2. The public page and policy also serves as a way to proactively communicate with researchers who submit feedback through other channels (support@[COMPANY], etc). 
3. Make sure to provide a way to contact you (typically security@[COMPANY] or a form for researchers to submit information)
4. In the policy, give the researchers areas of focus for their testing. Typically this takes the form of a “scope”, such as “.yourcompany.com”. If you find that you’re receiving issues that are out of scope, you can point researchers to this guidance. If your scope guidance is not explicit, researchers will assume they can test everything (*.yourcompany.com). 
5. Make sure to exclude sites and domains that you do not directly control.


##### 3. Publish your policy
Your policy should be made publicly available on a security-focused page on your public website. This page will become a resource for all visitors interested in how you protect their data.  We recommend https://www.[COMPANY].com/security. 

##### 4. Be responsive and communicate clearly
1. Acknowledge initial receipt of any report, and set expectations for a response.
2. Keep the researcher informed during each stage of the validation process. If the bug is not in scope, or otherwise not valid, email the researcher to bring closure to their case. Has the vulnerability been researched and validated? Let them know. Is your team unsure of how to validate the submission? Ask your researcher for clarity on how to duplicate the bug. Researchers want to know when a fix is deployed and remediated, so keep them updated on each stage of the process.
3. Be aware that researchers have expectations about your response time based on previous interaction with organizations. Some researchers will be understanding of a delayed response, some will not. 

##### 5. Be transparent
1. Explain your decisions. Remember that the researcher doesn't understand your business from the same perspective that you do. Be clear about why the issue is or isn't important to you.
2. Conduct your responses as though they're in public view. Researchers will occasionally publish a transcript of your conversations, along with the report of the vulnerability.
3. Keep records. A log of the entire communication history from your side can be helpful if you need to defend your actions.

##### 6. Don’t Panic
1. Don't panic! Receiving your first vulnerability report from the outside world can be a scary and confronting experience, but keep in mind that the researcher is proactively trying to help you.
2. Should the researcher publish the details of the report publicly ahead of time, contact them and ask them to take it down, and remind them of your policy.

##### 7. Acknowledge and credit
1. If it warrants a code or configuration change, reward the researchers with praise, a place on your hall of fame, or a bounty reward. 
2. A Hall of Fame is a page that lists researchers who have contributed valid, unique vulnerabilities to your team, and is a form of recognition that costs your team nothing. Researchers take pride in being listed, so make sure to add contributors when appropriate and properly manage your hall of fame.

##### 8. Fix fast
1. Make sure you resolve the vulnerability quickly. For most researchers, this is the most important part - seeing the positive impact of their work.
