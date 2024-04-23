## GGH_2k23 Ideathon

**Author**: Purvi Porwal

## Setting Up the Environment

1. **Install Flask:**

   ```bash
   pip install flask

   ```

2. **Install Flask-SQLAlchemy:**

   ```bash
   pip install flask_sqlalchemy

   ```

3. **Run the Flask Application:**

   ```bash
   python app.py
   ```

Once the application is running, you can access it in your web browser at the specified address (usually `http://localhost:5000`).

## Introduction

Globally, it is estimated that 1 in 7 (14%) 10–19 year-olds experience mental health conditions (1), yet these remain largely unrecognized and untreated.Suicide is a global concern, with nearly one million deaths annually and exponentially more attempts. Rates vary greatly by country, with India ranking 43rd, and youth are particularly vulnerable. It is crucial to address the needs of adolescents with mental health conditions. Avoiding institutionalization and over-medicalization, prioritizing non-pharmacological approaches.Some reasons for undetected and untreated cases of mental health disorder in India include: Lack of knowledge, Inequitable distribution of services, and Fear of stigma.

## Goal

- Developing an AI model for mental health prediction entails meticulous data collection and analysis to create a robust system . The aim of this project is to create a user-friendly tool for students to assess their mental well-being. By leveraging HTML, CSS for the frontend, and Flask with SQLAlchemy for prediction, the system will provide personalized insights into potential depression symptoms.
- The patient’s file could also be flagged to alert the medical staff the next time they have any kind of physician appointment to prompt doctors to start the conversation with patients. At the very least information and resources could be sent to patients directly to encourage them to take action on their own behalf.
- Using machine learning and data that may otherwise be in a patient’s medical file, the goal is to predict who may have depression in a way that requires very little human participation from doctors and has lower time and money costs associated. The patients who are predicted to have depression could potentially be referred straight to mental health professionals in their area or who accept their health care coverage.
- This AI model serves as a valuable tool in early detection, intervention, and support for individuals experiencing mental health challenges.

## Impact

- Early Detection and Intervention: By identifying students experiencing mental health challenges at an early stage, the system allows for timely intervention. Addressing issues early can prevent them from escalating into more severe conditions, leading to better long-term outcomes for students' mental health.

- Reduced Stigma: Providing a platform for students to track and seek support for their mental health promotes open conversations and reduces the stigma surrounding mental illness. This creates a more supportive environment where students feel comfortable seeking help and discussing their mental health concerns openly.

- Enhanced Well-being: By receiving personalized support and interventions, students can better manage their mental health and overall well-being. This can lead to improved academic performance, increased resilience, and a higher quality of life for students.

- Prevention of Suicides: Early detection and intervention are key to preventing suicides among students. By identifying students at risk of suicidal ideation and connecting them with appropriate support, the system plays a crucial role in preventing tragedies and saving lives.

## Feasibility

Colleges, universities, and schools can implement mental health tracking systems to support student well-being. These systems can be integrated into existing student support services, providing students with easy access to resources, counseling, and support groups. Schools can also use these systems to identify students at risk and intervene early to prevent mental health crises.

The importance of technical expertise in AI to develop algorithms capable of analyzing user symptoms and making accurate predictions.

## Use of AI

- The proposal utilizes AI technology, specifically machine learning algorithms, to predict depression based on patient data.Tree based models are not the best for this task and linear models performed the best.
- Machine learning algorithms analyze patient data, such as medical records, to identify patterns and indicators associated with depression.
  This approach allows for the development of predictive models that can accurately assess the likelihood of depression in individuals, thereby facilitating early intervention and treatment.
- The use of AI enables the system to efficiently process large volumes of data, leading to more accurate predictions and personalized recommendations for patients.

## Alternate Ideas

- Survey-Based Screening:
  Another alternative explored was a survey-based screening tool, where individuals would complete standardized questionnaires to assess their mental health status. However, this approach may suffer from response biases and may not capture real-time changes in symptoms.

- Self-Help Resources Only:
  Initially, there was a notion to provide self-help resources exclusively to individuals identified as at risk, without incorporating predictive modeling. However, this approach may miss opportunities for early intervention.
