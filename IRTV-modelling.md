# IRTV - modelling

# Scaffolding

## Role Modelling  

<details><summary>To build the scaffolding model ....</summary>
To build the scaffolding model, the IRTV dimensions should be pursued in parallel. For communi- cation with end users, however, we have found it useful to start with the Role models. Coming top down, the high level roles and positions in the organization is generally well known, and the roles constitute a suitable starting point for further analysis into which tasks each role is responsible for, and the most important information they provide or use. By simply identifying and listing the roles, we liberate these concepts from the organizational hierarchies that they are most often seen as part of. By focusing on the responsibilities of the roles in terms of tasks and information content, we direct the analysis towards work practices, rather than administrative reporting or human re- source management structures. Often, though, we find it useful to capture simple classification among role concepts, and the main communication relationships between roles. The details of how these relationships are handled, later become part of the information, task, and view models.  
Implicit modeling techniques such as just grouping related roles together, or placing them in lay- ers according to their decision making authority, are often useful triggers of discussions at this stage.
The benefit of this approach is that the users are first exposed to modeling in a domain and as- pect they are rather familiar with. Although simplistic, the analysis and discussions triggered by role modeling often leads to identifying critical issues, such as poor communication barriers and differences in focus and perspectives among the actors.  
The example below shows a typical role model at the scaffolding stage. No explicit relationships have been captured yet, but the roles are placed near other roles that they work with. Horizontal- ly, the roles are roughly placed according to where in the product and project lifecycle they are mostly involved, and vertically, we find officers and boards at the top, managers in between, and the people performing the work further down. This simple analysis led to the identification of an imbalance between the product organization to the right and the project organization to the left. The project organization has no counterpart to the “produktutviklingssjef” (product development manager) role. There is a need for the missing role, which for instance could be called “market manager”, in that nobody currently were in charge of a systematized collection and prioritization of market knowledge such as requirements and trends.

---

</details>

## Task Modeling  

<details><summary>At the scaffolding stage ....</summary>
At the scaffolding stage, the task models should identify the main activities performed in the do- main of study, for instance the phases of product lifecycles. Though some break-down of tasks into subtasks may be warranted, this is not the place to perform a full hierarchical process design. Typically, you should capture the two or three main tasks of the key actor roles identified above. The responsibility and participation relationships between roles and tasks should also be cap- tured.  
A very high level example is depicted below. In this case, the scope of study was defined as the “Capital value process”. According to the quality control project handbook of the customer com- pany, this process consists of five phases. Each phase ends in a decision gate, which determines whether the process should be continued into the next phase, as well as the major direction to follow. Each phase follows the same pattern, with five major sub-phases (initiation, planning etc.). In addition, the concrete tasks were classified by type (project integration, control, technology im- plementation etc.). For each type of task, a different set of roles are involved.  
This analysis shows some of the limitations of conventional business process modeling, and it is not a good example of how multi-dimensional task analysis should be performed. The process hierarchy emphasizes administrative issues such as decision gates, common global structures, and a strict sequence of activities rather than concurrent and collaborative engineering. The core parts of the work, the creation of designs that solves problems, the analysis of costs, safety, quality, risks and others factors that aid decision making, are buried several levels down in the hierarchy.

---

The multi-dimensional IRTV approach dictates that you should look at tasks in connection with the information content being used and produced. This guides the analysis towards the concrete tasks where the core design work is performed, where the key information is produced. By using roles as analysis lenses, we ask which tasks are the most important one for each participant.
Another way of approaching the task dimension, is to start with the critical design issues, the key questions that need to be settled in the process, e.g. “What kind of subsea equipment is needed for this oil field?”, “What price should we propose in this contract bid?” An example of a set of such design issues, and their main interdependencies, is presented below. In addition to the well structured tree of sub-issues, we find four generic concerns that must be addressed (capacity, competence, PR, legal issues). Starting from such elements, we next need to ask “which informa- tion is needed for settling these issues (populating the information model), and which roles are in charge of settling the issues (correcting the role model).

---

</details>

## Information Modeling  


</details>
<details><summary>The aim of information scaffolding  ...</summary>
The aim of information scaffolding is to identify the main information content of the domain, not to design language metamodels, glossaries, or structured ontologies. Therefore, we typically use a simple language for representing the information content, capturing the main elements, their most important relationships and properties.
We suggest focusing on the product information, and related structures such as customer re- quirements and engineering knowledge, because this most often constitutes the core knowledge of the company. Processes and organizational aspects should already be covered by task and role models to the presently needed degree. In general, however, depending on the domain, all the dimensions of the other knowledge spaces may constitute relevant objects for information modeling.
The example below shows a simple information model, identifying some core concepts and their interdependencies. Not only does this model cover different entities of information, different as- pects and forms of information are also represented, such as “assumptions” and “arguments”.

