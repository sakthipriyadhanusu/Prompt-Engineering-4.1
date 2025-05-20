# **EXP 4 – Scenario-Based Report Development Utilizing Diverse Prompting Techniques**

---

## **Lab Scenario: Smart Health Assistant System – "MediGuide"**
## REGISTER NUMBER: 212222040139

---

## **Description:**

### **Background:**

You are part of a development team working on an AI-based Smart Health Assistant named **"MediGuide"** that assists elderly patients in managing chronic diseases like **diabetes, hypertension, and arthritis**. The assistant must provide tailored health advice, medication reminders, daily tips, and emotional support through natural language conversations.

---

## **Objective:**

To develop a **scenario-based report** that demonstrates how diverse prompting techniques—**zero-shot, few-shot, chain-of-thought, role-based, and multi-modal prompts**—can be used to **optimize MediGuide’s responses** across different patient-centered use cases.

---

## **Algorithm:**

### **1. Zero-Shot Prompting**

**Use Case:** Providing a health tip without prior examples
**Prompt:**

> "Give a tip for managing arthritis pain naturally."

**Expected Response:**

> "Gentle stretching and low-impact exercises like swimming or yoga can help manage arthritis pain effectively."

---

### **2. Few-Shot Prompting**

**Use Case:** Recommending actions based on symptoms
**Prompt:**

> "Examples:
> 'I feel dizzy in the morning.' → 'Try checking your blood pressure after waking up. Dizziness could be related to low or high pressure.'
> 'My legs are swelling.' → 'Swelling in legs may indicate fluid retention. Please elevate your legs and consult a doctor.'
> Now, respond to: 'I have frequent headaches.'"

**Expected Response:**

> "Frequent headaches can be caused by high blood pressure or dehydration. Please ensure proper hydration and monitor your BP regularly."

---

### **3. Chain-of-Thought Prompting**

**Use Case:** Diagnosing medication side-effects
**Prompt:**

> "The user reports fatigue after starting a new hypertension drug.
> Step 1: Check when the medication was started.
> Step 2: Identify if fatigue is a known side effect.
> Step 3: Suggest consulting a physician if the symptom persists.
> Now, analyze: 'I feel very tired ever since I started my new BP tablets.'"

**Expected Response:**

> "Since you've started a new BP medication and are experiencing fatigue, it could be a side effect. It's best to review the start date and consult your doctor for adjustments."

---

### **4. Role-Based Prompting**

**Use Case:** Offering emotional support
**Prompt:**

> "Pretend you are a kind and empathetic virtual nurse.
> The user says: 'I feel lonely in the evenings.'"

**Expected Response:**

> "I’m here for you. It’s okay to feel lonely sometimes. Maybe we can try a relaxing routine together or talk about something that brings you joy."

---

### **5. Multi-Modal Prompting** *(text + visual reference)*

**Use Case:** Explaining a glucose chart
**Prompt:**

> "Given this glucose chart (image), explain if the patient’s sugar levels are stable."

**Expected Response:**

> "Based on the chart, your sugar levels show spikes after meals but return to normal within 2 hours. This indicates good glucose regulation. Keep monitoring consistently."

(Note: Actual implementation would require image upload and model support for visual analysis.)

---

## **Output:**

MediGuide was able to generate relevant, empathetic, and medically guided responses by adapting to each prompting technique. This enabled effective assistance in symptom analysis, emotional support, and chronic disease management.

---

## **Result:**

Thus, various prompting techniques like zero-shot, few-shot, chain-of-thought, role-based, and multi-modal were successfully implemented to enhance the functionality of the **Smart Health Assistant – MediGuide**.

