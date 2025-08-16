---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-08-15
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: ''  # 清空原标题
      subtitle: ''
      text: |-
        <div style="text-align: left;">
          <h2 style="text-align: left !important; font-size: 1.875rem; font-weight: bold; margin-bottom: 1.5rem; color: inherit;">📚 My Research</h2>
          
          <em>My previous <a href="https://sites.harvard.edu/jzhou/">webpage is here</a> for reference of past research and projects.</em>
          
          My primary research interests lie in the areas of natural language processing (NLP) and machine learning (ML). The ultimate goal is to build general intelligent machines that can understand, interact, and help human beings on a wide variety of tasks with <strong>trustworthiness</strong> and <strong>efficiency</strong>. I am glad to see LLMs are bringing us one step closer 🤔

          I am broadly interested in understanding and improving state-of-the-art deep learning models such as (large) language models (LLMs), on a variety of aspects such as efficiency, knowledge represention and manipulation, memorization, factualness, AI safety, fair evaluation, reasoning and planning, as well as multimodality.
          
          Check <a href="/research/">Research</a> for more details.
          Feel free to reach out to collaborate on any interesting problems.

          Here is a general talk I gave in Nov 2024 at Stony Brook for the CS department research seminar to all students and faculty - <strong>Generating from Generative ⸤Language⸣ Models (<a href="https://youtu.be/XQ5hRluP2bo">link</a>)</strong>
        </div>
    design:
      columns: '1'

  - block: markdown
    content:
     title: ''
     subtitle: ''
     text: |-
      <div style="text-align: left; width: 100%; margin: 0; padding: 0;">
        <h2 style="text-align: left !important; font-size: 1.875rem; font-weight: bold; margin: 0 0 1.5rem 0; padding: 0; display: block; width: 100%; transform: translateX(0);">🎯 Research Interests</h2>
        
        Natural Language Processing**: Understanding and generating human language
        Machine Learning**: Deep learning and neural architectures  
        Large Language Models (LLMs)**: Efficiency, safety, and capabilities
        Reasoning & Planning**: RL-based approaches for complex problem solving
      </div>
    design:
      columns: '1'

  - block: markdown
    content:
      title: ''  # 清空原标题
      subtitle: ''
      text: |-
        <div style="text-align: left;">
          <h2 style="text-align: left !important; font-size: 1.875rem; font-weight: bold; margin-bottom: 1.5rem; color: inherit;">🤝 Opportunities</h2>
          
          **Postdoc Positions:**
          If you are interested in postdoc positions starting 2025-2026 working with me, please apply directly to the <a href="https://ai.stonybrook.edu/">AI3 institute</a> official <a href="https://stonybrooku.taleo.net/careersection/2/jobdetail.ftl?job=2502254">application portal</a>. Feel free to reach out for any questions.

          **Prospective Students:**
          If you're interested in working with me, feel free to reach out with a brief introduction, an overview of your research background, and any problems or ideas you're currently exploring. I am looking for highly motivated students (in any stage) with strong technical skills in programming and mathematical reasoning. Strong communication and writing skills are equally important, as our work involves documenting and presenting research findings effectively.

          Our research focuses on advancing cutting-edge techniques in NLP and ML, so you should be prepared to write a substantial amount of code daily and conduct extensive experiments. I deeply value curiosity-driven minds, rigorous thinking, and creative problem-solving—essential qualities for producing impactful and innovative research that shapes a more exciting future.

          I am actively looking for outstanding Ph.D. applicants who meet the above criteria. If you are interested, consider applying to the Ph.D. programs in <a href="https://www.cs.stonybrook.edu/admissions/Graduate-Program">Computer Science</a>, <a href="https://www.cs.stonybrook.edu/admissions/Graduate-Admissions-Data-Science">Data Science</a>, or <a href="https://www.stonybrook.edu/commcms/ams/graduate/_resources/applying-to-the-AMS-grad-program.php">Applied Mathematics & Statistics</a> (if your background is in mathematics or statistics). Be sure to mention my name in your application, and feel free to reach out after applying if there is a strong alignment with your interests and expertise.

          Please note that I cannot guarantee a reply to every inquiry (apologies), and sometimes my response may be (very) delayed.
        </div>
    design:
      columns: '1'
  
---