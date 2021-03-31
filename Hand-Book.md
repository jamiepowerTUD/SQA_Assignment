# (1) Task Estimation In Scrum
![Task Estimation](images/taskestimation.png)<br>
<br>
Task estimation is an essential part of any scrum process. Team members must estimate
the duration and effort of each user story in the sprint backlog using a shared task list. Denise Canty 
outlines the benefit of task estimation on her [blog](https://www.projectmanagement.com/blog-post/46054/Task-Estimation-with-Scrum#:~:text=The%20most%20commonly%20used%20Scrum,backlog%20item%20to%20similar%20items.&text=Story%20points%20do%20not%20measure,a%20user%20story%20or%20task.):
>This practice results in a shared team perspective, resulting in a task estimation process that
is consistent and reliable throughout all Sprints.


## Best Practices

- **Decide the value of a story point and stick to it.**
<br>
  Story points do not have a set value, so it's up to the scrum team to decide on that value and 
  be consistent throughout the project. For example, if the value of a story point has been assigned 1 day,
  then a task which is assigned 3 story points would amount to 3 days of work. This allows for a clear
  understanding of relative levels of effort for a task compared to other tasks. <br>


- **Decompose Tasks**
  ![Decomposing Tasks](images/decompisition.jpg)
  <br>
  
  The task list contains all task that need to be completed in order to complete the user stories. Larger, high level tasks should be broken down 
  into smaller tasks with improved detail, which will allow the team to create product deliverables from the task list items. However, ensure that 
  you are prioritising the most important items to decompose. 
  As Mark Layton says in his [article on scrum decompisition](https://www.dummies.com/careers/project-management/scrum-decomposition-definitions/):
  > A requirement must earn the right of your investment. Only the highest priority items deserve your time in breaking them down into digestible requirements. Everything else can wait. This way, you are always only working on the most important things.
  

-  **Outline Task Dependencies**
  Once user stories are chosen, staff and technical dependencies should then be considered. By properly documenting
  these dependencies, the scrum team can determine the order in which to execute tasks. There are several types of dependencies, 
  including mandatory and discretionary, internal and external, or a combination of these. SCRUMstudy provide some good examples 
  in their [scrum dependency blog](http://blog.scrumstudy.com/dependency-determination-in-scrum-project/) to help understand 
  these dependencies, which will be shown below.

  **Mandatory**: This dependency can be a result of physical limitations, also known as "hard logic", or perhaps contractual 
  obligations and legal requirements that must be met. 
  >For example, work on the first floor cannot begin until the foundation of the building is complete.

  **Discretionary**: Discretionary dependencies are ones which are put in place by the scrum team by choice. They are usually 
  implemented due to prior experiences or accepted best practices, but are not necessarily required. 
  >For example, the team may choose to build the door and window frames before the full structure of the wall is in place.
  
  **External**: External dependencies are outside the scope of the scrum team, yet are necessary for the completion of the 
  project task. This could be certain tasks, activities or products that are outside of the team's control. 
  >For example, if the Scrum Team is not responsible for procuring the materials required for building the walls, then 
those materials and tasks related to their procurement are considered external dependencies.
  
  **Internal**: Finally, internal dependencies are task, activities or products that are within the scope and control of the 
  scrum team. They are basically part of the project work that must be completed. 
  >For example, installing drywall must be completed before painting the wall can begin.


***
***

#### Estimation Techniques<br>
Using story points as measures relative to effort levels allows teams to estimate work they must complete simultaneously.
Scrum being part of agile, uses a top down process and normally pushes teams to propose an estimate of long and how much effort is required for a task to be complete. There are a number of ways in which teams estimate the time and effort required 5 of which are the following: 

- **Planning Poker**
<br>
	- Uses story points to estimate a tasks difficulty based on the fibonacci sequence ( 0,1,2,3,5,8,13,20,40 and 100) with each number representing a different level of complexity. 
 	Team members use numbered cards to vote for an estimate of a task. Voting continues until all are agreed upon and unanimous after discussion. It is open to interpretation among teams 	so  many minor variations of the procedures are conducted depedning on the team or organisation. 

	* Pros 
	Good Technique to use when your team numbers are small and where there are 10 or less items to vote on
	Considered to be popular in the industry
	
	* Cons
	Not good for use with large teams and where the number of tasks to be estimated are high in numbers
 	

- **Sizing (T - shirt)**
<br>
	- Uses sizes as story points for the size of tasks. Gives a quick and rough estimate for how much work is expected and the sizes can be converted into numerical values at later stages. Decisions made through discussion amongst the team. 
	
	* Pros 
	Good for larger number of tasks
	
	* Cons 
	Open to interpretation of individuals, some tasks may seem greater for others and can lead to confusion and in worst cases conflict. 

- **Dot Voting**
<br>
	- Each team member gets a small number of "dots"  and uses them to estimate the size of a task, more dots means more time and effort.
	
	* Pros 
	Very efficient for small teams
	Very good visualisation tool 
	
	*Cons 
	Not necessarily an estimation techniqie, regarded more so as a decision making tool. 

- **Bucket System**
<br>
	- Uses the same structure of planning poker, groups or teams place tasks in "buckets" after confirming with others. A divide and conquer phase is present after asssingning taks to buckets. Buckets can be changed and rearranged if necessary. 
	
	* Pros
	Faster than Planning Poker due to the divide and conquer phase 
	Can be used with larger groups and with larger numbers of tasks
	
	* Cons 
	Not useful for small teams 
	Open to interpretation by individuals 
	

- **Affinity Mapping**
<br>
	-  Tasks are grouped by effort similarity, this can be easy, medium, hard etc. Team members place tasks with their relative perceived effort level or size. These can be changed as the process continues and discuss as they go. Once teams are finished editing they can finalize the product backlog items in their positions. 
	
	* Pros
	Good for smaller teams 
	
	*Cons 
	Bad choice if you have a large number of backlog items

<br>

##### Pros and Cons of Estimating techniques 

Story points are abstract estimates open to interpretation, usually inaccurate and not precise allowing a greater level of flexibility. As opposed to directly placing a specified value of time on a task where one team or individual can be held to a time frame whether its an estimate or not. 
Estimating addresses external communication problems and management outside the team of expectations placed on them. 
Estimating increases the likelihood of a project finishing at a time they say they will. 

However story points can lead to much confusion. Not every understands their value or what they may be interpreted as or how to use them properly. Lack of understanding and training is often the cause. Teams can often take a longer time to work out estimates as team members may be on different skill levels or understandings of certain tasks or effort levels required. Can be highly methodical, time consuming if not done efficiently and disgruntly team members if misunderstandings or disputes occur over estimations. 

 

# (2) Code Standards 

![Gitflow](images/Coding-Standards.jpg)

By definition coding standards are a set of practices and guidelines that determine the style 
and procedure of a specific programming language or project. These standards offer a uniformity and 
structure to massive code bases which have many developers collaborating on them with various different 
styles and habit's. 

***Why should you use code standards?*** 
<br>

Code standards offer many benefits to a team such as 

1. Improves readability while also reducing complexity <br>
		- methods can be unreadable and become difficult to maintain
	
2. Prevents the unnecessary reusing of code as well as highlights errors <br>
		- Reduces redundancy and simplifies error catching
3. Encourages positive integration of teams <br>
		- Allows team members to follow and collaborate on one anothers work
4. Reduce the overall cost of development 

5. Offers accountability of work and ensure correctness of code 

<br>
coding standards offer tried and testing benefits to organisations 
and team's who utilise them, but the efficacy of these practices relies 
heavily on how the standards are embedded and what aspects of the 
project are considered important enough to follow procedure.


### Implementation

![Gitflow](images/tabs_vs_spaces.jpg)

How standards should be enforced is an important decision, things as 
major as class names and project structure as well as comment style all
have potential to be standardized. An example of some common practices are

* Ensuring functions do not exceed a certain size
* Indentation Styles (Tabs vs. Spaces)
* Ensure all filenames are the same format
* Control the access and scope of certain variables
* Efficiency versus Complexity
* Error handling procedure

These standards not only allow individuals to work more efficiently in a
group setting, but it also encourages an environment of excellence to which
people shrive to achieve. Code standards improve the 


***Negatives of not utilising code standards*** 
<br>

A coding standard  makes sure developers are following guidelines on projects. 
Without the implementation of standards the project can be considered to be missing the essential attributes necessary in software development. Without standards the particular work in progress can lack style, structure and have a mixture of procedures involved that will affect the consistency and have an overall negative impact on the quality of a program.
For most organisations, smooth functioning programs are vital for growth. Coding standards are needed for development success. 
<br>

Without standards projects may encounter some of the following **problems** 
 
* Developers can all have different styles and ways of doing things making team work more challenging and hard to follow
* Can become hard to enforce as procedures must be created in order to follow standards if they are implemented at a later stage, meaning code refactoring of projects/programs and change in code creation. 
* Certain standards may not be suitable for use on different languages, allowing programs to be written with incorrect syntax/semantics.
* Enforcing standards may be difficult to enforce in large teams and can be very time consuming.
* Less accountability for work in teams.
* Security concerns can be raised if code is inconsistent, logically incorrect or contain bugs.
* Can cause performance issues due to poor code quality with no standards to correct the issue.
* Difficulty in reading code for anyone as naming conventions and indentation may not be adhered to.

<br>

**Summary - Pros and Cons of standards**

_Positives_
<br>

	* Code Quality
	* Efficiency
	* Accountability
	* Error handling 
	* Reduced Complexity 
	* Simplified Maintenance 
	* Cost Efficiency 
	
_Negatives_
<br> 

	* Security
	* Inconsistency 
	* Can become costly 
	* Risk in performance 
	* Legibility
	* Difficulty in error handling and complexity 
	
**Sources**
<br>
* [coursehero](https://www.coursehero.com/file/p15us6sn/Advantages-of-following-coding-standard-and-disadvantages-of-not-following-it/)
* [answers](https://www.answers.com/Q/What_are_the_advantage_and_disadvantage_of_coding_standards)
* [codingstandards](https://www.slideshare.net/ifourakash/coding-standards-and-best-practices-36493912)
* [multidots](https://www.multidots.com/importance-of-code-quality-and-coding-standard-in-software-development/)
* [mountaingoatsoftware](https://www.mountaingoatsoftware.com/blog/why-agile-teams-should-estimate-at-two-different-levels)
* [reqtest](https://reqtest.com/agile-blog/agile-estimation-techniques/)
* [berteig](https://berteig.com/how-to-apply-agile/9-agile-estimation-techniques/)
* [quora](https://www.quora.com/In-sprint-planning-what-are-the-pros-and-cons-of-using-story-points-hours-or-both-when-creating-estimates)


