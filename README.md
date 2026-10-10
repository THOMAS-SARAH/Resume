# Sarah Thomas — Technical Projects Portfolio

Welcome to my software engineering project repository! This portfolio showcases my work across **AIOps & Incident Automation**, **Machine Learning / Computer Vision**, and **Cloud Infrastructure Telemetry**.

---

## Technical Stack Overview

* **Languages & Frameworks:** Python, Java, FastAPI, REST APIs, Scikit-Learn, OpenCV, Linux/Bash
* **Cloud & DevOps:** AWS (S3, EC2, Lambda, IAM, CloudWatch), Docker, Terraform, Prometheus, CI/CD (GitHub Actions)
* **AI & Data Science:** OpenAI API, AIOps, Pandas, NumPy, Matplotlib

---

## Featured Projects

### 1.  AI Incident & Log Analysis Assistant
> **Tech Stack:** Python, FastAPI, OpenAI API, Uvicorn, Pydantic  
> **Repository:** [`exception_analyzer`](https://github.com/THOMAS-SARAH/exception_analyzer)

* **Overview:** A lightweight RESTful microservice that processes server log traces, stack traces, and system telemetry errors to generate automated Root-Cause Analysis (RCA) reports.
* **Key Features:**
  * Ingests multi-line stack traces via POST requests (`/analyze`).
  * Utilizes structured prompt engineering to output standardized summaries, root cause breakdowns, and actionable remediation steps.
  * Includes interactive Swagger UI (`/docs`) for seamless API testing and endpoint validation.

---

### 2.  Hybrid Ensemble Model for Enhanced Cancer Cell Classification
> **Tech Stack:** Python, Scikit-Learn, OpenCV, Pandas, Matplotlib  
> **Repository:** [`CANCER_CELL_DETECTION`](https://github.com/THOMAS-SARAH/CANCER_CELL_DETECTION)

* **Overview:** A hybrid machine learning pipeline designed to distinguish cancerous from non-cancerous cells in medical imaging data.
* **Key Features:**
  * Integrates multiple classification algorithms into a hybrid ensemble model for higher prediction reliability.
  * Employs advanced OpenCV pre-processing pipelines for image denoising, contrast adjustments, and feature extraction.
  * Evaluates performance using ROC-AUC curves, confusion matrices, and standard classification metrics.

---

### 3. AI-Driven Cloud Resource & Cost Optimizer
> **Tech Stack:** Terraform, Prometheus, Node Exporter, FastAPI, AWS, Linux/Bash  
> **Repository:** [`multi-region-aws-telemetry-pipeline`](https://github.com/THOMAS-SARAH/multi-region-aws-telemetry-pipeline)

* **Overview:** An end-to-end cloud infrastructure monitoring and telemetry pipeline built to track performance metrics and optimize workload health.
* **Key Features:**
  * Provisions multi-region AWS cloud infrastructure using modular Terraform templates.
  * Deploys Prometheus and Node Exporter to scrape real-time CPU, memory, and network throughput data across 2+ simulated cloud instances.
  * Integrates scraping endpoints with a FastAPI backend to trigger rule-based resource allocation and anomaly detection.

---

## 📬 Contact & Links

* **Email:** [saratthomas29@gmail.com](mailto:saratthomas29@gmail.com)
* **LinkedIn:** [linkedin.com/in/sarah-thomas-40a301289](https://linkedin.com/in/sarah-thomas-40a301289)
* **GitHub:** [github.com/THOMAS-SARAH](https://github.com/THOMAS-SARAH)
