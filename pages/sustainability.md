---
title: Sustainability
layout: home
parent: Principles of Engagement
nav_order: 3
---
# Sustainability

## I. Introduction
This guide is designed to help AVAnnotate stakeholders consider the extent to which AVAnnotate projects are sustainable. The following questions will help stakeholders think through *what* they want to keep, *why,* and *how* to keep it. 
- What does it mean to create contextual material sustainably?
- What happens if a system like AVAnnotate becomes unavailable?
- Can the created context be recuperated elsewhere?
- What is the preservation value of the data we are generating? How important is it for a project to be preserved, e.g. temporary class project versus academic publication?
- What defines the Archival Information Package (AIP) to be preserved?
- What is truly preservable in digital context-heavy projects? 
- How should permissions and responsibilities be distributed? Who makes decisions at each stage of the process?
- What does community involvement look like in the long term?
- How will preservation (of materials, of projects) happen?

## II. Key Aspects of Sustainability in DH
Digital Humanities scholars and practitioners have long considered what it means to create projects that are more ephemeral than books and that may require existing (and updated) platforms and/or interactive components. 

A. Technical Sustainability
- FAIR Principles: Findable, Accessible, Interoperable, Reusable.
- Infrastructure: Ensuring long-term viability of software, platforms, and hardware.
- Interoperability: Must be both machine-readable and human-comprehensible.
- Citability: Persistent citations via IIIF or other frameworks.
  
B. Financial Sustainability
- Funding Models: Need for ongoing support for staff, updates, and platform maintenance.
- Institutional Support: Exploring internal and external funding mechanisms.
 
C. Social Sustainability
- Community Engagement: Involving users in design and maintenance.
- Institutional Adoption: Integrating tools into everyday academic life.
- Outreach: Conference participation, presentations, education initiatives.

D. Content Sustainability
- Preservation Strategies: Metadata creation, archiving, and acknowledgment of contributors.
- Community Contributions: Properly credit or protect sensitive materials.
- Generative Experiences: Allow for multiple interpretations; avoid locking in a single narrative.
  
E. Infrastructure Sustainability
- Governance Structures: Institutional policies, roles, and workflows for DH projects.
- Technical Platforms: Ensuring support for data migration and software longevity.
  
F. Research and Development
- Early Planning: Select data formats, models, and technologies that support sustainability.
- Cross-Disciplinary Collaboration: Research and development that integrates technical and humanistic insights.

## III. Challenges to Sustainability
A. Financial and Institutional Dependencies

Digital humanities projects like AVAnnotate often rely on time-limited grants and institutional goodwill. Without sustained funding streams or a formal hosting model, even well-used platforms risk obsolescence once initial grant funding concludes. Dependence on university-based infrastructure also makes continuity vulnerable to administrative or personnel changes.

B. Technical Obsolescence and Infrastructure Fragility

Open-source software can face significant maintenance challenges as dependencies and browsers evolve. Without consistent developer oversight and regular updates, core functionalities—particularly those involving IIIF standards, GitHub Pages hosting, or Jekyll-based builds—may degrade.

C. Data Preservation and Metadata Integrity

Although AVAnnotate promotes static site export and IIIF manifest reuse, audiovisual data remain large, complex, and prone to loss. Maintaining metadata integrity and ensuring synchronization between annotations, manifests, and preserved audiovisual assets pose ongoing technical and organizational challenges.

D.  Labor and Knowledge Transfer

AVAnnotate depends on a distributed community of contributors. Without structured onboarding, training, or documentation workflows, institutional knowledge can dissipate when project leads or developers leave.

E. Ethical and Legal Stewardship

Ethical sustainability includes ensuring rights, permissions, and community consent remain valid over time. Changes in legal frameworks, institutional policies, or community priorities can challenge the ongoing appropriateness of public access to certain materials.

F. Engagement Fatigue and the 'Maintenance Gap'

Sustainability requires ongoing engagement from both users and institutions. However, enthusiasm often wanes once initial development goals are met, creating a 'maintenance gap' where projects risk stagnation.

## IV. Strategies for Addressing Sustainability Challenges
A. Funding and Resource Strategies
- Develop hybrid funding models combining institutional support, external grants, and in-kind contributions.
- Embed maintenance costs and sustainability planning early in grant applications.
- Establish stewardship partnerships between libraries, Digital Humanities centers, archives, and other project partners and stakeholders to distribute responsibilities.

B. Technical and Preservation Strategies
- Maintain up-to-date public documentation on dependencies and migration paths.
- Emphasize static-site and offline export features for long-term access.
- Encourage institutional repository archiving of IIIF manifests, annotation data, and media surrogates, digital “stand-ins” for original AV items.

C. Community and Labor Sustainability
- Develop train-the-trainer and mentorship models for onboarding new users.
- Acknowledge contributors through visible credit and citation practices.
- Create governance structures or advisory boards to ensure continuity of communication and programming.

D. Ethical and Legal Sustainability
- Institute regular reviews of copyright, access, and consent documentation.
- Engage community archives and stakeholders in long-term access decisions.
- Provide clear workflows for takedown or revision requests as needs evolve.

E. Communication and Outreach
- Promote projects through conferences, workshops, and social media.
- Maintain an open repository of exemplars, templates, and guides.
- Encourage community feedback via GitHub issues, forums, or discussion spaces.

## V. AVAnnotate Projects and Sustainability
A. Social Sustainability
- *Collaborative Partnerships and Institutional* Support AVAnnotate has been built with partners at multiple institutions and organizations, where researchers and professionals have provided resources, expertise, and ongoing support for projects.
  
