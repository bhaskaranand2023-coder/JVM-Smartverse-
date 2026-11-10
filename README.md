# Hi, I'm Bhaskar Anand! 👋

# 🚀 JVM Smartverse

### Where School Life Meets Artificial Intelligence.

**#TheFutureOfEducation**

JVM Smartverse is an AI-powered digital school portal developed for **Jawahar Vidya Mandir (JVM), Shyamli, Ranchi, India**. The project aims to bring essential school-related information, student services, academic resources, and interactive assistance together through a unified digital platform.

At the heart of the platform is **Shyamalian**, an AI-powered virtual school assistant designed to help students, parents, and visitors access relevant school information through natural-language conversations.

The project explores how Artificial Intelligence and web technologies can improve the accessibility, organization, and digital experience of everyday school operations.

---

## 📌 1. Project Overview

Traditional school websites often require users to navigate through multiple pages to find specific information. JVM Smartverse aims to simplify this experience by combining a structured school portal with an intelligent conversational assistant.

Instead of manually searching through different sections, users can interact with Shyamalian to find relevant information, navigate to specific website sections, and access available school services.

**Primary objectives:**

- Develop a centralized digital platform for school-related information.
- Integrate an AI-powered conversational assistant.
- Simplify access to academic and administrative information.
- Organize school events, holidays, and activities.
- Provide structured access to student-related services.
- Explore practical applications of AI in educational environments.

## ✨ 2. Key Features

### 🤖 Shyamalian — AI School Assistant

Shyamalian is the conversational AI assistant integrated into the JVM Smartverse portal.

Its intended capabilities include:

- Answering school-related questions.
- Providing information using the available school knowledge base.
- Responding to questions about fees, holidays, activities, faculty, and other school information.
- Understanding differently phrased questions.
- Supporting contextual follow-up conversations.
- Guiding users towards relevant website sections.
- Providing direct links to specific information wherever supported.

### 📅 Interactive Events Calendar

The portal includes an events calendar designed to make school activities easier to discover.

Features include:

- Monthly calendar navigation.
- Highlighted dates containing scheduled activities.
- Event information associated with individual dates.
- Multiple activities on the same date.
- School-wide and class-specific activities.
- Integration with the school's activity information.

### 🎓 Class-wise Activities and Holiday Information

The platform organizes school activities and holiday information across different classes.

The intended class coverage includes:

- LKG and UKG.
- Classes I–XII.

This helps users find relevant activities and schedules without searching through unrelated information.

### 💰 School Fee Information

The fee-information section is intended to provide access to structured school fee details.

The current data scope being prepared includes:

- Academic year 2025.
- Academic year 2026.
- Class-specific fee information, where available.
- Internal-student fee details, where applicable.
- Transportation and bus charges, where documented.

Only verified information should be presented as official fee information.

### 👨‍🎓 Student Dashboard Access

The portal includes student-record lookup functionality based on registration numbers.

Its intended capabilities include:

- Matching supplied registration numbers with available student records.
- Identifying the corresponding student record.
- Supporting access to the appropriate student dashboard.
- Handling invalid or unrecognized registration numbers.

Student information and dashboard access must remain subject to appropriate authentication and authorization controls.

### 👩‍🏫 Faculty Information

A structured faculty information section organizes available information about school faculty members.

### 🏆 Achievements

The achievements section presents school-related accomplishments and records maintained in the project's structured data.

### 📚 Timetable Management

The project includes timetable-related data and a timetable generation script to support the organization and presentation of academic schedules.

### 🌐 School Portal and Navigation

The website provides a centralized interface for accessing different school-related sections.

The portal is designed to offer:

- Organized navigation.
- Access to relevant school information.
- An integrated chatbot experience.
- Responsive website interaction across supported screen sizes.

---

## 🛠️ 3. Technology Stack

The project uses web technologies and Python-based application components.

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and content |
| CSS3 | Styling and visual presentation |
| JavaScript | Frontend functionality and interactivity |
| Tailwind CSS | Utility-first styling and responsive UI development |
| Python | Backend logic and supporting scripts |
| JSONL | Structured school and student data storage |
| AI integration | Conversational assistance through Shyamalian |

*Note: The exact AI model, API provider, backend framework, and external dependencies should be documented after verification of the final implementation.*

---

## 🏗️ 4. Project Architecture and Data Organization

The project uses a combination of frontend files, Python scripts, and structured data files.

### Main application files

| File | Description |
|---|---|
| `app_server.py` | Main Python application server |
| `index.html` | Website entry-point HTML file |
| `JVM_Shyamli_Portal.html` | School portal interface |
| `build_pages.py` | Supporting page-generation script |
| `generate_timetable.py` | Timetable-generation script |