## View Modeling  
When we get closer to the level of detail needed for configuring an operational solution, view models will take a center stage in the development effort. Views capture what information and services a user filling a roles needs in order to perform some tasks. Compared to the other di- mensions, views capture the to-be-solution to a greater extent than the as-is problem situation  

In the scaffolding phase, views offer the developers an opening to be a bit more inventive. Scaf- folding view models can be applied for testing ideas with respect to what kind of solution the user will find valuable. Views can also be used for capturing structures that cut across the dominant information areas, such as cost, risk, safety, etc. In the example below, several such cross- cutting aspects were grouped around the central collection of information, the business case, re- flecting the users’ statements that “basically, it all ends up in economics”. Such view models can be used for challenging users’ perspectives, and for ensuring that critical aspects have not been overlooked, e.g. in the information and task models.

---

</details>

---

# Scenario Modeling

## Task Modeling  
<details><summary>The next step is to refine the models ....</summary>
The next step is to refine the models for these tasks, representing subtasks and their interdepen- dencies. In this case, a conventional process modeling notation, such as BPM or IDEF, may be applied, as in the modeling of the Visual Solutions Development process:

Figure:

Note however that with AKM’s task management approach, there is no need to completely struc- ture the process, connecting every task into a sequence. If there is no absolute dependency be- tween the tasks, it is often better to give the users some freedom to choose in which order they want to perform the tasks, and to which degree they want to work on multiple tasks in parallel. Sometimes a tree structure such as a work breakdown hierarchy is therefore just as good a de- piction of the processes. Below, we have combined a tree structure with some sequencing.


---

</details>


## Information modeling

<details><summary>....</summary>

Above, we saw that task modeling plays an important role in defining scenarios. Existing metho- dologies such as UML, with their use case diagrams that capture roles and tasks, also follow this approach. Like UML, we also advocate the use of textual scenario descriptions to complement the visual models at this stage.
We must however not forget the other dimensions of the knowledge space. Alongside the task models, an information model should be developed that define the content of the information ap- plied in the tasks. Typically, existing documents is a useful source of inputs to the information model. By representing the information and task dimensions in parallel, we also ensure that no task which produces or uses critical information is forgotten.
An example information model is depicted below. It shows the main elements, and some of the more detailed content associated with each element. There are also relationships between the tasks above and the information elements, indicating production and usage of information.


---

</details>

## Defining Views for Scenario Tasks  

<details><summary>To complete the scenario models ....</summary>
To complete the scenario models, we take the joint information/task modeling one step further, by introducing the view concept. While information modeling aims to capture the overall information structures of the problem area, view modeling tries to identify exactly what information the roles need for performing a given task. In scenario modeling, information and views should be worked out in parallel.
Scenario views define what information should be available in the workplace of a given role when (s)he is performing a certain task. Depending on the case, we may decide to make view models for detailed, low level tasks, or for more high level situations, such as the involvement of a certain role in a given phase or process.
These issues and questions may help in capturing relevant views:
• As-is work practices
– Which information do they process?
– Which information do they send to others?
– Which information do they receive from others?
– Which information do they own?
– How much do they see of the work of others and the discussion in other engi- neering disciplines?
– In which areas do they propose new solutions?
• To-be work practices
– Identify needs and opportunities for improved knowledge sharing and interdiscip- linary collaboration
The example below shows one role view, defining which elements are worked on in the task “As- sess business case”, performed by the “Project controls” role.

In a complete and detailed scenario, we should combine information, role, task, and view model- ing. Such a model can be organized in different ways, depending on what we want to achieve. The first example defines role views as vertical swim-lanes, and follows the succession of tasks in the process downwards. The vertical axis then reflects the passing of time, indicating the relative start time and duration of each task, with concurrent tasks placed at the same horizontal line. When we open up each view, the information content is shown, like in the examples above. In addition to communication dependencies captures by the inclusion of the same information ele- ments in multiple views, the dominant communication links have been represented as relation- ships between the views for each task within the role swim-lanes.
We commonly use a red color to highlight items of concern. In this case, the feedback from the later phase “process view” to the early phase “business development view” indicates a potential source of rework and delay.


---

</details>