- *Community Engagement and Outreach* By hosting workshops and trainings, for example, the AVAnntotate team seeks to include the broader community in the software’s development and its dissemination to create a sense of ownership and ensure long-term support. In addition, significant project funds are used to support users creating AVAnnotate projects.

B. Technical Preservation
- *Open-Source Software*
  - AVAnnotate is an open-source tool that uses widely-supported file formats to ensure future accessibility while reducing reliance on proprietary technologies. 
- *Data Formats*
  - AVAnnotate annotations are encoded based on W3C Annotation standards and are embedded in the IIIF manifests for each AVAnnotate event.  They are reusable in future IIIF players that support AV and time-targeted annotations.
  - AV content providers should make AV accessible that is well-cited, ideally with persistent URIs and a citation that would allow findability of the AV asset in the future if that PID is not actually persistent.
- *Website Preservation* 
  - AVAnnotate sites can be published as static sites and downloadable as packages for future viewing. See Creating Offline or Alternative Server Projects. 
  - Creating a video walk-through of the project is one way to preserve the interface, showing what the published project contained and how it worked. 
- *Limitations* 
  - Media files often cannot be preserved directly (e.g., via [Archive-It](https://archive-it.org/)). As it stands, it will be up to the institution to preserve AV, both for the item itself (e.g. digital preservation system) and appropriate references for data (citations and persistent URIs, etc.). 

B. Content Sustainability
- *Provenance Metadata*
  - Human-created annotations should include information about the authors and dates created. Acknowledge scholarship and anonymize contributors as needed. 
  - AI generated content should be cited with the prompt, service (ChatGPT, Claude, etc.), version, and date of generation. They may be uploaded as separate AnnotationSets to make it easy to differentiate in the user interface who (or what) generated them. [MLA has recommendations for citing the use of AI](https://style.mla.org/citing-generative-ai-updated-revised/). 

## VI. Resources on DH and Sustainability
- [The British Academy](https://www.thebritishacademy.ac.uk/documents/4314/JBA-10-p093-Tucker.pdf): Facing the challenge of digital sustainability as humanities
- University of Pittsburgh and Collaborators: [Sustaining DH: An NEH Institute for Advanced Topics in the Digital Humanities](https://sites.haa.pitt.edu/sustainabilityinstitute/#:~:text=The%20ongoing%20sustainability%20of%20digital%20humanities%20projects,archivists%2C%20librarians%2C%20and%20digital%20humanities%20practitioners%20alike.&text=It%20is%20based%20on%20research%20findings%20that,to%20successfully%20sustain%20digital%20work%20over%20time)
- [Royal Academy of Engineering: Building sustainability into research programmes](https://raeng.org.uk/programmes-and-prizes/programmes/international-programmes/frontiers/resource-library/resources-for-researchers/building-sustainability-into-research-programmes#:~:text=Understand%20sustainability&text=human%20sustainability:%20the%20capacity%20of,programme%20with%20a%20local%20environment)
- [Humanities Division: Boost for sustainability of Digital Humanities](https://www.humanities.ox.ac.uk/article/boost-for-sustainability-of-digital-humanities#:~:text=7%20August%202020,digital%20innovation%20and%20open%20scholarship)
- The University of North Carolina at Charlotte: [Digital Humanities: Project Planning - Research Guides](https://guides.library.charlotte.edu/c.php?g=920263&p=8192419#:~:text=sharing%20this%20document.-,Personal%20Digital%20Archiving,programs%20or%20common%20file%20formats)
- Alliance of Digital Humanities Organizations: [Follow the Money?: Funding and Digital Sustainability](https://www.digitalhumanities.org/dhq/vol/17/1/000666/000666.html#:~:text=Strategies%20that%20work%20well%20during,in%20a%20fiscally%20sustainable%20manner)
- [PARADISEC: Sustainable data from digital research](): Humanities perspectives on digital scholarship
- British Library: [Insights from the Digital Humanities Climate Coalition Workshop](https://blogs.bl.uk/digital-scholarship/2024/07/embracing-sustainability-at-the-british-library-insights-from-the-digital-humanities-climate-coaliti.html#:~:text=Discovering%20the%20DHCC%20and%20its%20toolkit&text=The%20DHCC%20toolkit%2C%20in%20particular,tips%20for%20minimising%20ecological%20footprints)
- Alliance of Digital Humanities Organizations DH as Data: [Establishing Greater Access through Sustainability](https://www.digitalhumanities.org/dhq/vol/17/3/000715/000715.html#:~:text=Further%2C%20we%20define%20a%20sustainable,maintain%2C%20and%20preserve%20digital%20projects)
- [Sustainability of Digital Humanities Projects as a Publication and Documentation Problem](https://www.emerald.com/insight/content/doi/10.1108/jd-12-2019-0232/full/html?skipTracking=true#:~:text=Findings%20%E2%80%93%20The%20findings%20of%20the,the%20medium%20to%20long%20terms)
- [Ithaka S+R Sustainability Implementation Toolkit](https://sr.ithaka.org/publications/sustainability-implementation-toolkit/)
- [Visual Media Workshop: Socio-Technical Sustainability Roadmap](https://sites.haa.pitt.edu/sustainabilityroadmap/)
- [Endings Project (University of Victoria): Citability and preservation principles](https://endings.uvic.ca/principles.html)
- [Public Knowledge Project](https://pkp.sfu.ca/about/sustainability/) The importance of community and sustainability in advancing open research, access, advocacy, and infrastructure for scholarly publishing toward the global public good
