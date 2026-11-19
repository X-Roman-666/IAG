<p align="center"><a href="./README.md">简体中文</a> · <strong>English</strong></p>

<h1 align="center">IAG</h1>

<p align="center"><strong>Investigation-Augmented Generation</strong></p>

We are researching an AI collaboration method called **IAG — Investigation-Augmented Generation**.

RAG retrieves external information to help models obtain the knowledge they need to answer questions. In real projects, however, even with ample information, AI may still produce results that do not suit the user: it may not understand the user's real goals, industry context, prior experience, or specific difficulties. Users themselves may only gradually clarify what they want as the conversation progresses.

IAG (Investigation-Augmented Generation) is an investigation-driven framework for generation and collaboration. Centered on users and their real-world problems, the system continuously investigates goals, understanding, context, history, and existing work. It actively chooses actions such as asking questions, retrieving information, observing, and validating, then uses the evidence gathered and user feedback to update shared understanding, generated content, and execution plans.

IAG aims to integrate investigation throughout the entire workflow. While learning about the user and the actual problem, AI investigates the current situation, its history, and existing work. It helps users understand available approaches and key trade-offs, then continually adjusts its judgments and advances the task based on conversation and execution feedback. When there is enough information, it acts directly; when important unknowns arise, it investigates further, keeping collaboration from becoming an upfront questionnaire.

We draw on two guiding ideas: **"Making good use of external resources" (善假于物)** means actively finding and using existing tools, work, and practical experience; **"Investigation is problem-solving" (调查就是解决问题)** means understanding the specific situation in depth and continually refining plans in response to facts and feedback. At the same time, we keep people at the center, enabling users to understand, participate in, and define their own goals.

We have implemented initial mechanisms through the **DSH Collaborator plugin**, including records of shared understanding, guidance for finding relevant existing work, and reminders to maintain ongoing communication. Next, we will further specify how investigation actions are selected and how findings update the workflow, and evaluate whether these mechanisms improve the suitability of results while reducing rework and user burden.

Everyone is welcome to discuss this idea with us! Our lab is welcoming and open!

My email: [2641663627@qq.com](mailto:2641663627@qq.com) or [985211@gmail.com](mailto:985211@gmail.com)
