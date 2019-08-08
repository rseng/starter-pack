# Planning

After you have created a [proposal](https://docs.google.com/document/d/17CCeAc-I7GzbUDrSCvYWVPi-k4AyyVhP5oivjgTNNaQ/edit?usp=sharing) The first thing that you should do is to establish project objectives around it:

 - What do you want to accomplish?
 - What is the time frame for your goals?
 - Is there support from your institution that can help?

As an example, when I was developing [rse-services](https://stanford-rc.github.io/rse-services)
I started with the proposal, and then created a set of goals around it. It was easy to turn
general ideas and goals into tangible content that I wanted to write or provide. 
Below is an example of some of the specific project objectives developed,
all of which are integrated into the portal. Feel free to use any, all, or none
for inspiration.


## Project Objectives

This is a plan for how we will move forward with pursuing Research Software Engineering as a Service at `<your institution>`.

### Protocol for Interaction

> The protocol for interaction is your plan for how you (ideally) would want interactions with your group and researchers to go. It's easy to describe first in bulleted list, and then put into your portal.
 
The following describes the typical interaction that we will pursue between research groups or individuals and RSE-Services

 - **Contact**: It could be that we engage labs directly, or someone finds the portal. This step is an initial inquiry from the potential client to the RSE. It might be in the form of an email, and should go back and forth until the RSE has some understanding of the client needs.
 - **Consult**: After an initial contact, the RSE should have a meeting (virtual likely if remote) to discuss details about the project. During this meeting the RSE should get a good understanding of goals, work already done, and work to be completed.
 - **Support Plan**: The RSE then develops a support plan to share with the individual or group. Importantly, the first month is always a trial period for both parties, and if work continues, there is a monthly check-in to ensure that the project is continuing well. If the project is not making progress, it can be paused at the decision of the RSE until changes are made.
 - **Completion**: At completion of the project, a summary of work is written, and the final project showcased on the rse-services site.

> It's fairly straight forward! You'll engage with users, have consults to understand their needs, write a support plan, and then share and come to some agreement. The details for finances are up to your institution - but typically it comes down to paying some percentage of a salary for a period of time, an hourly rate, or a la carte. In fact, how you do this should be part of your plan. For the support plan, you should draft a template that you can easily re-use that reminds you of the content to include after a consult. [Here](https://docs.google.com/document/d/1xCKV8CbTt6cLhUpJPdF97pb9IZPcovt2AbaDQkQuMwU/edit?usp=sharing) is an example.


### Service Portal

> The service portal should be where all of information you've assembled above (your interaction, services, and other fun tools) are accessed by researchers.

The service portal at https://stanford-rc.github.io/rse-services should have:

 - a complete summary of general services [[example](https://stanford-rc.github.io/rse-services/docs/services/)]
 - Interactive tool to select services [[example](https://stanford-rc.github.io/rse-services/docs/tools/services-explorer/)]
 - A protocol for interaction (consult, statement of work, agreement). [[example](https://stanford-rc.github.io/rse-services/docs/getting-started#how-does-it-work)]
 - A "blueprint" graphic that lays out the steps for interaction [[example](https://stanford-rc.github.io/rse-services/docs/getting-started#5-completion)]
 - A tool for a researcher to evaluate the reproducibility of their software [[example](https://stanford-rc.github.io/rse-services/docs/tools/software-checklist/)]


> You can tell that along with providing content, I tried to make it a little fun! The software checklist is a badge generator, and the interactive tools and graphics make the portal more interesting. Along with listing services and these tools, I also wound up adding simple guides for [best practices](https://stanford-rc.github.io/rse-services/docs/guides/best-practices/).

### Community Interaction

> You need to establish clear steps for how you plan to interact with your community. The following are examples of such steps:

#### Call for Proposals

This is most definitely the most fun initiative! You might want to reach out to department heads and PIs and
announce your group, and a first call for proposals. The proposals might come from labs or individuals, and would
be a short paragraph to scope out a project for an RSE. You can get more details (if needed), select a top number that your group can provide, and get to work! The general steps to do this would be:

 - Identify departments across your institution
 - Identify PIs in each department
 - Prepare an email correspondence asking about software projects, and request a short (two paragraph) proposal. The proposal can come from anyone in the lab (graduate students, postdocs, other staff, the PI).
 - Arrange 30 minute consults with each PI (might include more than one project). For this step it will be important for the RSE, for each project, to:
   - Identify previously existing attempts or code
   - Help the PI to establish goals and timeframe, if not stated

Essentially, the RSE should be able to fill out most of the points in the Support Template.
After these meetings, you can review potential projects, code, and based on feasibility, impact, and interest, and select projects to work on. Keep all records of previous proposals to engage with labs for future work.


_Details worked on by [@cosden](https://www.github.com/cosden) and [@vsoch](https://www.github.com/vsoch)._


#### Engage via HPC Jobs

This suggestion comes from [Ian Cosden](https://www.github.com/cosden). If you have experience with high performance computing (HPC) you can find users via their jobs. You can establish a method for finding inefficient jobs (e.g., [seff](https://github.com/SchedMD/slurm/blob/master/contribs/seff/seff) and then reach out and offer to help. You should approach kindly, and with a no strings attached offer to briefly meet with them to discuss the code. Ideally they might share their code (with assurance it will not be shared by you) and give you some time to optimize it. A small engagement of this
manner is a great first step for creating awareness for your service.

#### Reach out Directly

It might be tempting to first engage with the largest labs, but on the contrary, the users that will need you
the most probably don't have an in house software engineer. You might consider looking across lab websites,
and reaching out to labs to offer help. If you find labs with in house staff, you could also reach out to see if
they need any help. For example, you might take a look at their software, and suggest that you could help with adding
tests or containerization. When you do this, share your website, along with tools that they can use on their own
to access the sustainability of their software.

#### Long term Hiring

Once relationships are established, you likely will fall naturally into conversation about longer term
hiring of RSEs to provide support for particular departments. It might be the case that the institution
can partner with individual departments to split the salary of an RSE or group of RSEs. In this case, in order to help find a good
match and ensure the best use of institutional funds, suggested steps from [@cosden](https://www.github.com/cosden) include:

 - Finding potential department partners via a letter of interest
 - Meeting with them and our group
 - 2-3 page proposal (or similar)
 - Review by some external institutional committee


### Promotion

For all of the above, you need to promote your group! Have a plan in place for keeping a record
of work and projects completed, and sharing with the broader community.

Next, read about creating a [portal](portal.md) to share what you've established.