### Structured data files

| File | Description |
|---|---|
| `achievements.jsonl` | School achievement records |
| `faculty.jsonl` | Faculty information |
| `official_sources.jsonl` | References to official information sources |
| `original_student_records.jsonl` | Original student records |
| `section_students.jsonl` | Class and section-related student records |
| `timetable.jsonl` | Timetable information |

### Documentation and deployment files

| File | Description |
|---|---|
| `audit_report.txt` | Project audit information |
| `changes_v3.txt` | Development change records |
| `ready-made_deployment.txt` | Deployment-related instructions |
| Windows startup script | Instructions or automation for Windows |
| macOS/Linux startup script | Instructions or automation for macOS and Linux |

The actual relationships between these components should be verified against the current source code.

---

## 🧠 5. AI Integration and Data Handling

A major part of JVM Smartverse is the integration of conversational AI into a school-information platform.

The goal is to make school information accessible through natural-language queries rather than relying exclusively on manual navigation.

The platform uses structured data sources to organize information such as:

- Faculty records.
- Student records.
- Achievements.
- Timetables.
- Official school references.
- Other school-related information.

The AI assistant is intended to use relevant verified information when responding to school-specific questions.

An important design principle is to avoid generating unsupported school information. When verified information is unavailable, the assistant should communicate that limitation rather than inventing an answer.

---

## 🔐 6. Deployment and Security Status

**Current deployment status:** Live website / development prototype.

The website is currently accessible online, but HTTPS and SSL/TLS security configuration have not yet been verified or completed.

The current deployment should therefore not be considered production-secure.

Security improvements to be considered before handling real student information include:

- HTTPS configuration.
- Secure authentication and authorization.
- Protection of student records.
- Secure storage of API keys and credentials.
- Input validation and server-side access controls.
- Appropriate session management.
- Protection against unauthorized dashboard access.

**Important:** The project has been developed with a zero-budget approach, using free tools and services wherever possible.

An SSL/TLS certificate does not necessarily require purchasing one. Free certificate options, such as Let's Encrypt, and free HTTPS support from some hosting providers can be explored.

Until HTTPS and the other necessary security controls are configured and verified, the live prototype should not be used to collect sensitive personal information or real student credentials.

---

## 💡 7. Development Philosophy

JVM Smartverse is built around three central ideas:

1. **Accessibility:** Making school information easier to discover.
2. **Intelligence:** Using AI to simplify interactions between users and school information.
3. **Integration:** Bringing different school-related resources into one digital environment.

The project also demonstrates how modern web development and AI tools can be applied to practical educational challenges.

---

## 🔮 8. Future Enhancements

Potential future improvements include:

- Voice-enabled interaction with Shyamalian.
- Improved chatbot accuracy and contextual understanding.
- More advanced calendar filtering and navigation.
- Enhanced student dashboard functionality.
- Secure authentication and HTTPS deployment.
- Improved mobile experience.
- Additional school information modules.
- Better data validation and administration tools.
- Expanded integration of verified school resources.

---

## ⚙️ 9. Setup and Installation

The project contains Python-based application files and platform-specific startup instructions.

The exact setup procedure depends on the current dependencies and deployment configuration.

Before publishing installation instructions, verify:

1. The required Python version.
2. The required Python packages and dependency file.
3. Any required environment variables.
4. AI API configuration.
5. The correct application entry point.
6. The Windows and macOS/Linux startup procedures.

Do not publish API keys, passwords, or other credentials in the repository.

---

## 📊 10. Project Status

| Component | Status |
|---|---|
| School website | Live prototype |
| Shyamalian AI assistant | Implemented; ongoing improvements |
| Events calendar | Included; data integration and verification ongoing |
| School information | Structured information available |
| Fee information | 2025 and 2026 data being organized and verified |
| Student dashboard | Registration-number functionality under development and verification |
| Faculty information | Structured data file available |
| Achievements | Structured data file available |
| Timetable | Data and generation scripts available |
| HTTPS security | Not yet configured or verified |

*Feature status should be updated as development and testing progress.*

---

## 👨‍💻 11. Project Credits

**Project Name:** JVM Smartverse

**Institution:** Jawahar Vidya Mandir, Shyamli

**Project Category:** Artificial Intelligence / Web Development / Educational Technology

**Project Focus:** AI-powered school information and digital services portal.

---

### Where School Life Meets Artificial Intelligence.

**#TheFutureOfEducation**
