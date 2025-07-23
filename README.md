# AICARE: AI-powered Case-based Approach for Real-world Experience --> The Patient Interview
This is an LLM-powered case-based approach that allows physical therapy students to practice their patient interview skills

In addition or as an alternative to the instructions below, you may also begin by examining the AICARE Instructions.pdf

AI CARE is an open source framework for enhancing Doctor of Physical Therapy (DPT) student clinical reasoning and interview skills through AI-powered patient simulations. The framework provides structured feedback based on established clinical assessment frameworks and is model-agnostic, working with any conversational AI platform.
> **Important**
> 
> This project is part of ongoing research at Tufts University School of Medicine's Doctor of Physical Therapy Program exploring AI applications in medical and allied health education.
>
> ## Quickstart

The recommended way to use AI CARE is with any conversational AI model (ChatGPT, Claude, Gemini, etc.) and the provided prompt templates. No special software installation required.

1. **Choose your AI platform**
   - ChatGPT, Claude, Gemini, or similar conversational AI

2. **Prepare your patient case**
   - Use existing case studies or create your own
   - Ensure sufficient detail for meaningful simulation

3. **Follow the extraction process**
   - Use Patient Case Extraction prompt first
   - Save the structured output

4. **Run the simulation**
   - Use Patient Interview prompt
   - Customize patient behavior as needed (modify the patient's personality, clinical setting, language barriers, individuals present during the interview, etc.)
   - Practice your clinical interview skills

5. **Review assessment**
   - Request feedback to receive detailed evaluation
   - Use suggestions for skill improvement

### Run an AI CARE Simulation

> **Note**
> 
> AI CARE simulations consist of two main components: patient case extraction and interactive patient interviews. The system evaluates student performance using the ECHOWS framework across multiple clinical competency domains.

To start a simulation, you'll need:
- Access to a conversational AI model
- A patient case document (published case or created by you)
- The prompt files from this repository

**Basic simulation setup:**

1. **Extract Patient Information**
   ```
   1. Upload your patient case document to your AI model (OpenAI, Anthropic, Gemini, etc.)
   2. Copy and paste the Patient Case Extraction prompt
   3. Save the structured JSON output for reference
   ```

2. **Initialize Patient Interview**
   ```
   1. Upload the Patient Interview prompt as an attachment
   2. Customize patient personality traits (optional)
   3. Begin your clinical interview
   4. Request assessment when complete
   ```
>
> ### Assessment and Feedback

Once your interview is complete, request feedback using phrases like:
- "How did I do?"
- "Can I get my assessment?"
- "End simulation"

The system provides comprehensive evaluation across seven ECHOWS categories with a total score out of 100 points.

## Repository Contents

| File | Description | Usage |
|------|-------------|-------|
| `Patient Interview.txt` | Complete patient simulation framework with ECHOWS assessment | Core simulation prompt |
| `Patient Case Extraction.txt` | Structured extraction of patient information from documents | Patient data preprocessing |
| `AICARE Instructions.pdf` | Visual step-by-step guide to the AI CARE process | Implementation guide |

## Assessment Framework

The AI CARE system evaluates performance across seven key domains:

- **Patient Comfort and Privacy** (10 points)
- **Organization and Preparation** (15 points)
- **Establishing Rapport** (15 points)
- **Questioning Strategies** (15 points)
- **Verbal Communication** (15 points)
- **Interview Content** (20 points)
- **Wrapping Up** (10 points)

**Total: 100 points**

Each assessment includes:
- Specific strengths with direct quotes
- Areas for improvement with actionable suggestions
- Critical information obtained vs. missed
- Next steps for skill development

## Frequently Asked Questions (FAQ)

**"Do I need special software to use AI CARE?"**

No, AI CARE works with any conversational AI model (ChatGPT, Claude, Gemini, etc.). Simply copy and paste the provided prompts.

**"What's the difference between the two prompt files?"**

The Patient Case Extraction prompt processes clinical documents into structured data, while the Patient Interview prompt creates the interactive patient simulation and assessment system.

**"How do I customize patient behavior?"**

You can modify patient personality traits in the Patient Interview prompt (see AICARE Instructions.pdf). Examples include making patients anxious, stubborn, talkative, or reserved by editing the highlighted personality section. Other modifications in the personality secion could include having the patient present with an active child, apprehensive caregiver or even speaking English as a second language. Use your imagination!

**"Can I use my own patient cases?"**

Yes, AI CARE works with almost any patient case. Ensure your case contains sufficient detail for meaningful extraction and simulation.

**"How accurate is the assessment system?"**

The ECHOWS framework is based on established clinical assessment standards. However, AI assessment should supplement, not replace, human clinical education oversight.

**"Can I integrate this into my curriculum?"**

AI CARE is designed for educational use. Contact the research team for guidance on curriculum integration and implementation support.

**Tufts University School of Medicine - Doctor of Physical Therapy Program**
- Ben D. Stern (`benjamin.stern@tufts.edu`)
- Lydia Thurston


> **Important**
> 
> AI CARE is designed as an educational tool to enhance clinical training through supplemental practice opportunities. It is not intended to replace supervised clinical instruction, faculty mentorship, or standardized patient interactions. Users should critically evaluate all AI-generated content, as these systems may produce inaccurate or misleading information that requires verification.

## Citation

If you use AI CARE in your research or educational programs, please cite our work appropriately

By using AI CARE, you acknowledge this is a research tool intended for educational purposes
