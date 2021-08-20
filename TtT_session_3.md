# ELIXIR – EXCELERATE Train-the Trainer subtask

## Session 3: Session, course, and materials design

* [Using Concept Maps to develop courses and sessions;](#conceptmaps)
* [Training session design and plan;](#sessions)
* [Training materials: sharing and making re-use possible;](#design)
    * [Training materials repositories and resources: GOBLET, TeSS, GitHub, etc.](#repositories)
* [Reproducibility of compute environments;](#reproducibility)
* [Training rooms for bioinformatics;](#rooms)

In this session you will learn how to:

- design, prepare, deliver, get feedback, and review (according to feedback) a three-minute presentation;
- design a training session;
- design a training course;
- design and develop training materials;

<a name="conceptmaps"></a>
## Using Concept Maps to develop courses and sessions

**Description**: This sequence describes what are concept maps and how they can be used to design course sessions and courses.

**Keywords**: concept maps, relationships, course design, course sessions

**Learning objective**: Develop an understanding of concept maps, apply concept maps to the development of courses and course sessions
 
**Introduction**

> From Ambrose et al (2010) "How learning works" - Appendix B
> 
> Concept maps are graphical tools for organizing and representing knowledge (Novak and Cañas, 2008, "Theory underlying concept maps and how to construct them"). They are drawn as nodes and links in a network structure in which nodes represent concepts, usually enclosed in circles or boxes, and links represent relationships, usually indicated by lines drawn between two associate nodes. Words on the line, referred to as linking words or linking phrases, specify the relationship between the two concepts. Both your students and you can benefit from the construction of concept maps. You can ask students to draw concept maps to get insight into what they already know and how they represent their knowledge. You can then use that information to direct your teaching. You can also use concept map to design a talk, a lesson, a session or even an entire course..
> 
> The ["Theory underlying concept maps and how to construct them"](http://cmap.ihmc.us/Publications/ResearchPapers/TheoryUnderlyingConceptMaps.pdf) ([PDF](./docs/TheoryUnderlyingConceptMaps.pdf)) by Novak and Cañas is an excellent document to read if you want to know more about concept maps and learn how to construct them.
> 
> We cite from Novak and Cañas:
> 
> The starting point for constructing a concept map can consist of only the focus question. It is important that a question be given (e.g. "What is the structure of the Universe?" and not just a topic (e.g. “make a concept map about the Universe”) since answering the question helps focus on your map. 
> 
>  A second step for the construction of the concept map can be a list of concepts that you want to definitely include in your map. We refer to a list of concepts waiting to be added to a concept map as the parking lot of concepts.
> 
> **The concept map deals with a key concept that needs to be understood as a foundation for learning science. See the following example for the beginning of a concept map with a focus question and a parking lot with concepts to be included in the map:**
> 
> 
> ![focus session and parking lot](fig/concept-map-parking-lot.jpg)
> 
> **An expert skeleton concept map**<br>
> Now see the concept map that was drawn based on the parking lot from the previous figure. Some concepts were left in the parking lot for subsequent addition.
> 
> ![focus session and parking lot](fig/concept-map.jpg)

**References**:  
- Ambrose et al (2010) "How learning works - Seven research-based principles for smart teaching". Jossey-Bass, a Wiley Imprint.
- Novak and Cañas (2008), "Theory underlying concept maps and how to construct them"

**Tools to create concept maps**:
- [bubbl.us](https://bubbl.us/) - (online, collaboratif with login) - Several examples to edit and start with.
- [Gliffy](https://www.gliffy.com/) - (online, collaboratif with login, synchronous) - Several examples to edit and start with.
- [Cmap Tools from Novak](http://cmap.ihmc.us/cmaptools/) - to download (Windows only), individual
- [VUE](http://vue.tufts.edu/) - (visual understanding environment) - to download (work offline), individual

<a name="sessions"></a>
## Training session design and plan

**Description**: This sequence describes the steps to define a coherent session plan.

**Keywords**: course sessions, session design, plan

**Learning objective**: Practice to design and plan a training session 

**Learning outcome**: To reflect on, and to practice the design and planning of a training session 
 
**Introduction**  
Defining a course and course sessions is an iterative and circular process. You start by defining an overall objective related to the concepts and skills you want the learners to develop (see concept maps). These objectives should be as much as possible SMART (Specific, Measurable, Achievable, Realistic, Time-limited). You can then explicit what are the pre-requirements that the learners will need to have a priori and what are the set of skills the training course will provide. You can also define an evaluation that participants would take to prove they have achieved the learning, and what are the concepts/competencies/skills they need to learn to succeed the evaluation. With this information at hand, you can start describing and creating the course session content, the process of the session (instructions), and any materials that would be needed. Bear in mind that this is an iterative process and can be revised several times. 
  


> ### Recipe for planning a mini-session 
>    * Identify the ideal target audience;
>    * Set learning objectives;
>    * Set learning outcomes;
>    * Identify the required prior knowledge;
>    * Draw a concept map of the session's topic;
>    * Expand the learning outcomes into an outline;
>    * Decide how much time to allocate for each activity;
>    * Decide the order of activities;
>    * Try to include at least a warm-up session, a short lecture, a practical or group activity, and a wrap-up.


**Warm-up** <br>
Describe clearly your learning objectives and the expected outcomes. Describe what you are going to teach and how it relates to previous topics (if any).
Warm-ups may include an activity learners carry out. For example, solving an exercise, answering a small questionnaire, or making a prediction game. 

Purpose: activate prior knowledge, prepare the brain to learn, introduce a topic.

**Lecture** <br>
This is where you can transfer content. Have very clear learning objectives. Try to make it as interactive as possible. Consider using a short video, capturing images, appropriate citations, making examples from real life. 

**Practical or group activity**<br>
This could be a hands-on or a tutorial, one or more exercises, an instructional game, any group activity.
Allocate enough time to complete the assignment and be ready to allocate extra time if necessary. 
Show the solution of the exercises, or - even better - ask one or more learners to show it to the class.  

**Wrap-up**<br>
The wrap-up can be used to repeat the main concepts illustrated during the teaching. This should be preferably done by learners. 
It can also be used to assess learning outcomes (for example using a questionnaire with questions similar to the questions of the warm-up questionnaire, or any other test).
In a course wrap-up, you can also assess learners' expectations and collect feedback from them.

Your plan for 1h15 session may look like this:

|Time|Activity|Description|Goal/Outcome|
|------|-------|-----------------------------|----------------|
|9.00-9.15|warm-up|Learners summarise the key points of each session from the previous day and answer questions from the audience. The instructor describes the plan of the day in detail.|Retrieval from memory, repetition, get prepared for new topics, expose learners|
|9.15-9.25|lecture|Python functions|Learning to write a function, about function input and output, and how to call a function.|
|9.20-10.00|practical activity|Two exercises two be solved in pairs on a single computer. After solving the first exercise, the "driver" and the "navigator" will swap. Two learners (one per exercise) will display their solutions to the audience. Questions and discussion.|Learners will be able to write and call a function calculating the distance between two points in the 3D space and a function taking the base and height of a triangle as input and returning its area.|
|10.00-10.15|wrap-up|Group test on functions (match input and output with specific functions; fill gaps in pieces of code). Game: repetition using ball throwing.|Assess learning. Do we need to work more on functions? Repeat meaning and usage of all Python objects introduced so far.|


> ## Challenge

> In your group…
> 
> - Take one session idea and expand to a “real” training session
> - You will need to:
>   - Identify target audience
>   - Define session structure (include indicative content, length, breakdown and timings)
>   - Set learning objectives and outcomes, expand the them to make a session outline
>   - Decide learning activities  
>   - Suggest how you will assess trainee progress
> - Let us know of anything else you will need to think about….

#### Recipe to prepare a new training course

    * Define the main idea (matching a perceived need)
    * Define the Ideal Target Audience
    * Define pre-requisites for the participants
    * Select potential instructors. One of them plays the leader role. Involve him/her in all discussions from this point on.
    * Breakdown into skills and concepts needed
    * for each skill {
        state learning objective(s) and write them down (use SMART learning objectives) 
        consider exercise alternatives 
        gauge duration, technical requirements, testing  
        pick the best suited exercise 
        design a short lecture to precede it   
        adjust timing for an ideal training slot duration 
        prepare self-assessment questions
    }
    * Compose a logical sequence of slots and distribute them in a course plan timetable
    * for each training day {
        program a fist slot / 
        On the fist day, use that slot to break the ice and establish team work discipline / 
        On the other days, use it for the wrap-up of the content of the evening / 
    }
    * Plan a final wrap-up discussion at the end of the course
    * Distribute the time slots through the days of training, using duration to balance the learning effort
    * Use breaks to induce periods of collective reflection
    * Foresee some physical activity, a couple of walks, a deep breathing exercise, for example

<a name="design"></a>
## Training materials: sharing and making re-use possible

<a name="repositories"></a>
###  Training materials repositories and resources: GOBLET, TeSS, GitHub, etc.
With sharing and [FAIR](https://fair-dom.org/) principles in mind, GOBLET (the Global Organisation for Bioinformatics Learning Education and Training)  has pioneered a public repository within a [training Portal](http://mygoblet.org/training-portal) in 2014  where a significant amout of training materials has already been deposited.

The need for referencing training materials in general, in the context of ELIXIR, has led to the development of [TeSS](https://tess.elixir-europe.org), a training e-support system. It is all about discovering, packaging and linking training related objects, i.e. aggregating training materials, events and resources and making them accessible through one single entry point.

Many people involved in the production of training materials are finding useful to adopt collaborative platforms to support their activity. Git and GitHub, on which this resource is developed and served, is not a de facto standard, but presently it seems to be a smart choice, especially because updating is left in the hands of the authors. The extended capabilities to produce websites, e-books, etc. are also seen as strengths. 

Alternatively, the use of electronic notebooks, namely [Jupyter](http://jupyter.org) and its satellite services are gaining popularity. "Notebook documents (or “notebooks”, all lower case) are documents produced by the Jupyter Notebook App, which contain both computer code (e.g. python) and rich text elements (paragraph, equations, figures, links, etc...). Notebook documents are both human-readable documents containing the analysis description and the results (figures, tables, etc..) as well as executable documents which can be run to perform data analysis."

**References**:  
- [P.Fernandes - March 2013] (ftp://gtpb.igc.gulbenkian.pt/bicourses/posters/Calix_March2013.pdf)

**Examples**:  
* http://mygoblet.org/training-portal/courses/ngs-data-analysis-rnaseq-chipseq    (GOBLET ENTRY) 
* http://bioinformatics-core-shared-training.github.io/ndarc16/   (gitpages) 
* https://github.com/sdwfrost/mevr        (repository) 
* http://sdwfrost.github.io/mevr/         (gitbook) 
* http://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb        (Jupyter) 


