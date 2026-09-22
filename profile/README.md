<div id="coms6998-course-page" style="margin: 0 auto; font-family: Arial, Helvetica, sans-serif; font-size: 16px; line-height: 1.6; color: #202b35; background-color: #ffffff;" lang="en">
    <div id="coms6998-masthead">
        <h4 style="margin: 0 0 16px;"><a style="color: #155e8a; text-decoration: underline;" href="#coms6998-people">Course Staff</a> &middot; <a style="color: #155e8a; text-decoration: underline;" href="#coms6998-logistics">Logistics</a> &middot; <a style="color: #155e8a; text-decoration: underline;" href="#coms6998-content">Content</a> &middot; <a style="color: #155e8a; text-decoration: underline;" href="#coms6998-coursework">Coursework</a> &middot; <a style="color: #155e8a; text-decoration: underline;" href="#coms6998-schedule">Schedule</a></h4>
    </div>
    <div id="coms6998-people" style="margin-bottom: 28px;">
        <h3 id="coms6998-course-staff-heading" style="margin: 28px 0 16px; padding-bottom: 8px; border-bottom: 1px solid #cbd5df; font-size: 1.3em; line-height: 1.35;"><strong>Course Staff</strong></h3>
        <table style="width: 100%; table-layout: fixed; border-collapse: collapse; margin: 12px 0 24px;" aria-labelledby="coms6998-course-staff-heading">
            <colgroup>
                <col style="width: 50%;" />
                <col style="width: 50%;" />
            </colgroup>
            <thead>
                <tr>
                    <th style="padding: 12px; background-color: #edf2f7; color: #202b35; text-align: left; vertical-align: top; border: 1px solid #cbd5df;" scope="col">Instructor</th>
                    <th style="padding: 12px; background-color: #edf2f7; color: #202b35; text-align: left; vertical-align: top; border: 1px solid #cbd5df;" scope="col">Teaching Assistant</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td style="padding: 12px; text-align: left; vertical-align: top; border: 1px solid #cbd5df;">
                        <div style="display: inline-block; margin: 0 0 8px; padding: 3px 8px; background-color: #edf2f7; color: #24465c; font-size: 0.8em;" aria-hidden="true">RK</div>
                        <div style="margin-bottom: 4px;">Rahul Krishna</div>
                        <div><a style="color: #155e8a; text-decoration: underline;" href="mailto:rk3080@columbia.edu">rk3080@columbia.edu</a></div>
                    </td>
                    <td style="padding: 12px; text-align: left; vertical-align: top; border: 1px solid #cbd5df;">
                        <div style="display: inline-block; margin: 0 0 8px; padding: 3px 8px; background-color: #edf2f7; color: #24465c; font-size: 0.8em;" aria-hidden="true">IK</div>
                        <div style="margin-bottom: 4px;">In Keun Kim</div>
                        <div><a style="color: #155e8a; text-decoration: underline;" href="mailto:ik2619@columbia.edu">ik2619@columbia.edu</a></div>
                    </td>
                </tr>
            </tbody>
        </table>
    </div>
    <div>
        <div id="coms6998-logistics" style="margin-bottom: 28px;">
            <h2 style="margin: 28px 0 16px; padding-bottom: 8px; border-bottom: 1px solid #cbd5df; font-size: 1.3em; line-height: 1.35;"><strong><span style="font-size: 14pt;">Logistics</span></strong></h2>
            <ul style="margin: 8px 0 20px; padding-left: 26px;">
                <li style="margin: 0 0 10px;"><strong>Lectures:</strong> Fridays 2:10&ndash;4:00pm, September 11 &ndash; December 11, 2026, in <strong>Hamilton 303</strong>.</li>
                <li style="margin: 0 0 10px;"><strong>Exams:</strong> midterm in class Friday, October 23; final exam Thursday, December 17.</li>
                <li style="margin: 0 0 10px;"><strong>Office hours:</strong> Rahul Krishna, Fridays 12:00&ndash;1:30pm. Email <a style="color: #155e8a; text-decoration: underline;" href="mailto:rk3080@columbia.edu"><em>rk3080@columbia.edu</em></a> to arrange another time.</li>
                <li style="margin: 0 0 10px;"><strong>Contact:</strong> ask all course-related questions in the <a style="color: #155e8a; text-decoration: underline;" href="https://courseworks2.columbia.edu/courses/258447/discussion_topics" data-api-endpoint="https://courseworks2.columbia.edu/api/v1/courses/258447/discussion_topics" data-api-returntype="[Discussion]">CourseWorks discussion topics</a>. All announcements are made there. Email <a style="color: #155e8a; text-decoration: underline;" href="mailto:rk3080@columbia.edu"><em>rk3080@columbia.edu</em></a> for personal matters.</li>
            </ul>
        </div>
    </div>
    <div id="coms6998-content" style="margin-bottom: 28px;">
        <h2 style="margin: 28px 0 16px; padding-bottom: 8px; border-bottom: 2px solid #cbd5df; font-size: 1.3em; line-height: 1.35;"><span style="font-size: 24pt;"><strong>Content</strong></span></h2>
        <h3 style="margin: 28px 0 16px; padding-bottom: 4px; border-bottom: 1px solid #cbd5df; font-size: 1.3em; line-height: 1.35;"><strong>What this Course is about?</strong></h3>
        <p style="margin: 0 0 16px;">An agent is a system: a model proposes work, a runtime executes it through tools, state connects the steps, and the whole thing runs on infrastructure that fails. This course treats agents as a systems-engineering problem rather than a prompting problem. Teams build one application over the semester &mdash; a security-alert triage agent that inspects a pinned repository and returns structured, evidence-backed findings &mdash; and each unit adds a constraint that forces a redesign: bounded execution and token budgets, tool contracts and <a style="color: #155e8a; text-decoration: underline;" href="https://modelcontextprotocol.io/docs/learn/architecture">MCP</a> servers backed by <a style="color: #155e8a; text-decoration: underline;" href="https://github.com/codellm-devkit">CLDK</a>, dependency-aware concurrency, context compaction and durable checkpoints, and finally deployment on a local Kubernetes cluster with measured recovery from a restart.</p>
        <p style="margin: 0 0 16px;">Each week teaches a systems concept and you implement that concept in the agent you already have. The lecture surveys several related ideas; the implementation obligation is one central mechanism, not every technique discussed.</p>
        <h3 style="margin: 28px 0 16px; padding-bottom: 8px; border-bottom: 1px solid #cbd5df; font-size: 1.3em; line-height: 1.35;"><span style="font-size: 18pt;"><strong>Prerequisites</strong></span></h3>
        <ul style="margin: 8px 0 20px; padding-left: 26px;">
            <li style="margin: 0 0 10px;"><strong>Proficiency in Python</strong>
                <p style="margin: 0 0 16px;">Course examples and the supported stack are Python. You will write, instrument, and debug one growing codebase across the semester with minimal scaffolding.</p>
            </li>
            <li style="margin: 0 0 10px;"><strong>Working familiarity with LLM APIs</strong>
                <p style="margin: 0 0 16px;">You should have called a messages or chat-completion API with tool definitions before, or be ready to pick that up in week 1.</p>
            </li>
            <li style="margin: 0 0 10px;"><strong>Basic systems background</strong>
                <p style="margin: 0 0 16px;">Processes, networking, containers, and databases at the level of an undergraduate systems course. Kubernetes is taught in the course; prior exposure helps but is not required.</p>
            </li>
        </ul>
        <p style="margin: 0 0 16px;">This is an implementation-heavy course, and teams own one codebase all semester, so please allocate enough time for it.</p>
        <h3 style="margin: 28px 0 16px; padding-bottom: 8px; border-bottom: 1px solid #cbd5df; font-size: 1.3em; line-height: 1.35;"><span style="font-size: 18pt;"><strong>Readings</strong></span></h3>
        <p style="margin: 0 0 16px;">There is no authoritative textbook on LLM agent systems yet, so the course runs on papers, systems texts, and engineering write-ups, all listed in the <a style="color: #155e8a; text-decoration: underline;" href="#coms6998-schedule">schedule</a> under the week that assigns them. Read the whole paper. Three books serve as companions:</p>
        <ul style="margin: 8px 0 20px; padding-left: 26px;">
            <li style="margin: 0 0 10px;"><a style="color: #155e8a; text-decoration: underline;" href="https://www.oreilly.com/library/view/designing-data-intensive-applications/9781098119058/">Designing Data-Intensive Applications</a> (2nd ed.), for data systems: measurement and reliability, service interfaces, durable workflows, and partial failure.</li>
            <li style="margin: 0 0 10px;"><a style="color: #155e8a; text-decoration: underline;" href="https://www.manning.com/books/kubernetes-in-action-second-edition">Kubernetes in Action</a> (2nd ed.), for deployment: Pods, Services, probes, and storage.</li>
        </ul>
    </div>
    <div>
        <div id="coms6998-coursework" style="margin-bottom: 28px;">
            <h3 style="margin: 28px 0 16px; padding-bottom: 8px; border-bottom: 1px solid #cbd5df; font-size: 1.3em; line-height: 1.35;"><strong><span style="font-size: 18pt;">Homework</span></strong></h3>
            <p style="margin: 0 0 16px;">Three solo (or 2-3 member team) assignments build one agent incrementally. Each is graded once after submission. Full briefs are released with each assignment; (tentative) deadlines are on the <a style="color: #155e8a; text-decoration: underline;" href="#coms6998-schedule">schedule</a>&nbsp;below.</p>
            <ul style="margin: 8px 0 20px; padding-left: 26px;">
                <li style="margin: 0 0 10px;"><span style="text-decoration: underline;"><strong>HW1: Bounded agent execution</strong></span>
                    <ul style="margin: 8px 0 20px; padding-left: 26px;">
                        <li style="margin: 0 0 10px;">Build a sequential reactive agent that triages one JSON alert against a pinned repository with local search/read tools and returns a structured TP/FP/Other finding with evidence references.</li>
                        <li style="margin: 0 0 10px;">Add a configurable per-run token budget: pre-call admission with an output allowance, post-call reconciliation of reported usage, and an explicit exhaustion outcome.</li>
                        <li style="margin: 0 0 10px;">Experiment: one normal run and one scripted exhaustion run, showing the runtime refuses an unaffordable invocation. The report also explains your architecture and state model and compares alternative architectures analytically.</li>
                    </ul>
                </li>
                <li style="margin: 0 0 10px;"><span style="text-decoration: underline;"><strong>HW2: Tool interfaces and coordinated execution</strong></span>
                    <ul style="margin: 8px 0 20px; padding-left: 26px;">
                        <li style="margin: 0 0 10px;">Wrap CLDK as an MCP server: expose its analysis surface as tools, not a hand-picked pair of operations, and connect the agent to it.</li>
                        <li style="margin: 0 0 10px;">Compare that structured-tool interface against a CodeAct-style code-action interface over the same analyses, and say which operations each one makes cheap or awkward.</li>
                        <li style="margin: 0 0 10px;">Organize the application into explicit stages with conditional routing, and parallelize one independent read-only section under a bounded concurrency limit.</li>
                        <li style="margin: 0 0 10px;">Experiment: the same fixed work run sequentially and concurrently. The report also compares the direct and MCP tool paths.</li>
                        <li style="margin: 0 0 10px;">Guard the tool boundary against prompt injection and similar abuse, for example with <a style="color: #155e8a; text-decoration: underline;" href="https://docs.arcjet.com">Arcjet</a>.</li>
                    </ul>
                </li>
                <li style="margin: 0 0 10px;"><span style="text-decoration: underline;"><strong>HW3: Recoverable integrated prototype</strong></span>
                    <ul style="margin: 8px 0 20px; padding-left: 26px;">
                        <li style="margin: 0 0 10px;">Add one context-compaction mechanism that keeps artifact references and source identity; persist run, progress, and accounting state; checkpoint one completed stage.</li>
                        <li style="margin: 0 0 10px;">Deploy the agent and MCP server on a local KIND cluster using the supplied deployment and storage examples.</li>
                        <li style="margin: 0 0 10px;">Experiment: one uninterrupted run and one run interrupted by a Pod restart at a committed checkpoint, resumed as the same job. Its report is the final project report.</li>
                        <li style="margin: 0 0 10px;">Repeat the experiment on a larger application and report how the design scales up.</li>
                    </ul>
                </li>
            </ul>
            <h3 style="margin: 28px 0 16px; padding-bottom: 8px; border-bottom: 1px solid #cbd5df; font-size: 1.3em; line-height: 1.35;"><span style="font-size: 14pt;"><strong>Submitting Homework</strong></span></h3>
            <ul style="margin: 8px 0 20px; padding-left: 26px;">
                <li style="margin: 0 0 10px;">Homework is done in teams (or as individual member). Submit your codebase, a two-page report with one main results table or figure, and reproducible run instructions.</li>
                <li style="margin: 0 0 10px;">Include configuration, pinned dependencies, snapshots, raw logs, and a short contribution statement.</li>
                <li style="margin: 0 0 10px;">The supported stack is the one used in lecture (<a style="color: #155e8a; text-decoration: underline;" href="https://docs.langchain.com/oss/python/langgraph/workflows-agents">LangGraph</a>); another framework is fine if it meets the same behavioral expectations.</li>
                <li style="margin: 0 0 10px;"><strong>Late days:</strong> each student has 4 late days for the semester, and may use at most 2 on any one assignment. A late day extends a deadline by 24 hours.</li>
            </ul>
            <h3 style="margin: 28px 0 16px; padding-bottom: 8px; border-bottom: 1px solid #cbd5df; font-size: 1.3em; line-height: 1.35;"><span style="font-size: 18pt;"><strong>Exams</strong></span></h3>
            <ul style="margin: 8px 0 20px; padding-left: 26px;">
                <li style="margin: 0 0 10px;"><strong>Midterm</strong> (October 23): Forty minutes, individual, closed book. Covers units 1&ndash;2 &mdash; dynamic control, token accounting and admission, tool contracts, action representation, scheduling tradeoffs, and agentic security at the tool boundary.</li>
                <li style="margin: 0 0 10px;"><strong>Final</strong> (December 17): individual, closed book. Emphasizes context, state, and recovery &mdash; checkpoint placement, compaction-related information loss, state ownership, duplicate effects, and recovery timelines &mdash; while connecting earlier units.</li>
            </ul>
            <p style="margin: 0 0 16px;">Both exams are structured as multiple choice multiple answer questions with a brief explanatory prose when applicable. We will ask you to reason about scenarios and conceptual understanding.</p>
            <h3 style="margin: 28px 0 16px; padding-bottom: 8px; border-bottom: 1px solid #cbd5df; font-size: 1.3em; line-height: 1.35;"><span style="font-size: 18pt;"><strong>Grading</strong></span></h3>
            <table style="width: 100%; border-collapse: collapse; margin: 12px 0 24px;" aria-labelledby="coms6998-grading-heading">
                <thead>
                    <tr>
                        <th style="padding: 12px; background-color: #edf2f7; color: #202b35; text-align: left; vertical-align: top; border: 1px solid #cbd5df;" scope="col">Assessment</th>
                        <th style="padding: 12px; background-color: #edf2f7; color: #202b35; vertical-align: top; text-align: right; white-space: nowrap; border: 1px solid #cbd5df;" scope="col">Weight</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; border: 1px solid #cbd5df;">HW1: Bounded agent execution</td>
                        <td style="padding: 12px; vertical-align: top; text-align: right; white-space: nowrap; border: 1px solid #cbd5df;">20%</td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; border: 1px solid #cbd5df;">HW2: Tool interfaces and coordinated execution</td>
                        <td style="padding: 12px; vertical-align: top; text-align: right; white-space: nowrap; border: 1px solid #cbd5df;">20%</td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; border: 1px solid #cbd5df;">HW3: Recoverable integrated prototype</td>
                        <td style="padding: 12px; vertical-align: top; text-align: right; white-space: nowrap; border: 1px solid #cbd5df;">20%</td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; border: 1px solid #cbd5df;">Midterm</td>
                        <td style="padding: 12px; vertical-align: top; text-align: right; white-space: nowrap; border: 1px solid #cbd5df;">20%</td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; border: 1px solid #cbd5df;">Final exam</td>
                        <td style="padding: 12px; vertical-align: top; text-align: right; white-space: nowrap; border: 1px solid #cbd5df;">20%</td>
                    </tr>
                </tbody>
            </table>
            <h3 style="margin: 28px 0 16px; padding-bottom: 8px; border-bottom: 1px solid #cbd5df; font-size: 1.3em; line-height: 1.35;"><span style="font-size: 14pt;"><strong>Prerequisites</strong></span></h3>
            <p style="margin: 0 0 16px;">Each homework is marked out of 20 on four criteria worth 5 points each: systems design and claim, experimental design, evidence and reproducibility, and interpretation and limitations. A sound experiment earns full credit without a speedup, a token reduction, or a confirmed hypothesis; a missing required mechanism does not. This will be specified in the homework brief.</p>
            <h3 style="margin: 28px 0 16px; padding-bottom: 8px; border-bottom: 1px solid #cbd5df; font-size: 1.3em; line-height: 1.35;"><span style="font-size: 14pt;"><strong>Academic Integrity</strong></span></h3>
            <p style="margin: 0 0 16px;">All work is subject to the <a style="color: #155e8a; text-decoration: underline;" href="https://www.cs.columbia.edu/academic/academic-honesty/">Columbia Computer Science academic honesty policy</a>. Teams must be able to explain every part of what they submit; the individual exams test that.</p>
            <p style="margin: 0 0 16px;"><strong>AI tools:</strong> using an AI assistant to learn &mdash; explaining a concept, debugging your own code, reviewing a design &mdash; is permitted, and so is scoped autocomplete. Handing an assignment to an agent and submitting what it produces is not: it removes the practice this course is built on. You remain responsible for every line you submit. You must follow and uphold all of Columbia's integrity requirements.&nbsp;</p>
        </div>
    </div>
    <div id="coms6998-schedule" style="margin-bottom: 28px;">
        <h3 id="coms6998-schedule-heading" style="margin: 28px 0 16px; padding-bottom: 8px; border-bottom: 1px solid #cbd5df; font-size: 1.3em; line-height: 1.35;"><span style="font-size: 18pt;"><strong>Schedule (weekly topics may change)</strong></span></h3>
        <p style="margin: 0 0 16px;"><span style="display: block; margin-bottom: 4px; font-size: 0.9em;"><strong>Weeks 1&ndash;3:</strong> Agent architectures and control</span> <span style="display: block; margin-bottom: 4px; font-size: 0.9em;"><strong>Weeks 4&ndash;6:</strong> Tool interfaces and concurrency</span> <span style="display: block; margin-bottom: 4px; font-size: 0.9em;"><strong>Weeks 8&ndash;9:</strong> Context, state, and persistence</span> <span style="display: block; margin-bottom: 4px; font-size: 0.9em;"><strong>Weeks 10&ndash;12:</strong> Deployment, recovery, and observability</span></p>
        <div style="width: 100%; overflow-x: auto;" role="region" aria-labelledby="coms6998-schedule-heading">
            <table id="coms6998-schedule-table" style="width: 100%; border-collapse: collapse; margin: 12px 0 24px; min-width: 840px; table-layout: fixed; font-size: 0.9em; line-height: 1.5;" aria-labelledby="coms6998-schedule-heading">
                <colgroup>
                    <col style="width: 5%;" />
                    <col style="width: 13%;" />
                    <col style="width: 37%;" />
                    <col style="width: 25%;" />
                    <col style="width: 20%;" />
                </colgroup>
                <thead>
                    <tr>
                        <th style="padding: 12px; background-color: #edf2f7; color: #202b35; text-align: left; vertical-align: top; border: 1px solid #cbd5df;" scope="col">#</th>
                        <th style="padding: 12px; background-color: #edf2f7; color: #202b35; text-align: left; vertical-align: top; border: 1px solid #cbd5df;" scope="col">Date</th>
                        <th style="padding: 12px; background-color: #edf2f7; color: #202b35; text-align: left; vertical-align: top; border: 1px solid #cbd5df;" scope="col">Description</th>
                        <th style="padding: 12px; background-color: #edf2f7; color: #202b35; text-align: left; vertical-align: top; border: 1px solid #cbd5df;" scope="col">Reading</th>
                        <th style="padding: 12px; background-color: #edf2f7; color: #202b35; text-align: left; vertical-align: top; border: 1px solid #cbd5df;" scope="col">Deadlines (tentative)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;">1</td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;" scope="row">Fri Sep 11</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;">Map the system: model, controller, tools, state, environment; one alert-to-finding trace <br /><a style="color: #155e8a; text-decoration: underline;" href="https://github.com/comse6998-019/lectures/blob/main/lecture-1--2026-09-11/slides.pptx">Slides</a></td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;"><a style="color: #155e8a; text-decoration: underline;" href="https://www.anthropic.com/engineering/building-effective-agents">Building effective agents</a>; <a style="color: #155e8a; text-decoration: underline;" href="https://artint.info/3e/html/ArtInt3e.Ch2.html">Poole &amp; Mackworth</a> &sect;&sect;2.1&ndash;2.3; <a style="color: #155e8a; text-decoration: underline;" href="https://arxiv.org/abs/2309.02427">CoALA</a> &sect;4</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;">Teams and repositories set up</td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;">2</td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;" scope="row">Fri Sep 18</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;">Agent architectures, state, and dynamic control flow: fixed workflows, ReAct, plan&ndash;execute; who chooses the next operation</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;"><a style="color: #155e8a; text-decoration: underline;" href="https://arxiv.org/abs/2210.03629">ReAct</a> &sect;2; <a style="color: #155e8a; text-decoration: underline;" href="https://docs.langchain.com/oss/python/langgraph/workflows-agents">LangGraph workflows and agents</a>; <a style="color: #155e8a; text-decoration: underline;" href="https://arxiv.org/abs/2303.11366">Reflexion</a> &sect;3</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;">HW1 <span style="white-space: nowrap;">out</span></td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;">3</td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;" scope="row">Fri Sep 25</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;">Termination, token budgets, and controlled measurement: admission versus accounting, output reservations, exhaustion outcomes</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;"><a style="color: #155e8a; text-decoration: underline;" href="https://platform.claude.com/docs/en/build-with-claude/token-counting">Token counting</a>; <a style="color: #155e8a; text-decoration: underline;" href="https://arxiv.org/abs/2407.01502">AI Agents That Matter</a> &sect;&sect;3&ndash;4; <a style="color: #155e8a; text-decoration: underline;" href="https://www.oreilly.com/library/view/designing-data-intensive-applications/9781098119058/">DDIA2</a> ch. 2</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f6fc; border: 1px solid #cbd5df;"></td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;">4</td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;" scope="row">Fri Oct 2</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;">Tool contracts and execution boundaries: schemas, validation, discovery, local dispatch versus RPC, transport versus domain failures</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;"><a style="color: #155e8a; text-decoration: underline;" href="https://modelcontextprotocol.io/docs/learn/architecture">MCP architecture</a>; <a style="color: #155e8a; text-decoration: underline;" href="https://platform.claude.com/docs/en/agents-and-tools/tool-use/how-tool-use-works">native tool use</a>; <a style="color: #155e8a; text-decoration: underline;" href="https://arxiv.org/abs/2305.15334">Gorilla</a> &sect;3.3</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;"></td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;">5</td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;" scope="row">Fri Oct 9</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;">Action composition and dependency-aware workflows: stage contracts, dependency DAGs, fork/join, bounded fan-out, critical paths</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;"><a style="color: #155e8a; text-decoration: underline;" href="https://arxiv.org/html/2312.04511v3">LLMCompiler</a> fig. 2, &sect;&sect;3.1&ndash;3.3; <a style="color: #155e8a; text-decoration: underline;" href="https://arxiv.org/html/2402.01030v4">CodeAct</a> &sect;2.1; <a style="color: #155e8a; text-decoration: underline;" href="https://arxiv.org/abs/2412.07017">AsyncLM</a> &sect;3 (optional)</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;">HW1 <span style="white-space: nowrap;">due</span><br />HW2 <span style="white-space: nowrap;">out</span></td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;">6</td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;" scope="row">Fri Oct 16</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;">Controlled execution experiments: sequential and concurrent timelines, dependency stalls, overhead, one failure trace. Agentic security: guarding the tool boundary against prompt injection and abuse</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;"><a style="color: #155e8a; text-decoration: underline;" href="https://arxiv.org/abs/2302.12173">Indirect prompt injection</a> &sect;3; <a style="color: #155e8a; text-decoration: underline;" href="https://arxiv.org/abs/2506.08837">Design patterns for securing agents</a> &sect;3; <a style="color: #155e8a; text-decoration: underline;" href="https://docs.arcjet.com/">Arcjet docs</a>; <a style="color: #155e8a; text-decoration: underline;" href="https://arxiv.org/abs/2503.18813">CaMeL</a> &sect;5 (optional)</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #eff7f2; border: 1px solid #cbd5df;"></td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff0f1; border: 1px solid #cbd5df;">7</td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff0f1; border: 1px solid #cbd5df;" scope="row">Fri Oct 23</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff0f1; border: 1px solid #cbd5df;"><strong>Midterm exam</strong> (in class, one hour). No lecture</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff0f1; border: 1px solid #cbd5df;">Review weeks 1&ndash;6</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff0f1; border: 1px solid #cbd5df;"><span style="white-space: nowrap;">midterm</span></td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff7eb; border: 1px solid #cbd5df;">8</td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff7eb; border: 1px solid #cbd5df;" scope="row">Fri Oct 30</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff7eb; border: 1px solid #cbd5df;">Context working sets, compaction, and provenance: selection versus lossy summarization, artifact references, source identity</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff7eb; border: 1px solid #cbd5df;"><a style="color: #155e8a; text-decoration: underline;" href="https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents">Context engineering</a>; <a style="color: #155e8a; text-decoration: underline;" href="https://arxiv.org/abs/2310.08560">MemGPT</a> &sect;2; <a style="color: #155e8a; text-decoration: underline;" href="https://aclanthology.org/2024.tacl-1.9.pdf">Lost in the Middle</a> (optional)</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff7eb; border: 1px solid #cbd5df;"></td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff7eb; border: 1px solid #cbd5df;">9</td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff7eb; border: 1px solid #cbd5df;" scope="row">Fri Nov 6</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff7eb; border: 1px solid #cbd5df;">State ownership, checkpointing, and resumption: run-local versus durable state, checkpoint boundaries, replay</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff7eb; border: 1px solid #cbd5df;">LangGraph <a style="color: #155e8a; text-decoration: underline;" href="https://docs.langchain.com/oss/python/langgraph/persistence">persistence</a> and <a style="color: #155e8a; text-decoration: underline;" href="https://docs.langchain.com/oss/python/langgraph/checkpointers">checkpointers</a>; <a style="color: #155e8a; text-decoration: underline;" href="https://www.microsoft.com/en-us/research/wp-content/uploads/2021/10/DF-Semantics-Final.pdf">Durable Functions</a> &sect;&sect;2.1&ndash;2.2, 3.5</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff7eb; border: 1px solid #cbd5df;">HW2 <span style="white-space: nowrap;">due<br />HW3 out<br /></span></td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;">10</td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;" scope="row">Fri Nov 13</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;">Deployment and service lifecycle: reconciliation, Pods and Services, readiness and liveness, ephemeral versus persistent storage</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;"><a style="color: #155e8a; text-decoration: underline;" href="https://kubernetes.io/docs/concepts/workloads/pods/probes/">Kubernetes probes</a>; <a style="color: #155e8a; text-decoration: underline;" href="https://kind.sigs.k8s.io/docs/user/quick-start/">KIND quick start</a></td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;"></td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;">11</td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;" scope="row">Fri Nov 20</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;">Partial failure and bounded recovery: deadlines, retry amplification, backoff, idempotent writes, uncertain outcomes</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;"><a style="color: #155e8a; text-decoration: underline;" href="https://sre.google/sre-book/addressing-cascading-failures/">SRE: cascading failures</a>; <a style="color: #155e8a; text-decoration: underline;" href="https://sigops.org/s/conferences/hotos/2021/papers/hotos21-s11-bronson.pdf">Metastable failures</a> &sect;&sect;1, 2.1; <a style="color: #155e8a; text-decoration: underline;" href="https://www.cidrdb.org/cidr2007/papers/cidr07p15.pdf">Life beyond distributed transactions</a> &sect;5; <a style="color: #155e8a; text-decoration: underline;" href="https://www.oreilly.com/library/view/designing-data-intensive-applications/9781098119058/">DDIA2</a> ch. 9</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;"></td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f4f4f4; border: 1px solid #cbd5df;"></td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #f4f4f4; border: 1px solid #cbd5df;" scope="row">Fri Nov 27</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f4f4f4; border: 1px solid #cbd5df;"><em>No class (Thanksgiving break)</em></td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f4f4f4; border: 1px solid #cbd5df;"></td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f4f4f4; border: 1px solid #cbd5df;"></td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;">12</td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;" scope="row">Fri Dec 4</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;">Observability and recovery measurement: correlated events, service signals, end-to-end latency, completed versus repeated work</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;"><a style="color: #155e8a; text-decoration: underline;" href="https://sre.google/sre-book/monitoring-distributed-systems/">SRE: monitoring</a>; <a style="color: #155e8a; text-decoration: underline;" href="https://research.google/pubs/dapper-a-large-scale-distributed-systems-tracing-infrastructure/">Dapper</a> &sect;&sect;2.1&ndash;2.3; <a style="color: #155e8a; text-decoration: underline;" href="https://research.google/pubs/the-tail-at-scale/">The Tail at Scale</a></td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f5f1fa; border: 1px solid #cbd5df;">HW3 <span style="white-space: nowrap;">due</span></td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f5f6; border: 1px solid #cbd5df;">13</td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f5f6; border: 1px solid #cbd5df;" scope="row">Fri Dec 11</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f5f6; border: 1px solid #cbd5df;">Integration studio: trace one job end to end across components, identify limitations, fix integration defects</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f5f6; border: 1px solid #cbd5df;">Your team's reports and traces; <a style="color: #155e8a; text-decoration: underline;" href="https://arxiv.org/abs/2411.00640">Adding error bars to evals</a>; <a style="color: #155e8a; text-decoration: underline;" href="https://arxiv.org/abs/2406.12045">&tau;-bench</a> (optional)</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #f0f5f6; border: 1px solid #cbd5df;"></td>
                    </tr>
                    <tr>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff0f1; border: 1px solid #cbd5df;">14</td>
                        <th style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff0f1; border: 1px solid #cbd5df;" scope="row">Thu Dec 17</th>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff0f1; border: 1px solid #cbd5df;"><strong>Final exam</strong> (individual, closed book). No regular class</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff0f1; border: 1px solid #cbd5df;">Review weeks 1&ndash;13</td>
                        <td style="padding: 12px; text-align: left; vertical-align: top; background-color: #fff0f1; border: 1px solid #cbd5df;"><span style="white-space: nowrap;">final exam</span></td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
    <p style="margin: 32px 0 0; padding-top: 16px; border-top: 1px solid #cbd5df; font-size: 0.9em; color: #52616d;">COMS 6998-019 &middot; Columbia University &middot; Fall 2026</p>
</div>
<div id="codex-browser-sidebar-comments-root" style="z-index: 2147483647;"></div>
