# Coding Method for the Systematic Literature Review

## 1. Overview

The coding process consisted of two stages of qualitative analysis, followed by an analysis of cross-level relationships.

1. **Identification of sustainability implementation mechanisms (RQ1)**
2. **Categorization of mechanisms into organizational levels (RQ2)**
3. **Identification of cross-level relationships (RQ3)**
4. **Classification of evidence supporting the relationships**
5. **Synthesis of recurring cross-level relationships**

The organizational levels were developed after the initial extraction. They were not predefined categories used to identify mechanisms.

## 2. Identification of Mechanisms (RQ1)

Sustainability implementation mechanisms were extracted from the empirical findings of the 39 included studies.

Mechanisms included:

- Development practices and activities
- Organizational arrangements and responsibilities
- Sustainability requirements and policies
- Practitioner actions and competencies
- Technical tools and methods
- External pressures and expectations

Mechanisms were identified based on their reported role in introducing, supporting, or integrating sustainability into software engineering.

Information mentioned only in an article's background or related work was not treated as an empirical finding of that study.

### Coding example: S11 — Energy dashboard

The study described the use of an energy dashboard in Scrum sprint reviews.

Two mechanisms were identified:

- **Energy dashboard:** A technical tool providing energy-related information.
- **Scrum sprint reviews:** A development activity in which the information was discussed.

At this stage, the mechanisms were extracted without assigning organizational levels.

## 3. Categorization of Mechanisms (RQ2)

After extraction, mechanisms were compared according to their main purpose and organizational context.

Similar mechanisms were grouped into five organizational levels.

| Organizational level | Coding definition | Examples of mechanisms |
|---|---|---|
| **Institutional** | External pressures and expectations influencing organizational sustainability priorities. | Regulations, reporting obligations, customer requirements, procurement criteria. |
| **Governance** | Organizational decisions and arrangements that define priorities, responsibilities, and resources. | Strategies, policies, management support, targets, resource allocation. |
| **Process** | Practices that integrate sustainability considerations into software development activities. | Requirements engineering, Scrum, Agile, code reviews, DevOps workflows. |
| **Behavioral** | Mechanisms related to practitioners' knowledge, competencies, awareness, and actions. | Training, collaboration, knowledge sharing, developer initiatives. |
| **Technical** | Technical practices, software properties, methods, and tools related to sustainability. | Energy monitoring, code optimization, green coding, architectural tactics. |

Mechanisms were assigned to levels according to their primary role. Where a study addressed mechanisms at several levels, those mechanisms were examined separately.

### Examples of level assignment

| Study | Identified mechanism | Assigned level | Reason for classification |
|---|---|---|---|
| S12 | Regional sustainability objectives and funding | Institutional | External conditions influencing the project. |
| S12 | Organizational approval of an IT project | Governance | Organizational decision-making and resource commitments. |
| S19 | Developer-initiated sustainability practices | Behavioral | Sustainability-related activities initiated by practitioners. |
| S11 | Scrum sprint reviews | Process | An established software development workflow. |
| S11 | Energy dashboard | Technical | A tool providing energy-related measurements. |
| S32 | Sustainability analysis framework used in a design exercise | Process | A structured method for examining sustainability concerns and identifying feature proposals. |

These classifications describe the role of each mechanism, not whether sustainability implementation was successful.

## 4. Identification of Cross-Level Relationships (RQ3)

After categorizing the mechanisms, the studies were examined for reported relationships between mechanisms at different organizational levels.

A relationship was coded when the study's findings explicitly connected mechanisms operating at two different levels.

For each relationship, the analysis identified:

- **Source level:** The organizational level from which the reported relationship originated.
- **Destination level:** The organizational level to which the mechanism was connected.
- **Connecting mechanism:** How sustainability-related information, decisions, or activities were linked between the levels.
- **Direction:** The direction reported or proposed in the study.
- **Supporting evidence:** The empirical finding, reported association, or proposal supporting the relationship.

The presence of mechanisms at several levels within the same study was not considered sufficient evidence of a relationship.

### Coding example 1: S12 — Institutional → Governance

**Reported finding:** Regional sustainability objectives and funding were connected to organizational approval and implementation of an IT project.

**Mechanisms:**
- Regional sustainability objectives and funding: Institutional
- Project approval and organizational decision-making: Governance

