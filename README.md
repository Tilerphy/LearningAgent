# First, Play the AnEasyAgentsInteraction.ipynb

In this notebook, you can learn that how to create Agent, how to use Agent. 

Do not mind if it is 'autogen' based, you can also write codes by yourself to make them interacting, and more free space to customize the flow. 

# Phases

- Phase 1: Create Agents

  No matter which type of Agent you want to create, just do it.
  
  A planner, some assistants, a supervisor, some executor, no matter, just create it.

  In this phase, you just need to agree that, Agent will bring intelligence to legacy object.

- Phase 2: Evaluate the Interaction Context

  Maybe you have realize that, something is strange, of course, maybe not, no matter again.

  Think about the tranditional programming, sorry I call it tranditional programming, it means no AI init in this scene.

  In that type of programming or software engineering, we always try to find something can be reused, abstracted, deleted, cached.

  So how about this time, we reuse what? abstract what? delete what? cache what?

  We need to do some evaluation before we do those things. Which part needs to be evaluated?

  Do you remember this?

  <img src="img.png" width="500">

  we need to evaluate if step 3-6 were stable.

  Why? The reason is in the next Phase. Because in some project or produc, we just need to evaluate it and give some report to customer or to ourself, the work is done here. But, if your work is to intergrate systems or other agent, you need to step into next Phrases.

  - Phase 3: Persistent (For Dynamic & Automatic Systems Integration)

  Take an assumption: We have a lot of legacy systems, legacy endpoints, legacy APIs, new Agents. Then we got a new Customer Requirement to Create an API. After thinking and talking about the requirement, we found that we just need to combine some of we have, then we can complete the job.
  
  If we had done the upgradation from Legacy system to Agent (Phase 1 job). We just need to ask *planner agent* to schedule plan or calling flow, then let *scripting agent* to generate some glue codes, then let *supervior agent* to summarize necessary data and collect it. (Phase 1 job)
  
  If we found it is being a stable(after evaluation) Multi-Agent. (Phase 2 job) When this API faces the same or similar request:

  Shall we call *planner agent* to schedule plan or calling flow again?

  Shall we let *scripting agent* to generate glue codes again?

  Shall we let *supervior agent* to summarize necessary data again?

  Probably not.

  Then we need to make the plan, calling flow, generated glue codes, input/output rule and so on, to be persistent.

  
  

