---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
<ul>
  <li>
    <p>
      <strong>University of Alberta</strong>, Edmonton, Canada<br>
      <em>Master of Science in Computer Science</em><br>
      Sep. 2023 – Jan. 2026<br>
      GPA: 3.83 / 4.0
    </p>
  </li>

  <li>
    <p>
      <strong>Amirkabir University of Technology</strong>, Tehran, Iran<br>
      <em>Bachelor of Science in Computer Engineering</em><br>
      Sep. 2018 – Jun. 2023<br>
      GPA: 3.76 / 4.0
    </p>
  </li>
</ul>

---

Experience
======
<ul>
  <li>
    <p>
      <strong>Client Coaching (Startup Mentorship)</strong><br>
      Alberta Machine Intelligence Institute (Amii), Edmonton, Canada<br>
      Jan. 2026 – Present
    </p>
    <ul>
      <li>Advised startups on the design and architecture of LLM-based agent systems, from ideation to implementation</li>
    </ul>
  </li>

  <li>
    <p>
      <strong>Project Validation (Technical Advisement)</strong><br>
      Alberta Machine Intelligence Institute (Amii), Edmonton, Canada<br>
      Jan. 2025 – Mar. 2025
    </p>
    <ul>
      <li>Advised on designing an LLM-based RAG pipeline to assess contractor policy alignment with owner
requirements</li>
      <li>Proposed parameter-efficient fine-tuning and context engineering strategies for deployment-constrained
settings</li>
      <li>Guided model and system selection by balancing accuracy, latency, and cost trade-offs across the ML stack</li>
    </ul>
  </li>

  <li>
    <p>
      <strong>Natural Language Processing Research Scientist</strong><br>
      University of Alberta, Edmonton, Canada<br>
      Jan. 2024 – Jan. 2026
    </p>
    <ul>
      <li>Improved long-term memory and long-context reasoning in LLMs by up to 12.69% over strong baselines</li>
      <li>Designing a severity-aware metric and model to quantify the harm of errors in LLM outputs</li>
      <li>Built a medical RAG chatbot that improved accuracy, readability, comprehensiveness, and empathy
over baselines by integrating multimodal retrieval, long-term memory, and hallucination detection</li>
      <li>Built inference-time scaling and agentic AI systems to support multi-step reasoning in LLM applications</li>
    </ul>
  </li>

  <li>
    <p>
      <strong>Software Engineer</strong><br>
      Digikala, Tehran, Iran<br>
      Jan. 2022 – May 2022
    </p>
    <ul>
      <li>Reduced large-scale database query latency by 20% by optimizing query plans and indexing strategies in
production systems</li>
      <li>Developed a PHP (Symfony) service for generating diverse reports, significantly improving report delivery time</li>
      <li>Built and deployed a highly efficient caching mechanism, reducing data retrieval latency by approximately 15%</li>
    </ul>
  </li>

  <li>
    <p>
      <strong>Backend Developer</strong><br>
      Narvan Startup Studio, Tehran, Iran<br>
      Jun. 2021 – Jan. 2022
    </p>
    <ul>
      <li>Enabled high-performance backend architecture using Nginx, gRPC, Elasticsearch, and PostgreSQL</li>
      <li>Integrated monitoring tools such as Prometheus and Kafka to ensure optimal application performance</li>
    </ul>
  </li>

  <li>
    <p>
      <strong>Machine Learning Engineer & Frontend Developer</strong><br>
      Bookapo, Tehran, Iran<br>
      Aug. 2020 – Jun. 2021
    </p>
    <ul>
      <li>Developed machine learning models to recommend similar books, enhancing user engagement</li>
      <li>Built the frontend of the Bookapo platform using React.js, delivering a seamless and intuitive user interface</li>
    </ul>
  </li>

  <li>
    <p>
      <strong>Computer Vision Research Scientist</strong><br>
      NODET, Tehran, Iran<br>
      May 2020 – Dec. 2020
    </p>
    <ul>
      <li>Developed object detection models for identifying diverse objects in aerial imagery</li>
      <li>Designed and implemented image pre- and post-processing pipelines</li>
    </ul>
  </li>
</ul>

---

Technical Skills
======
<ul>
  <li><strong>Programming Languages:</strong> Python, C/C++, Java, Go</li>
  <li><strong>Machine Learning & NLP:</strong> PyTorch, Hugging Face Transformers, LangChain, LlamaIndex, spaCy</li>
  <li><strong>Agentic Systems:</strong> Tool-Using Agents, Multi-Agent Systems, Memory-Augmented Architectures</li>
  <li><strong>Retrieval & Search:</strong> FAISS, Chroma, Milvus, Elasticsearch, RAG Pipelines, Knowledge Graphs</li>
  <li><strong>Fine-Tuning & Optimization:</strong> PEFT, DeepSpeed, BitsAndBytes, Quantization</li>
  <li><strong>Inference & Serving:</strong> vLLM, Ray Serve, Distributed Inference</li>
  <li><strong>Databases:</strong> PostgreSQL, MongoDB</li>
  <li><strong>MLOps & Infrastructure:</strong> Docker, Kubernetes, CI/CD, Git, Bash, Weights & Biases</li>
  <li><strong>Cloud Platforms:</strong> AWS, GCP</li>
  <li><strong>Web & App Development:</strong> Django, JavaScript, React, Node.js, Android</li>
</ul>

---

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