**Coded relationship:** Institutional → Governance

**Connecting mechanism:** External sustainability objectives and funding influenced organizational project decisions.

### Coding example 2: S19 — Behavioral → Process

**Reported finding:** Employees in one organization initiated sustainability-related development practices without explicit management guidance.

**Mechanisms:**
- Employee initiative: Behavioral
- Sustainability-related development activities: Process

**Coded relationship:** Behavioral → Process

**Connecting mechanism:** Practitioner initiatives introduced sustainability considerations into development work.

This relationship was supported by practitioner reports. It was not treated as proof of sustained organizational adoption.

### Coding example 3: S11 — Technical → Process

**Reported finding:** Energy-dashboard information was incorporated into Scrum sprint reviews.

**Mechanisms:**
- Energy dashboard: Technical
- Scrum sprint reviews: Process

**Coded relationship:** Technical → Process

**Connecting mechanism:** Technical measurements were brought into an existing development workflow.

### Coding example 4: S32 — Process → Technical

**Reported finding:** A sustainability framework was evaluated in a design exercise and supported the identification of additional sustainability goals and proposed software features.

**Mechanisms:**
- Sustainability analysis: Process
- Proposed software features: Technical

**Coded relationship:** Process → Technical

**Connecting mechanism:** A structured sustainability analysis was used to develop technical feature proposals.

The study did not demonstrate deployment of the proposed features.

## 5. Coding Longer Pathways

Some studies described longer pathways involving three or more organizational levels.

To compare findings across studies, longer pathways were examined as separate two-level relationships.

For example, a reported pathway:

**Institutional → Governance → Behavioral → Process**

was examined as:

1. Institutional → Governance
2. Governance → Behavioral
3. Behavioral → Process

Each connection was coded only when supported by the study's findings or explicitly proposed by the authors.

The connections were not assumed to represent an observed chronological sequence.

This approach allowed relationships from different studies to be compared without requiring identical longer pathways.

## 6. Classification of Relationship Evidence

Each identified relationship was classified according to the evidence supporting it.

| Evidence category | Definition | Illustrative study |
|---|---|---|
| **Documented** | Connected mechanisms were documented as being used in organizational operations or development activities. | S11: Energy-dashboard information incorporated into Scrum reviews. |
| **Partial** | The relationship was supported by practitioner reports, statistical associations, or evaluation of part of a pathway without demonstrating the complete relationship in operation. | S19: Practitioner-reported sustainability activities; S32: Evaluated framework producing feature proposals. |
| **Proposed** | The connection was suggested or recommended but its operational implementation was not demonstrated. | S36: Proposed CSR-related pathway connecting organizational policies, training, development practices, and technical activities. |

All three evidence categories were included in the relationship synthesis.

The classification concerns the evidence supporting a relationship. It is not a general assessment of the methodological quality of the study.

Documented evidence does not necessarily demonstrate causality, sustained use, or measurable sustainability improvements.

## 7. Synthesis of Recurring Relationships

After identifying and classifying individual relationships, the relationships were compared across the included studies.

Relationships with the same source and destination levels were grouped together.

For example, reported relationships connecting Governance to Process were grouped under:

**Governance → Process**

Each study was counted once per relationship type, although an individual study could contribute to several types.

The final synthesis identified the most frequently reported cross-level relationships and their supporting studies. These are presented in Table III of the manuscript.

The relationship counts include documented, partially supported, and proposed connections. They describe how frequently relationships were identified in the reviewed literature, not how frequently successful implementation occurred in practice.

## 8. Coding Boundaries and Limitations

The following principles were used to distinguish the types of evidence:

- Mechanisms operating at different levels were not automatically considered connected.
- A proposed relationship was not classified as documented implementation.
- Practitioner-reported activities were distinguished from directly documented operational use.
- Statistical associations were not interpreted as demonstrated causal relationships.
- Longer pathways were divided into individual relationships only when their connections were supported.
- A study could contribute to several relationship categories but was counted only once within each category.
- The presence of a mechanism did not establish successful or sustained sustainability implementation.

The coding involved interpretative decisions. The supporting study findings and extracted evidence were retained to allow the classifications to be reviewed and validated.

**Note:** This document describes the coding procedure and categories developed and adjusted during the review.
